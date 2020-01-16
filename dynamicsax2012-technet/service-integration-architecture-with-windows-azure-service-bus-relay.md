---
title: Service integration architecture with Windows Azure Service Bus Relay
TOCTitle: Service integration architecture with Windows Azure Service Bus Relay
ms:assetid: f7b102b5-b8c4-4e96-92ad-f287bf81fc8f
ms:mtpsurl: https://technet.microsoft.com/library/Dn720290(v=AX.60)
ms:contentKeyID: 62221430
author: Khairunj
ms.date: 04/25/2014
mtps_version: v=AX.60
---

# Service integration architecture with Windows Azure Service Bus Relay 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012.</P>



Leveraging the power of Windows Azure cloud computing, the Application Integration Framework (AIF) enables communication between the Microsoft Dynamics AX 2012 enterprise environment and an external client application by using the Windows Azure Service Bus Relay. This solution requires only the following infrastructure: Microsoft Dynamics AX 2012 components, Internet Information Services (IIS), and Microsoft Active Directory Federation Services (AD FS). Setup is a one-time process that involves configuration of a Service Bus namespace, Windows Azure Access Control Services, and Microsoft AD FS as a Security Token Service (STS). After setup, AX 2012 services can be deployed via AIF by using the Service Bus adapter.

The Service Bus Relay marshals service requests and responses to the enterprise environment behind the firewall. The enterprise environment uses Application Integration Framework (AIF), the Windows Azure Service Bus adapter, and Internet Information Services (IIS) 7.5 or later versions. The AD FS acts as a Security Token Service (STS) for the application and establishes trust with the Access Control Services (ACS). The Service Bus receives service calls over HTTP from the client application. Each Service Bus namespace has an associated ACS configuration which authenticates service calls. The client application must send user credentials to AD FS to begin the secure communication process.

The client application prompts the user for credentials and creates an authentication request using Windows claims-based authentication for the AD FS. For more information about AD FS, see [Active Directory Federation Services](http://go.microsoft.com/fwlink/?linkid=194245). The client calls the AD FS Security Token System (STS) with the AD FS credentials and obtains a Security Assertion Markup Language (SAML) token. The SAML token is signed but unencrypted because the same token is used on premises by the custom authentication component to identify the calling user. The ACS is configured depending on AD FS settings.

Application Integration Framework (AIF) publishes the services by using the Service Bus adapter. As part of publishing the service, AX 2012 deploys a Windows Communication Framework (WCF) routing service onto IIS 7.5. For more information, see [Publishing a service by using the Windows Azure Service Bus adapter](publishing-a-service-by-using-the-windows-azure-service-bus-adapter.md).

The following diagram illustrates the calls from a client application that uses the Service Bus to make calls to X++ services that are running on AX 2012 in an enterprise network behind a firewall.

![Windows Azure integration diagram](images/Dn720290.AIFcu6_WASB-adapter-architecture(AX.60).jpg "Windows Azure integration diagram")

The following steps describe the authentication process and the service call and response.

1.  The client application sends user credentials to AD FS. The client calls the AD FS STS with the user credentials and requests a SAML token.  The SAML token is signed but unencrypted, because it will be used by AX 2012 to identify the user.

2.  The computer that is running AD FS sends token A to the client.

3.  The client sends token A (the SAML token) to ACS.

4.  ACS verifies that the SAML token corresponds to a user who has permissions to call the Service Bus, and then sends token B to the client application. Token B is a Single Web Token (SWT) that has the claim required to make the service call to the Service Bus.

5.  The client calls the Service Bus and passes tokens A and B and also the service request. The Service Bus consumes the SWT (token B), but allows the SAML token (token A) stored in a custom header to pass through. The SAML token is used by an authentication component hosted in IIS.

6.  The Service Bus relays the SAML token and service message through to the WCF routing service. Because the WCF routing service has established an outbound connection to the Service Bus, messages from the Service Bus are enabled through the firewall.

7.  The AOS receives the SAML token and the service message from the WCF Routing service.
    
    An authentication component for the service is invoked by IIS as part of the authentication process. The authentication component performs the following steps when it processes the message:
    
      - Reads the custom header from the message.
    
      - Extracts the SAML token from the custom header.
    
      - Validates the token by verifying that the signature of the token matches the signature expected by the AD FS STS.
    
      - Extracts the claims from the token.
    
      - Creates the claims identity and principal and sets them on the security context of the message.
    
    An AIF extension obtains the user identity from the message security context and includes it in the header of the message being forwarded to the AOS. The AOS authenticates the caller that is specified in the message header.

8.  The AOS processes the service call and sends the Response message to the WCF routing service hosted in IIS.

9.  The WCF routing service sends the service response back through the Service Bus.

10. The Service Bus sends the service response back to the client.

## See also

[Service Bus Overview](http://go.microsoft.com/fwlink/?linkid=302333%26clcid=0x409)

[How to Authenticate Web Users with Azure Active Directory Access Control](http://www.windowsazure.com/en-us/develop/net/how-to-guides/access-control/)

  


