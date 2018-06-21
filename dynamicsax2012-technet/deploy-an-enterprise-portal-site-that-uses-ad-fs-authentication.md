---
title: Deploy an Enterprise Portal site that uses AD FS authentication
TOCTitle: Deploy an Enterprise Portal site that uses AD FS authentication
ms:assetid: 2de9bc47-e66f-49d6-ab97-b09b83422f94
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn621030(v=AX.60)
ms:contentKeyID: 61078356
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Deploy an Enterprise Portal site that uses AD FS authentication [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to deploy Enterprise Portal for Microsoft Dynamics AX in an Active Directory Federation Services (AD FS) environment. AD FS simplifies access to systems and applications by using a claims-based authorization mechanism to help maintain application security. AD FS supports web single sign-on technologies that help IT organizations collaborate across organizational boundaries. AD FS is a server role in Windows Server 2008 R2 and Windows Server 2012. For more information about AD FS, see [Active Directory Federation Services](http://go.microsoft.com/fwlink/?linkid=389356).

This topic includes the following sections.

  - Before you begin

  - Pre-installation tasks

  - Install Enterprise Portal binaries

  - Enable SharePoint Claims to Windows Token Service

  - Create a claims-aware Enterprise Portal site

  - Register an SSL certificate on the AD FS server

  - Install Active Directory Federation Services 2.0

  - Add a trusted relying party

  - Manage the AD FS token-signing certificate

  - Specify the claims provider in SharePoint

  - Register the AD FS signing certificate as a trusted root authority with SharePoint

  - Create a new user for AD FS authentication

  - Assign security roles for users

  - Validate AD FS configurations

  - Troubleshooting AD FS issues

  - Specify which trusted identity provider is available for users at logon

## Before you begin

Complete the following tasks before you install Enterprise Portal.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Install Microsoft Dynamics AX hotfixes for claims-mode authentication (required for Microsoft Dynamics AX 2012 R2 or earlier; not required for Microsoft Dynamics AX 2012 R3).</p></td>
<td><ol>
<li><p><a href="http://go.microsoft.com/fwlink/?linkid=294944">Download</a> and install the Microsoft Dynamics AX 2012 claims-mode authentication hotfix (KB 2823664).</p></li>
<li><p><a href="http://go.microsoft.com/fwlink/?linkid=294677">Download</a> and install the Microsoft Dynamics AX 2012 R2 claims-mode authentication hotfix (KB 2824690).</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p>Create a domain account</p></td>
<td><p>Create a domain account for the Microsoft Dynamics AX .NET Business Connector proxy.</p>
<div class="alert">

> [!WARNING]
> <P>The account should not be a member of the Microsoft Dynamics AX system administrator group or a member of the Windows administrator group on the Enterprise Portal server. The login should not be used for standard logon purposes. Only those individuals who are responsible for deploying and configuring Microsoft Dynamics AX should know the credentials for this login. If a malicious user gained access to the credentials for this login, that person could potentially impersonate any Microsoft Dynamics AX user.</P>


</div>
<p>Enter the account in the Microsoft Dynamics AX client on the <strong>System administration</strong> &gt; <strong>System</strong> &gt; <strong>System service accounts</strong> form.</p></td>
</tr>
<tr class="odd">
<td><p>Install SharePoint</p></td>
<td><p>After you install SharePoint on the web server, run the SharePoint configuration wizard. Specify the Microsoft Dynamics AX .NET Business Connector proxy account on the <strong>Specify Configuration Database Settings</strong> &gt; <strong>Specify Database Access Account</strong> page of the SharePoint configuration wizard.</p></td>
</tr>
<tr class="even">
<td><p>Compile Microsoft Dynamics AX if you installed any non-SYS layer mode files</p></td>
<td><p>If you installed a non-SYS layer model file in the Microsoft Dynamics AX environment, compile Microsoft Dynamics AX before you install Enterprise Portal. If you do not compile Microsoft Dynamics AX, the Enterprise Portal installation might fail.</p></td>
</tr>
<tr class="odd">
<td><p>Download and deploy language packs</p></td>
<td><p>If you want to deploy Enterprise Portal in multiple languages, download and deploy the SharePoint language packs on the Web server before you install Enterprise Portal. You must create a unique Web application in SharePoint for each language. You can download language packs from Microsoft.com.</p></td>
</tr>
<tr class="even">
<td><p>Verify the server name</p></td>
<td><p>Verify that the name of the server that will host Enterprise Portal does not include an underscore, for example EPserver_1. If an Enterprise Portal server includes an underscore in the server name, lookups and web pages might display errors.</p></td>
</tr>
<tr class="odd">
<td><p>Verify prerequisites and system requirements</p></td>
<td><p>On the computer where you will install Enterprise Portal, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see <a href="check-prerequisites.md">Check prerequisites</a>.</p>
<p>For more information about the hardware and software requirements for Microsoft Dynamics AX, see the <a href="http://go.microsoft.com/fwlink/?linkid=165377">system requirements</a>.</p></td>
</tr>
<tr class="even">
<td><p>Verify permissions</p></td>
<td><p>Verify that you have the appropriate permissions to install Enterprise Portal. If you are installing Enterprise Portal on a server that already hosts an Enterprise Portal deployment and you want to overwrite that deployment, you must have Full Control permission in SharePoint for the existing Enterprise Portal site collection. If you do not have Full Control permission, you will not be able to delete the existing site collection by using Setup. For more information about permissions, see <a href="verify-that-you-have-the-required-permissions-for-installation.md">Verify that you have the required permissions for installation</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Verify SSL settings</p></td>
<td><p>For Secure Sockets Layer (SSL) encryption, you cannot install Enterprise Portal on a web application that is already configured to use HTTP and HTTPS bindings. You must remove the HTTP binding from the site by using Internet Information Services (IIS) Manager before you install Enterprise Portal.</p></td>
</tr>
</tbody>
</table>


## Pre-installation tasks

Perform the following tasks to verify that you can deploy Enterprise Portal on the web server.

1.  Verify that you can open SharePoint Central Administration on the Enterprise Portal server.

2.  Verify that you have the appropriate permissions to create sites by using SharePoint Central Administration to create a SharePoint team site.

3.  Verify that you can browse the team site without prompts and resolve the URL without proxy errors or other problems.

4.  If you intend to deploy or configure Enterprise Portal at a command prompt, verify that you can start the SharePoint Management Shell.

## Install Enterprise Portal binaries

This section describes how to install Enterprise Portal binaries by using Setup. During this initial install, you will not install create an Enterprise Portal site. You will create the site later in this document.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on the computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Enter a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, in the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Enterprise Portal (EP)** and **.NET Business Connector**, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any warnings or errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no warnings or errors remain, click **Next**.

8.  On the **Select a file location** page, select the location where you want to install 32-bit versions of Microsoft Dynamics AX files, and then click **Next**.

9.  On the **Specify a location for configuration settings** page, specify whether you want Enterprise Portal to access configuration information from the registry on the local computer or from a shared configuration file. If you select to use a shared configuration file, you must enter the network location of the file. Click **Next**.

10. On the **Connect to an AOS instance** page, enter the name of the computer that is running the Application Object Server (AOS) instance that you want to connect to. If necessary, verify name of the AOS instance, the TCP/IP port number, and the WSDL port for services before you click **Next**. If the AOS details are correct, click **Next**.

11. On the **Specify Business Connector proxy account information** page, enter the user name and password for the proxy account that is used by the .NET Business Connector. Click **Next**.

12. On the **Configure a Web site for Enterprise Portal** page, select the SharePoint – 80 (SharePoint Web application). If no web applications are available in the list, you must cancel Setup, create a web application by using SharePoint Central Administration, and then try the installation again.
    

    > [!WARNING]
    > <P>Do not select any other options on this page. Verify that you specified the SharePoint – 80 web application and that all other options are cleared before you click <STRONG>Next</STRONG>.</P>

    
    ![Enterprise Portal web site options in Setup](images/Hh575253.EPWebSiteSetup(AX.60).png "Enterprise Portal web site options in Setup")
    
    Click **Next**.

13. On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

14. On the **Ready to install** page, click **Install**.

15. After the installation is complete, click **Finish** to close the wizard.


> [!IMPORTANT]
> <P>Before you proceed to the next section, verify that the .NET Business connector proxy account was added to the <STRONG>WSS_WPG</STRONG> group on the web server computer: From a command prompt type <STRONG>net localgroup wss_wpg</STRONG> and press Enter.</P>



## Register an SSL certificate on the AD FS server

For testing, you can create a self-signed SSL certificate. If you create self-signed certificates, we recommend that you have one self-signed SSL certificate for the Enterprise Portal server (SSLCert1) and one self-signed SSL certificate for the AD FS server (SSLCert2). For more information, see [Create a Self-Signed Server Certificate in IIS 7.0](http://go.microsoft.com/fwlink/?linkid=235235). For production servers, you must register an SSL certificate from a certification authority on the AD FS server. The certificate will help make sure that the user’s claim was not changed in transit. We recommend that you register separate SSL certificates for the AD FS and Enterprise Portal servers. After you have created self-signed certificates or acquired certificates, complete the following procedure.

1.  On the Windows Server that will host the claims-based Enterprise Portal site, click **Start** \> **Run**, type **mmc**, and then click **OK**.

2.  Click **File** \> **Add/remove snap-in**.

3.  Click **Certificates**, and then click **Add**.

4.  When the system prompts you to specify which type of account to manage certificates for, click **Computer Account**, and then click **Next**.

5.  Click **Local computer**, and then click **Finish**.

6.  In the **Add or Remove Snap-ins** dialog box, click **OK**.

7.  In MMC snap-in, click the **Certificates (Local Computer)** node.

8.  Right-click **Personal**, and then click **All tasks** \> **Import**. The Certificate Import Wizard opens. Click **Next**.

9.  Browse to the certificate, and then click **Next**.

10. Enter the password for the certificate, and then click **Next**.

11. Select the **Mark this key as exportable** option, and then click **Next**. The **Certificate Store** dialog box appears.

12. Click **Next**.

13. Click **Finish**.

## Enable SharePoint Claims to Windows Token Service

You must enable the SharePoint claims to Windows token service (C2WTS) for claims-based authentication. Use the following procedure to start this service.

1.  In SharePoint Central Administration, under **System Settings**, click **Manage services on server**.

2.  Locate the Claims to Windows Token Service.

3.  In the **Action** column, click **Start**.

4.  In Windows, click **Start** \> **Run**, type **services.msc** and press Enter.

5.  In the **Services** console, verify that the **Claims to Windows Token Service** is running.


> [!NOTE]
> <P>Do not use the services.msc to start the C2WTS because the service will be automatically disabled after a period of time. You must use SharePoint Central Administration to start this service.</P>



## Create a claims-aware Enterprise Portal site

This section describes how to create a claims-aware Enterprise Portal site by using a Microsoft Windows PowerShell cmdlet. The cmdlet in this section first creates a claims-aware web application in SharePoint, and then deploys an Enterprise Portal site on that web application. If you are not familiar with Windows PowerShell cmdlets for Microsoft Dynamics AX, see [Administering Microsoft Dynamics AX by using Windows PowerShell](http://go.microsoft.com/fwlink/?linkid=235298) for more information. You can also create a claims-aware Enterprise Portal site on an existing SharePoint web application. Complete one of the following procedures.

  - Create a claims-aware site on a new SharePoint web application

  - Create a claims-aware site on an existing SharePoint web application

## Create a claims-aware site on a new SharePoint web application


> [!NOTE]
> <P>Windows PowerShell includes a security setting called the execution policy that determines how scripts are run. By default, the execution policy is set to <STRONG>Restricted</STRONG>, which prevents any scripts from running. To run the installation scripts for Microsoft Dynamics AX components, we recommend that you set the execution policy to <STRONG>RemoteSigned</STRONG> by using Set-ExecutionPolicy cmdlet. This setting allows you to run scripts that you’ve written and scripts that have been signed by a trusted publisher.</P>



1.  Open the Microsoft Dynamics AX 2012 Management Shell with administrator privileges. Click **Start** \> **Administrative Tools** \> right-click **Microsoft Dynamics AX 2012 Management Shell** and click **Run as administrator**.

2.  Enter the following command and press Enter.
    
    $Cred=Get-Credential

3.  When prompted, enter the credentials for the .NET Business Connector proxy account. The credentials must be the .NET Business Connector proxy account and password that were specified when Enterprise Portal binaries were installed earlier in this document. If you specify an account other than the .NET Business Connector proxy account, then the cmdlet overwrites the existing .NET Business Connector account, which can cause existing Enterprise Portal installations to stop working. Also note, this cmdlet designates the .NET Business Connector proxy account as the Enterprise Portal site administrator.

4.  Execute the following command, replacing “PathToSSLCert1” with the path to *SSLCert1*, which you imported earlier in this document.
    
    $SSLCert = Get-PfxCertificate "PathToSSLCert1"
    
    When prompted, enter the password that you specified when you exported the SSL certificate.

5.  On the Enterprise Portal server, execute the **New-AXClaimsAwareEnterprisePortalServer** cmdlet. For descriptions of the required parameters and syntax, see [New-AXClaimsAwareEnterprisePortalServer](http://go.microsoft.com/fwlink/?linkid=217573) on TechNet.
    
    The following example shows the cmdlet with the required parameters. Note that the port value of 8000 is a user-defined value. You can specify any available port number. If you specify port 443, then you do not need to specify the port number when you type the web site URL.
    
    new-AXClaimsAwareEnterprisePortalServer -Credential $Cred -Port 8000 -SSLCertificate $SSLCert
    
    This cmdlet can take several minutes to be completed. After the cmdlet is completed, you can access a new instance of Enterprise Portal at the following URL: https://*ServerName*:*PortNumber*/sites/DynamicsAx.

Browse this site to verify that the command was executed properly. If you viewed the site, then you skip to the section titled “Install Active Directory Federation Services 2.0” in this topic. If you were not able to view the site, see the section titled “Troubleshooting issues with a claims-aware site”.

## Create a claims-aware site on an existing SharePoint web application

If you want to create a new claims-aware site on an existing SharePoint web application, note the following requirements.

  - The web application must be configured for Integrated Windows/NTLM authentication in SharePoint Central Administration. This is required even if the web application is already configured as a claims-mode web application.

  - You must be a member of the site collection administrator group in SharePoint to perform the following procedures.


> [!IMPORTANT]
> <P>We recommend that the web application be configured with SSL to enhance data security.</P>



**Verify that the existing web application uses the Windows authentication provider**

Use the following procedure to verify that the existing web application uses the Windows authentication provider.

1.  In SharePoint Central Administration, click **Application Management**.

2.  Under Web applications, click **Manage web applications**.

3.  Click the application and then click **Authentication Providers**.

4.  Verify that the **Zone** lists **Default** and the **Membership Provider Name** lists **Windows**.

5.  Click the **Zone** link.

6.  In either the **IIS Authentication Settings** section or the **Claims Authentication Types** section, verify that **Integrated Windows** and **NTLM** are selected.

7.  Save your changes.

**Create an Enterprise Portal site on the web application**

Choose one of the following options to create an Enterprise Portal site on the existing web application.

  - Use Microsoft Dynamics AX Setup

  - Use Microsoft Dynamics AX 2012 Management Shell

**Use Microsoft Dynamics AX Setup**

To create an Enterprise Portal site on the existing web application by using Microsoft Dynamics AX Setup, complete the procedure described earlier in this topic under “Install Enterprise Portal binaries”. However, when you perform that procedure, you must select the existing web application and select the following options: **Configure for Windows SharePoint Services**, **Create Web site**, and **Restart IIS after installation is completed**.

![Enterprise Portal web site options in Setup](images/Hh575253.EPWebSiteSetup2(AX.60).png "Enterprise Portal web site options in Setup")

**Use the Microsoft Dynamics AX 2012 Management Shell**

You can create an Enterprise Portal site on the existing web application by using the Microsoft Dynamics AX 2012 Management Shell.

1.  Determine the name of the web application where you want to create the site. In SharePoint Central Administration, click **Manage web applications**. Find the name of the application. For example, SharePoint – 443.

2.  On the Enterprise Portal server, execute the **New-AXClaimsAwareEnterprisePortalServer** cmdlet by using the following parameters.
    
    new-AXClaimsAwareEnterprisePortalServer -Credential $Cred –WebApplication “ExistingWebApplicationName”
    
    For example: new-AXClaimsAwareEnterprisePortalServer -Credential $Cred –WebApplication “SharePoint - 443”
    
    This cmdlet can take several minutes to be completed. After the cmdlet is completed, you can access a new instance of Enterprise Portal at the following URL: https://*ServerName*:*PortNumber*/sites/DynamicsAx. Browse this site to verify that the command was executed properly. If you viewed the site, then you skip to the section titled “Install Active Directory Federation Services 2.0” in this topic. If you were not able to view the site, see the section titled “Troubleshooting issues with a claims-aware site”.

## Troubleshooting issues with a claims-aware site

**Error: A specified logon session does not exist.**

This error is caused by incorrect certificate information. Verify that you selected **Mark this key as exportable** when you imported the certificate.

**Error: Setup could not find the IIS virtual server by using the name you specified.**

This error occurs when the web application and Enterprise Portal site already exist on the server, so that the Windows PowerShell cmdlet detects a conflict.

To resolve this issue:

1.  Click **Start** \> **Administrative Tools** \> **Internet Information Services (IIS) Manager**.

2.  Expand the server node, and then expand the **Web sites** node.

3.  Click the Enterprise Portal site.

4.  In the center pane, under **IIS**, double-click **Authentication**.

5.  Click **ASP.NET Impersonation**, and then, in the **Actions** pane, click **Disable**.

6.  Use Microsoft Dynamics AX Setup to install Enterprise Portal on the web application created by the **New-AXClaimsAwareEnterprisePortalServer** cmdlet. For more information, see [Install Enterprise Portal](install-enterprise-portal.md) on TechNet.
    

    > [!NOTE]
    > <P>On the <STRONG>Configure a Web site for Enterprise Portal</STRONG> page of the Setup Wizard, clear all options. You will configure SharePoint and create the website later in this procedure.</P>



7.  After you install Enterprise Portal on the web application, click **Start** \> **SharePoint Central Administration**.

8.  Click **Application Management**.

9.  Under **Site Collections**, click **Create site collections**.

10. Under **Select a template**, click the **Custom** tab.

11. Select the **Microsoft Dynamics Enterprise Portal** template.

12. After SharePoint creates the site collection, select the Enterprise Portal site in IIS Manager.In the center pane, under **IIS**, double-click **Authentication**.

13. Enable **ASP.NET Impersonation** authentication.

## Install Active Directory Federation Services 2.0

This section describes how to install AD FS on an Enterprise Portal server.

1.  [Download](http://go.microsoft.com/fwlink/?linkid=235894) AD FS, and run Setup.

2.  When prompted to select a server role, click **Federation server**.

3.  After the installation is completed, restart the server as recommended by Setup, and then run the AD FS 2.0 Management tool. In Windows, click **Start** \> **Administrative Tools** \> **AD FS 2.0 Management**.

4.  Under **Configure This Federation Server**, click **AD FS 2.0 Federation Server Configuration Wizard**.

5.  Click **Create a new Federation Service**, and then click **Next**.

6.  Click **Stand-alone federation server**, and then click **Next**.

7.  Specify the SSL certificate that you created earlier in this document, and then click **Next**.

8.  Complete the wizard. AD FS creates a new application named **adfs** on the Default Web Site in IIS.

## Add a trusted relying party

A relying party trust is a trust object that is created to maintain the relationship with a Federation Service or an application that consumes claims from the Federation Service. This section describes how to configure a trusted relying party in AD FS 2.0 Management.

1.  In **AD FS 2.0 Management**, click **Require: Add a trusted relying party**. The Add Relying Party Trust Wizard opens.

2.  Click **Start**.

3.  Click **Enter data about the relying party manually**, and then click **Next**.

4.  In the **Display Name** field, enter a name, such as **ADFS Sign-on**, and then click **Next**.

5.  Click **ADFS 1.0 and 1.1 profile**, and then click **Next**.

6.  In the **WS-Federation Passive URL** field, enter the URL of the claims-aware Enterprise Portal site. The URL must use the following format: https://*ServerName*:*portnumber*/\_trust/. The server name and port must be the values that you specified earlier in this document when you created the claims-aware Enterprise Portal site.
    
    For example: https://TestServer:8000/\_trust/

7.  Type an identifier in the format urn:*ServerName*:*ProviderName*, and then click **Add**.
    
    For example: urn:TestServer:ADFSProvider

8.  Remove the following entry from the list of providers: https://*ServerName*:*PortNumber*/\_trust/

9.  Click **Next**.

10. Click **Permit all users to access this relying party**, and then click **Next**.

11. On the **Ready to Add Trust** page, click **Next**.

12. On the **Finish** page, click **Open the Edit Claim Rules** for the relying party trust.

13. Click **Add Rule**.

14. Select the **Send LDAP Attributes as Claims** claim rule template, and then click **Next**.

15. Enter a claims rule name, such as **ADFS sign-on**.

16. In the **Select an attribute store** section, click **Active Directory**.

17. Click **LDAP Attribute**, and then click **SAM-Account-Name**.

18. In the **Outgoing claim type** section, click **E-mail address**.

19. Click **Finish**.

## Manage the AD FS token-signing certificate

1.  In **AD FS 2.0 Management**, expand **Service**, and then click **Certificates**.

2.  In the center pane, in the **Token-signing** section, right-click the **CN=ADFS Signing** certificate, and then click **View Certificate**.

3.  Click **Details**, and then click **Copy to file**.

4.  Save the file as *Name*.cer by using the **DER Encoded Binary X.509** option and then copy it to a directory on the Enterprise Portal server. For example, you could save the certificate as **adfs-TokenSigningCert.cer** and save it in a **cert** directory on the C:\\ drive of the Enterprise Portal server.


> [!NOTE]
> <P>Users must specify a valid email address for their account logon.</P>



## Specify the claims provider in SharePoint

1.  In Windows, click **Start** \> **Administrative Tools**.

2.  Click **Microsoft Dynamics AX 2012 Management Shell**.

3.  Execute the following command, replacing **“path-to-token signing certificate from the AD FS server”** with the path of the *Name*.cer file that you configured in step 4 of the previous procedure.
    
    $SigningCert  = Get-PfxCertificate "path-to-token signing certificate from the AD FS server"

4.  On the Enterprise Portal server, execute the **Add-AXSharepointClaimsAuthenticationProvider** cmdlet. For descriptions of the required parameters and syntax, see [Add-AXSharepointClaimsAuthenticationProvider](http://go.microsoft.com/fwlink/?linkid=217572) on TechNet.
    
    The following example shows the cmdlet with the required parameters.
    
    Add-AXSharepointClaimsAuthenticationProvider -Type ADFS -Name ADFSProvider -SigningCertificate $SigningCert –ServerUrl "https://ServerName/adfs/ls/"
    
    You can specify any name for the provider. In this example, the name is ADFSProvider. The server URL must be the FQDN of the server that runs AD FS, followed by **/adfs/ls/**.

5.  On the Enterprise Portal server, execute the **Add-AXEnterprisePortalClaimsAuthenticationProvider** cmdlet. For descriptions of the required parameters and syntax, see [Add-AXEnterprisePortalClaimsAuthenticationProvider](http://go.microsoft.com/fwlink/?linkid=217571) on TechNet.
    
    The following example shows the cmdlet with the required parameters.
    
    Add-AXEnterprisePortalClaimsAuthenticationProvider -URL "https://ServerName:PortNumber" -Name ADFSPROVIDER
    
    This cmdlet adds the AD FS-based authentication trusted identity provider to the claims-aware Enterprise Portal site. The URL must be the URL of the Enterprise Portal site that you created earlier in this document: https://*ServerName*:*PortNumber*. The name of the provider must be the name that was used to create the provider in the previous procedure. Users should now see this provider in the providers list when they browse the site (https://*ServerName*:*PortNumber*/sites/DynamicsAx).

## Register the AD FS signing certificate as a trusted root authority with SharePoint

1.  Click **Start** \> **All Programs** \> **Microsoft SharePoint Products** \> **SharePoint Management Shell**.

2.  Execute the following commands, replacing *\<Path-to-certificate\>\\Name.cer* with the path and name of the AD FS signing certificate.
    
    $cert = New-Object System.Security.Cryptography.X509Certificates.X509Certificate2("\<Path-to-certificate\>\\Name.cer")
    
    $spcert = New-SPTrustedRootAuthority -Certificate $cert -Name "ADFSSigningCert"


> [!NOTE]
> <P>“ADFSSigningCert” is a user-specified value.</P>



## Create a new user for AD FS authentication

The **New-AXUser** cmdlet creates a new user in Microsoft Dynamics AX. You can specify the type of user to add. If you are creating a claims user, specify the name of the claims provider in the *UserDomain* parameter, as described in the following procedure.

1.  In Windows, click **Start** \> **Administrative Tools**.

2.  Click **Microsoft Dynamics AX 2012 Management Shell**.

3.  On the Enterprise Portal server, execute the New-AXUser cmdlet. For descriptions of the required parameters and syntax, see [New-AXUser](http://go.microsoft.com/fwlink/?linkid=217580) on TechNet.
    
    The following example shows the cmdlet with the required parameters. AXUser, UserName, and UserDomain are user-specified values. The value of UserDomain is the same value that you specified in Step 4 of the “Specify the Claims Provider in SharePoint” procedure earlier in this document.
    
    New-AXUser -AccountType ClaimsUser -AXUserId april -UserName aprilbuckley -UserDomain ADFSProvider

## Assign security roles for users

You must assign security roles for each user who was created by using the New-AXUser cmdlet. For information about how to assign security roles in the Microsoft Dynamics AX client, see [Assign users to security roles](assign-users-to-security-roles.md). For information about how to assign security roles by using PowerShell, see the [Add-AXSecurityRoleMember](add-axsecurityrolemember.md) cmdlet Help on TechNet.

## Validate AD FS configurations

1.  Open a web browser, and browse the Enterprise Portal site: https://*ServerName*:*PortNumber*/sites/DynamicsAx

2.  In the list of providers, select the AD FS provider. For example, **ADFSProvider**.

3.  Log on to Enterprise Portal by using the credentials that you created in the previous procedure. You should be able to log on to Microsoft Dynamics AX as a system user.

## Troubleshooting AD FS issues

_**Error: Users see a blank page after logging on to Enterprise Portal by using the AD FS provider.**_

This error occurs when the logon URL for the AD FS provider (for example, https://TestServer.contoso.com/adfs/ls/) cannot be opened in a web browser. To resolve this issue, you must update the hosts file on the server.

1.  Open the hosts file. By default, the file is located in the following directory: C:\\Windows\\System32\\drivers\\etc folder

2.  Add an entry for the AD FS provider in the form \<IP address of AD FS server\> \<AD FS Server Name\> \<FQDN of AD FS server\>
    
    For example: 10.10.50.215 TestServer  TestServer.contoso.com

3.  In Internet Explorer, open **Internet options**.

4.  Click the **Connections** tab, and then click **LAN settings**.

5.  Clear the **Automatically detect settings** option. You might have to instruct all Enterprise Portal users to change this setting in their web browser.

_**Error: Users select the AD FS provider on the logon page, and then receive a “404: Page not found” error.**_

To resolve this issue, use IIS Manager to verify that Default Web Site or the site that hosts the AD FS provider is running.

_**Error: There was a problem accessing the site.**_

To learn more about this error, view the details in the AD FS 2.0 Admin event log. If you need more details about this issue, you can enable the AD FS debug log, as described in the following procedure.

1.  In Event Viewer, click **View** \> **Show Analytic and Debug Logs**.

2.  To view events in the debug log, click **AD FS 2.0 Tracing** \> **Debug**.

3.  Right-click the **Debug** log, and then click **Enable Log**.

_**Error in the AD FS Admin log: An error was encountered during a federation passive request.**_

Exception details:

Microsoft.IdentityServer.Web.InvalidScopeException: MSIS7007: The requested relying party trust 'urn:ServerName:Provider' is unspecified or unsupported. If a relying party trust was specified, it is possible that you do not have permission to access the trust relying party. Contact your administrator for details at: Microsoft.IdentityServer.Web.FederationPassiveAuthentication.SubmitRequest(MSISRequestSecurityToken request

To resolve this issue:

1.  In AD FS 2.0 Management, click **Trust Relationships** \> **Relying Party**.

2.  Double click **ADFS Sign-on**.

3.  Click the **Identifiers** tab.

4.  In the **Relying party identifiers** field, verify that the address matches the address shown in the error message. Addresses are case sensitive.

## Specify which trusted identity provider is available for users at logon

You can select which flexible authentication provider is available in the **Sign-in** list when a user accesses the Enterprise Portal site.

1.  In SharePoint Central Administration on the Enterprise Portal server, click **Manage web applications**.

2.  Click the claims-aware Enterprise Portal site.

3.  Click **Authentication providers**.

4.  Click **Default**.

5.  In the **Claims Authentication Types** section, select the providers that you want to appear in the **Sign-in** list.

6.  Click **OK**.

## See also

[Deploy an Enterprise Portal site that uses forms-based authentication](deploy-an-enterprise-portal-site-that-uses-forms-based-authentication.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

