---
title: Publishing a service by using the Windows Azure Service Bus adapter
TOCTitle: Publishing a service by using the Windows Azure Service Bus adapter
ms:assetid: 16b6d55c-3d9f-4aaf-b319-982cc75e10f8
ms:mtpsurl: https://technet.microsoft.com/library/Dn720288(v=AX.60)
ms:contentKeyID: 62221429
author: Khairunj
ms.date: 04/25/2014
mtps_version: v=AX.60
---

# Publishing a service by using the Windows Azure Service Bus adapter 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012.</P>



The Windows Azure Service Bus adapter extends the existing Application Integration Framework (AIF) functionality and uses Internet Information Services (IIS) 7.5 to provide a method to deploy services by using cloud computing. The AIF Service Bus adapter provides a Service Bus listener, hosts the listener in IIS, and routes messages to the AIF service that was deployed using the adapter. The following infrastructure helps accomplish this:

  - IIS 7.5
    
    The Service Bus adapter uses IIS to host Microsoft Dynamics AX 2012 services published by using the Service Bus adapter. IIS hosts the Service Bus listener and a routing service that work in tandem to pass messages from the Service Bus to Microsoft Dynamics AX 2012. Both the listener and the routing service are Windows Communication Foundation (WCF) services.

  - Authentication Classes
    
    Each call to AX 2012 services through the Service Bus must be authenticated. By using the Service Bus adapter, the AIF now enables registering authentication classes to authenticate inbound Service Bus messages and extract the user’s AX 2012 credentials. Registering authentication classes is a one-time configuration step, and the authentication classes can be used across multiple Service Bus namespaces and published services after they are registered.

  - AIF Service Bus Namespace Registration
    
    Registering a Service Bus namespace is a one-time step for each namespace you want to use. Registration includes supplying the namespace name, access key credentials, authentication classes, and X.506 signing certificate that is used to sign the ADFS SAML token. The AIF uses all these to establish trust with the Service Bus before opening a connection.

  - AIF Service Bus Adapter
    
    After you have registered a Service Bus namespace with AIF, you can begin publishing Microsoft Dynamics AX 2012 services by using the AIF Service Bus adapter. The process of publishing AIF services has not changed. First, you create a new port by using the **Inbound Ports** form. Next, you select the AIF Service Bus adapter, and then select the service operations to expose on the port. After you activate the port, your service can be accessed from the cloud.

For detailed steps to deploy this infrastructure, register the namespace with AIF, and create an inbound port that uses the Service Bus adapter, see [Deploy Microsoft Dynamics AX Services to the Windows Azure Service Bus](deploy-microsoft-dynamics-ax-services-to-the-windows-azure-service-bus.md).

To read complete walkthroughs of a scenario that uses the Service Bus adapter to communicate with AX 2012 from a mobile client application, see [Developing secure mobile applications for Microsoft Dynamics AX 2012](https://go.microsoft.com/fwlink/?linkid=391769%26clcid=0x409).

## See also

[Adapters](adapters.md)

[Service Bus Overview](https://go.microsoft.com/fwlink/?linkid=302333%26clcid=0x409)

  


