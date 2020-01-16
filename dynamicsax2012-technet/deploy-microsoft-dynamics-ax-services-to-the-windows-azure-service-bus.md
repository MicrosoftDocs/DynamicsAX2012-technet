---
title: Deploy Microsoft Dynamics AX Services to the Windows Azure Service Bus
TOCTitle: Deploy Microsoft Dynamics AX Services to the Windows Azure Service Bus
ms:assetid: cf55c0d5-b12b-4f42-a157-c1dd9508ed3f
ms:mtpsurl: https://technet.microsoft.com/library/Dn720289(v=AX.60)
ms:contentKeyID: 62221428
author: Khairunj
ms.date: 04/29/2014
mtps_version: v=AX.60
---

# Deploy Microsoft Dynamics AX Services to the Windows Azure Service Bus 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012.</P>



The Windows Azure Service Bus adapter and the Service Bus configuration forms are included with cumulative update 6 for Microsoft Dynamics AX 2012.

With cumulative update 6 for Microsoft Dynamics AX 2012, you can configure Application Integration Framework (AIF) to use the Windows Azure Service Bus for integration with external applications. In other words, you can develop client applications that communicate with Microsoft Dynamics AX 2012 by using the Internet. The Service Bus acts as a message relay to pass service messages sent over the Internet to Microsoft Dynamics AX service endpoints on a private network and return the message responses to the client application.

To publish a Microsoft Dynamics AX 2012 service that listens to messages from the Service Bus you must configure a Service Bus namespace and register that namespace with AIF. You must also enable authentication. The Service Bus requires each on-premises service to be authenticated and authorized to listen on a particular address before establishing a new relay connection. Clients must also be authenticated and authorized before the Service Bus relays messages on their behalf. The Service Bus relies on the Windows Azure Access Control Services (ACS) for authenticating clients. Therefore, you must also configure trust relationships between the ACS and your security system. You can configure trust relationships by using Active Directory Federation Services (AD FS).

This topic describes the following steps which summarize the actions you must take to configure an environment to deploy Microsoft Dynamics AX services to the Service Bus:

1.  Configure AD FS or contact the administrator of an existing AD FS and request that your ACS namespace be added as a relying party application.

2.  Obtain the thumbprint of the X.509 token signing certificate that is used as the digital signature by the Security Token Service (STS) running on the AD FS.

3.  Configure ACS. You must configure the ACS with the parameters related to the relying party in addition to the identity provider and rule groups that include a claim rule for the identity provider. For more information, see [How to: Use ACS Management Service to Configure AD FS 2.0 as an Enterprise Identity Provider](https://go.microsoft.com/fwlink/?linkid=317708).

4.  Enable authentication. You must set up trust relationships between Service Bus and AD FS and between Microsoft Dynamics AX and the Service Bus.

5.  Configure the Service Bus parameters in Microsoft Dynamics AX. You must register the Service Bus namespace with AIF and enter authentication parameters by using the Microsoft Dynamics AX client.

6.  Create an enhanced integration port that uses the Service Bus adapter.

For a code sample that implements a mobile application that uses the Service Bus, see [Developing Secure Mobile Apps for Microsoft Dynamics AX 2012](https://go.microsoft.com/fwlink/?linkid=393709%26clcid=0x409).

## Prerequisites

Verify that the following steps are completed before you begin to configure the environment to deploy the Service Bus to publish Microsoft Dynamics AX services over the Internet:

  - Install Microsoft Dynamics AX web services on Internet Information Services (IIS). You must use IIS 7.5 or later versions. For more information, see Install web services on IIS.

  - Install cumulative update 6 for Microsoft Dynamics AX 2012, or Microsoft Dynamics AX 2012 R3, or the [AIF Microsoft Azure Service Bus hotfix](https://go.microsoft.com/fwlink/?linkid=393710%26clcid=0x40).

  - Configure a Microsoft Azure account. For more information, see [Microsoft Azure web site](https://go.microsoft.com/fwlink/?linkid=313634).

  - Create a new Service Bus namespace. For more information, see [How To: Create or Modify a Service Bus Service Namespace](https://go.microsoft.com/fwlink/?linkid=313633). The Service Bus uses ACS to implement Federated Authentication. A buddy namespace is created for the ACS when you create the Service Bus namespace. For example, if you create a Service Bus namespace contosomobile, the buddy namespace is contosomobile-sb.

  - Place the file Microsoft.ServiceBus.dll (v1.8) in the **Bin** folder of the web site where you deployed the service. The Microsoft.ServiceBus.dll is included with the Microsoft Azure Software Development Kit (SDK). To download the SDK, see [Microsoft Azure SDK Download Page](https://go.microsoft.com/fwlink/?linkid=313636).

## Configure AD FS

To configure authentication that MSDAX requires for clients that use the Service Bus as a message relay, you need the following:

  - The federation metadata URL or the file that is available from your configured AD FS server.

  - The thumbprint of the X.509 token-signing certificate that is used by the Federation Service.

Use the information in the following articles to configure the AD FS.

  - [Deploying Federation Servers](https://go.microsoft.com/fwlink/?linkid=393711%26clcid=0x409)

  - [Configure a New Federation Server](https://go.microsoft.com/fwlink/?linkid=393712%26clcid=0x409)


> [!IMPORTANT]
> <P>If you do not set up your own AD FS, you can contact the administrator of an existing AD FS and request that your ACS namespace be added as a relying party application.</P>



## Obtain the thumbprint of the X.509 token-signing certificate

For more information about token signing certificates, see [Certificate Requirements for Federation Servers](https://technet.microsoft.com/library/dd807040\(v=ws.10\).aspx) and [Add a Token-Signing Certificate](https://technet.microsoft.com/library/dd807039\(v=ws.10\).aspx).

### To obtain the thumbprint of the X.509 token-signing certificate

1.  Click **Start** \> **Administrative Tools** \> **AD FS 2.0 Management** to open the AD FS 2.0 Management tool.

2.  Expand the **Service** node and then click **Certificates**.

3.  Right-click the token-signing certificate in the **Certificates** list and then click **View Certificate…**

4.  On the **Details** tab of the **Certificate** form, copy the **Thumbprint** value and save it to a file. Remove the spaces between pairs of characters.
    
    This is the value for the thumbprint that you will enter when you register your Service Bus namespace in AIF by using the **Mobile Authentication Configuration** form in Microsoft Dynamics AX 2012 R2.

## Configure ACS

Use the following steps to configure the ACS with the parameters that relate to the relying party. This includes the identity provider and rule groups.

### To Configure the ACS

1.  Open your [Windows Azure dashboard](https://manage.windowsazure.com/error/nosubscriptions#workspace/all/dashboard).

2.  Click **Service Bus** and select the namespace that you want to configure, and then click **Access key** on the Action Pane.

3.  In the form that opens, click the **Open ACS Management Portal** link.

4.  On the **Access Control Service** page, click **Identity providers**.

5.  Select **WS-Federation identity provider (e.g. Microsoft AD FS 2.0)** and then click **Next**.

6.  In the **Display name** box, enter a name for your identity provider.

7.  Enter the WS-Federation metadata for your server. You can use the file FederationMetadata.xml from your federation server, or you can enter the URL that points to the file if your Federation Service has an Internet-facing IP address.
    
    The file FederationMetadata.xml is located at a URL that resembles the following:
    
      - https://\<FederationServiceComputerName\>/FederationMetadata/2007-06/FederationMetadata.xml
    

    > [!WARNING]
    > <P>Make sure to check the box <STRONG>Require URLs in metadata to use HTTPS (recommended)</STRONG>.</P>



8.  Select the **Service Bus** box in the **Used By** section under **Relying party applications**.

9.  Click the **Service Bus** link. Ensure that the value for the URL is valid for your application. In the **Token format** box, enter **SWT**.

10. Configure the Authentication Settings.
    
    ### To configure Authentication Settings
    
    1.  Select the name of the identity provider that you created to use with the relying party.
    
    2.  Select the **Default Rule Group for ServiceBus** box to use the default rule group.

11. Configure the default rule group. You must configure the Send action to use the Windows account name for the input claim type.
    
    ### To configure the default rule group
    
    1.  Click **Rule Groups** and then select the **Default Rule Group for ServiceBus** box.
    
    2.  View the predefined rules that have **Access Control Service** as the claim issuer value. Click each rule to view the values. These rules have **owner** as the **Input claim** value, and **Listen**, **Manage**, or **Send** as the **Output claim** value.
    
    3.  Delete the rules that have **Output claim** values of **Manage** and **Send**.
    
    4.  Select your identity provider name.
    
    5.  Under **Input claim type**, select the **Select type** option, and then select the following URI:
        
        http://schemas.microsoft.com/ws/2008/06/identity/claims/windowsaccountname
        
        Do not change the values in the **Input claim value** section.
    
    6.  In the **Enter Type:** box for **Output claim type**, enter **net.windows.servicebus.action**.
    
    7.  In the **Enter value:** box for **Output claim value**, enter **Send**.
    
    8.  Click **Save**.

12. If you are managing your AD FS server, update the relying party federation metadata.
    
    ### To update the relying party federation metadata
    
    1.  Open the AD FS 2.0 Management tool and expand the **AD FS 2.0\\Trust Relationships \>** node.
    
    2.  Select the **Relying Party Trusts** to display the list of **Relying Party Trusts**.
    
    3.  Right-click the relying party that you added and then click **Update from Federation Metadata**.

## Enable Authentication

The Service Bus requires each on-premises service to be authenticated and authorized to “listen” on a particular address before establishing a new relay connection. Clients must also be authenticated and authorized before the Service Bus relays messages on their behalf. The Service Bus relies on ACS for authenticating clients.

Microsoft Dynamics AX services use a shared secret token provider to authenticate with the Service Bus. You provide the shared secret to AIF when you register your Service Bus namespace.

The following two types of client authentication are required:

  - **Service Bus authentication** - Clients are required to provide a send claim in order to be able to send messages to a service on the Service Bus. The ACS must trust the identity provider that is used by the client. You must set up and configure ACS with the parameters that relate to the relying party

  - **Microsoft Dynamics AX authentication** - When the Service Bus relays a message to the on-premises service, the caller identity is used to log on to Microsoft Dynamics AX. This caller identity is determined by calling a custom authentication component to parse the incoming message token and to provide a valid claims identity. The user specified by the claims identity must be a valid Microsoft Dynamics AX user.

## Create a custom authentication component

A custom authentication component has two parts:

  - An X++ class that implements the AifAuthenticationManager interface and provides configuration information.

  - A .NET class that implements the System.ServiceModel.ServiceAuthenticationManager and the System.IdentityModel.Policy.IAuthorizationPolicy interface to provide runtime authentication.

## Create the X++ class that implements the AifAuthenticationManagerInterface

The AifAuthenticationManagerInterface is used by the services framework to obtain information that is used to configure and deploy the custom authentication runtime component.

The following code shows the interface. The interface methods are described in comments.

```
     interface AifAuthenticationManager
    {
        AifAuthenticationManagerName getName(); // Returns the friendly name of the component that is displayed in the Windows Azure ServiceBus configuration form.
    
        str getAuthenticationManagerType(); //Returns the .NET type of the WCF custom authentication class in the runtime assembly.
    
        str getAuthorizationPolicyType();  //Returns the .NET type of the WCF authorization policy class in the runtime assembly.
    
        AifAssemblyName getAuthenticationManagerAssemblyName(); //Returns the name of the authentication assembly that contains the WCF custom authentication class.
    
        Map getAppSettings(); //Returns custom settings that are required by the .net authentication component at authentication time. These settings are available in the AppSettings section of the web.config file, which is located in the IIS website directory. Returns null if app settings are not required.
    
        MenuItemNameDisplay getConfigurationDisplayMenuItem; //the name of the display menu item for the configuration form of this component. Returns the empty string if no configuration form is available.
    
    }
```

## Create the .NET authentication component

A .NET class that implements the following interfaces can perform custom authentication:

  - System.ServiceModel.ServiceAuthenticationManager

  - System.IdentityModel.Policy.IAuthorizationPolicy

The System.ServiceModel.ServiceAuthenticationManager interface contains the ReadOnlyCollection method that inspects the request message and headers, performs the custom authentication, and sets the authenticated principal on the message as a property.

The following code shows the signature of the ReadOnlyCollection method.

```
    ReadOnlyCollection<IAuthorizationPolicy> Authenticate(
        ReadOnlyCollection<IAuthorizationPolicy> authPolicy, 
        Uri listenUri, 
        ref Message message)
```

The System.IdentityModel.Policy.IAuthorizationPolicy interface contains the Evaluate method shown in the following example:

    bool Evaluate(  
    EvaluationContext evaluationContext,
    ref Object state
    )

You implement the Evaluate method to set the authenticated principal and identity on the security context of the message.

The following example shows an implementation of the .NET authentication components.

    using System;
    using System.ServiceModel;
    using System.Collections.ObjectModel;
    using System.Security.Principal;
    using System.IdentityModel.Policy;
    using System.ServiceModel.Channels;
    using System.IdentityModel.Claims;
    using System.Collections.Generic;
    using System.Threading;
    using System.Diagnostics;
    using System.Security.Authentication;
    
    namespace Mobile.WebService.Security
    {
        class Constant
        {
            internal const string AnonymousIdentity = "Anonymous";
            internal const string PrincipalProperty = "Principal";
            internal const string IdentitiesProperty = "Identities";
            internal const string SecurityTokenHeaderName = "PassthroughBinarySecurityToken";
            internal const string SecurityTokenHeaderNamespace = "";
            internal const string EventLogSource = "Dynamics AX Services (IIS)";
            internal const string SvcFileName = "xppservice.svc";
        }
    
        class AuthenticationManager : ServiceAuthenticationManager
        {
            public override ReadOnlyCollection<IAuthorizationPolicy> Authenticate(ReadOnlyCollection<IAuthorizationPolicy> authPolicy, Uri listenUri, ref Message message)
            {
                IPrincipal principal = null;
    
                try
                {
                    // Check if this is the service endpoint
                    if (listenUri.ToString().EndsWith(Constant.SvcFileName, StringComparison.OrdinalIgnoreCase))
                    {
                        // Service endpoint should receive the security token
                        principal = AuthenticationHelper.Authenticate(listenUri, message.Headers, message.Properties);
                    }
                    else
                    {
                        // Metadata endpoint will not receive the token, but still needs an identity 
                        GenericIdentity genericIdentity = new GenericIdentity(Constant.AnonymousIdentity);
                        principal = new GenericPrincipal(genericIdentity, null);
                    }
    
                    // Set the principal on the message
                    message.Properties[Constant.PrincipalProperty] = principal;
                }
                catch (Exception ex)
                {
                    EventLog.WriteEntry(Constant.EventLogSource, String.Format("Authentication failed: {0}\n{1}", ex.Message, ex.ToString()), EventLogEntryType.Warning);
                    // Throw generic exception -- do not expose internal details.
                    throw new AuthenticationException("Authentication failed.");
                }
    
                return authPolicy;
            }
        }
    
        class AuthorizationPolicy : IAuthorizationPolicy 
        {
            // Called after the authentication stage
            public bool Evaluate(EvaluationContext evaluationContext, ref object state) 
            {
                IPrincipal principal = null; 
    
                if (OperationContext.Current.IncomingMessageProperties.Keys.Contains(Constant.PrincipalProperty))
                {
                    principal = OperationContext.Current.IncomingMessageProperties[Constant.PrincipalProperty] as IPrincipal;
    
                    // Set the Principal and Identity on the security context of the message
                    if (principal != null)
                    {
                        evaluationContext.Properties[Constant.PrincipalProperty] = principal;
                        evaluationContext.Properties[Constant.IdentitiesProperty] = new List<IIdentity> { principal.Identity };
                    }
                }
    
                return true;
            }
    
            public ClaimSet Issuer
            {
                get { return ClaimSet.System; }
            }
    
            public string Id
            {
                get 
                {
                    return this.GetType().FullName;
                }
            }
        }
    }

## Register the authentication component

Before an authentication component can be used, it must be registered with the Services framework. The registerAuthenticationManager and unregisterAuthenticationManager methods on the AifAuthenticationHelper class must be used to register and unregister the authentication component. You create an X++ job that calls these X++ methods to register and unregister the authentication components. When a component is registered, the .NET assembly is uploaded to the database so that it can be accessed by all AOS instances. You must grant read permission to the AOS service account to the file path that contains the component so that the file can be uploaded to the database.

For more information about the AOS service account, see the following topics:

  - [Install an AOS instance](install-an-aos-instance.md)

  - [Change the account used by AOS](change-the-account-used-by-aos.md)

The following code shows the signature for the registerAuthenticationManager method:

```X++
    static public void registerAuthenticationManager(
        AifAuthenticationManagerClass authenticationManagerClass, // Class ID of the X++ authentication manager class that implements the AifAuthenticationManager interface.
    
        FilePath assemblyFolder, //path of the folder that contains the .net authentication manager assembly.
    
        boolean updateExisting = false //flag indicating that any existing assembly in the database should updated with the assembly in the folder. 
    )
```

The method unregisterAuthenticationManager takes one parameter authenticationManagerClass that is the class ID of the X++ authentication manager class.

## Create and configure encryption key containers

Encryption is used to protect confidential data in the web.config file. This requires al RSA encryption key container to be created and configured on all the computers involved in the message relay. For more information, see [Walkthrough: Creating and Exporting an RSA Key Container](https://msdn.microsoft.com/library/2w117ede\(v=vs.80\).aspx).

You use the Internet Information Services (IIS) configuration utility aspnet\_regiis.exe to manage the key containers. For more information, see [ASP.NET IIS Registration Tool (aspnet\_regiis.exe)](https://go.microsoft.com/fwlink/?linkid=314235).

### To create and configure encryption key containers

1.  In a folder on the computer that is running IIS 7.5, use the following command to create an RSA key container called MyKey for export.
    
    aspnet\_regiis -pc "MyKey" -exp

2.  Type the following text at a command prompt to export the key container to an XML file that is named MyKey.xml.
    
    aspnet\_regiis -px "MyKey" "MyKey.xml" -pri

3.  Import the key container into each computer that is participating in your cloud application scenario. This includes the computers that are running IIS and the computer where the AOS is running.
    
    Use the following command on each computer to import the key container XML file that you exported.
    

    > [!IMPORTANT]
    > <P>Be sure to delete the XML file from each computer after you have imported it. This is important to prevent unauthorized access to the key container.</P>

    
    aspnet\_regiis -pi "MyKey" "MyKey.XML"

4.  On each computer, grant the appropriate user access to the key container. The user you grant access to depends on the role of the computer.
    
      - On the computer that is running IIS, you grant access to the AppPool identity (which is the same as the BC proxy user). For example, enter the following command to grant access to the AppPool domain user: aspnet\_regiis –pa “MyKey” "domain\\user".
    
      - On the AOS computer, you grant access to the AOS account. This is either a domain account or the Network Service account. For example, enter the following command on the AOS computer to grant access to the Network Service account: aspnet\_regiis –pa “MyKey” "NT AUTHORITY\\NETWORK SERVICE".

## Register the Service Bus namespace with AIF and configure authentication parameters

### To set up AIF to work with the Service Bus

1.  Open the Microsoft Dynamics AX 2012 R2 client and then click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Windows Azure Service Bus Configuration**.

2.  In the **Windows Azure service namespace** box, enter the namespace that you created.

3.  In the **Windows Azure service key issuer name** box, enter the default issuer name. In the **Windows Azure service key issuer secret** box, enter the secret key. For more information, see the section “To obtain the security credentials for a service namespace” in the topic [How To: Create or Modify a Service Bus Service Namespace](https://go.microsoft.com/fwlink/?linkid=313633).

4.  In the **Deployment web site** box, enter the name of the IIS web site where the service is to be deployed.

5.  In the **Class name** box, enter the name of the X++ authentication class that you created to provide configuration information. For more information about how to create authentication classes, see Create the X++ Authentication Class.

6.  In the **RSA Key Container Name** box, enter the name for the RSA key container.

7.  Click **Configure** to open the **Mobile Authentication Configuration** form and enter the trusted issuer name and the trusted issuer thumbprint for the X.509 certificate, and then click **Close**.

## To publish the service by using the Service Bus adapter

To publish your service and make it available on the Service Bus, create an enhanced integration port that uses the Service Bus adapter.

### To create an integration port that uses the Service Bus adapter

1.  Click **System Administration** \> **Services and Application Integration Framework** \> **Inbound Ports** and then click **New** to create a new port.

2.  Type the name of the port. It is a best practice to incorporate the name that you used for the Service Bus namespace on the **Windows Azure Service Bus Configuration** form.

3.  Enter a description of the services that this port hosts.

4.  Select **Windows Azure Service Bus** for **Adapter**.

5.  Click the Down Arrow key for **URI:** to open the **Select Windows Azure Service Bus namespace** form.

6.  Select the namespace that you created.

7.  Click **Ok** to close the form.

8.  Click **Service Operations** and find the service that you have created.

9.  Select all of the operations on your service that you want to publish in the right-hand pane and move them to the left-hand pane by using the **\<** button.

10. Select the new port in the **Inbound Ports** form and then click **Activate**.
    
    Your service is now published to IIS 7.5. The URL to access the Microsoft Dynamics AX service through the Service Bus is displayed in the **URI:** field.

## See also

[Understanding the Windows Azure Management Portal](https://go.microsoft.com/fwlink/?linkid=313635)

[Service Bus Authentication and Authorization with the Access Control Service](https://msdn.microsoft.com/library/windowsazure/hh403962.aspx)

[How to Use the Service Bus Relay Service](https://go.microsoft.com/fwlink/?linkid=393026%26clcid=0x409)

[Service Bus Overview](https://go.microsoft.com/fwlink/?linkid=302333%26clcid=0x409)

  


