---
title: Deploy an Enterprise Portal site that uses forms-based authentication
TOCTitle: Deploy an Enterprise Portal site that uses forms-based authentication
ms:assetid: dca19036-df4f-41b0-b6af-5fcfa951c67e
ms:mtpsurl: https://technet.microsoft.com/library/Hh575253(v=AX.60)
ms:contentKeyID: 39555416
author: Khairunj
ms.date: 07/01/2015
mtps_version: v=AX.60
f1_keywords:
- forms authentication
- claims authentication
- EP with Live ID
- Live ID
---

# Deploy an Enterprise Portal site that uses forms-based authentication 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to deploy an Enterprise Portal for Microsoft Dynamics AX site that uses the claims-mode authentication that is provided by SharePoint. In the context of Microsoft Dynamics AX, this kind of authentication is called flexible authentication. Flexible authentication enables businesses and organizations to authenticate Enterprise Portal users without having to store user accounts in Active Directory Domain Services. By using flexible authentication, you can configure a claims-aware Enterprise Portal site to authenticate users by using one of the following services: forms-based authentication or Microsoft Active Directory Federation Services (AD FS). This topic describes how to deploy an Enterprise Portal site that uses forms-based authentication. Forms-based authentication validates credentials that are entered in a logon form and stored in an ASP.NET database.

> [!NOTE]
> <P>Active Directory Domain Services (AD DS) is still required for Enterprise Portal administration tasks.</P>

Before you create a forms-based Enterprise Portal site, we recommend that you learn about the concepts of claims-based authentication. The procedures in this topic assume that you are familiar with the concepts in the following documents.

[Forms Authentication Provider](https://go.microsoft.com/fwlink/?linkid=235460)

[A Guide to Claims-Based Identity and Access Control (2nd Edition)](https://go.microsoft.com/fwlink/?linkid=234145)

[Implementing Claims-Based Authentication with SharePoint Server 2010](https://go.microsoft.com/fwlink/?linkid=234146)

This topic includes the following sections.

  - Before you begin

  - Pre-installation tasks

  - Install Enterprise Portal binaries

  - Configure certificates

  - Enable SharePoint Claims to Windows Token Service

  - Create a claims-aware Enterprise Portal site

  - Install the ASP.NET database

  - Create a signing certificate to establish trust between the Enterprise Portal site and the forms-based site

  - Grant the .NET Business Connector proxy access to the signing certificate

  - Create a forms-based Security Token Service site

  - Force new users to change their password at first logon

  - Create a new user for forms-based authentication

  - Logon to the site using forms-based authentication

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
<li><p><a href="https://go.microsoft.com/fwlink/?linkid=294944">Download</a> and install the Microsoft Dynamics AX 2012 claims-mode authentication hotfix (KB 2823664).</p></li>
<li><p><a href="https://go.microsoft.com/fwlink/?linkid=294677">Download</a> and install the Microsoft Dynamics AX 2012 R2 claims-mode authentication hotfix (KB 2824690).</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p>Create a domain account</p></td>
<td><p>Create a domain account for the Microsoft Dynamics AX .NET Business Connector proxy.</p>

> [!WARNING]
> <P>The account should not be a member of the Microsoft Dynamics AX system administrator group or a member of the Windows administrator group on the Enterprise Portal server. The login should not be used for standard logon purposes. Only those individuals who are responsible for deploying and configuring Microsoft Dynamics AX should know the credentials for this login. If a malicious user gained access to the credentials for this login, that person could potentially impersonate any Microsoft Dynamics AX user.</P>

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
<p>For more information about the hardware and software requirements for Microsoft Dynamics AX, see the <a href="https://go.microsoft.com/fwlink/?linkid=165377">system requirements</a>.</p></td>
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



## Configure certificates

The procedures in this section require secure sockets layer (SSL) and security token service (STS) certificates. These certificates help ensure that a user’s claim is not changed in transit. The following certificates are required.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Certificate</p></th>
<th><p>Details</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>SSL certificate for the Enterprise Portal site</p></td>
<td><p>Referred to as <em>SSLCert1</em> in this document</p></td>
</tr>
<tr class="even">
<td><p>SSL certificate for the STS site</p></td>
<td><p>Referred to as <em>SSLCert2</em> in this document</p></td>
</tr>
<tr class="odd">
<td><p>STS signing certificate for the token service</p></td>
<td><p>Referred to as <em>STScertSigningCert</em></p></td>
</tr>
</tbody>
</table>


For test environments, you can create [self-signed certificates](https://go.microsoft.com/fwlink/?linkid=235235) by using Internet Information Services (IIS) manager. However, for production environments you must acquire certificates from a valid certificate authority. Before you proceed in this topic, install SSLCert1 and SSLCert2 into the **Personal** node in the certificate store on the web server. You will configure the STScertSigningCert later in this document. For information about how to work with certificates see [Certificate Overview](https://go.microsoft.com/fwlink/?linkid=282620).

1.  On the Windows server that will host the forms-based Enterprise Portal site, click **Start** \> **Run**, type mmc, and then click **OK**.

2.  Click **File** \> **Add/remove snap-in**.

3.  Click **Certificates**, and then click **Add**.

4.  When the system prompts you to specify which type of account to manage certificates for, click **Computer Account**, and then click **Next**.

5.  Click **Local computer**, and then click **Finish**.

6.  In the **Add or Remove Snap-ins** dialog box, click.

7.  In the MMC snap-in, click the **Certificates (Local Computer)** node.

8.  Right-click **Personal**, and then click **All tasks** \> **Import**. The **Certificate Import Wizard** opens. Click **Next**.

9.  Browse to the certificate, and then click **Next**.

10. Enter the password for the certificate, and then click **Next**.

11. Select the **Mark this key as exportable** option, and then click **Next**. The **Certificate Store** dialog box appears. Click **Next**.

## Enable SharePoint Claims to Windows Token Service

You must enable the SharePoint claims to Windows token service (C2WTS) for claims-based authentication. Use the following procedure to start this service.

1.  In SharePoint Central Administration, under **System Settings**, click **Manage services on server**.

2.  Locate the **Claims to Windows Token Service**.

3.  In the **Action** column, click **Start**.

4.  In Windows, click **Start** \> **Run**, type **services.msc** and press Enter.

5.  In the **Services** console, verify that the **Claims to Windows Token Service** is running.


> [!NOTE]
> <P>Do not use the services.msc to start the C2WTS because the service will be automatically disabled after a period of time. You must use SharePoint Central Administration to start this service.</P>



## Create a claims-aware Enterprise Portal site

This section describes how to create a claims-aware Enterprise Portal site by using a Microsoft Windows PowerShell cmdlet. The cmdlet in this section first creates a claims-aware web application in SharePoint, and then deploys an Enterprise Portal site on that web application. If you are not familiar with Windows PowerShell cmdlets for Microsoft Dynamics AX, see [Administering Microsoft Dynamics AX by using Windows PowerShell](https://go.microsoft.com/fwlink/?linkid=235298) for more information. You can also create a claims-aware Enterprise Portal site on an existing SharePoint web application. Complete one of the following procedures.

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

5.  On the Enterprise Portal server, execute the **New-AXClaimsAwareEnterprisePortalServer** cmdlet. For descriptions of the required parameters and syntax, see [New-AXClaimsAwareEnterprisePortalServer](https://go.microsoft.com/fwlink/?linkid=217573) on TechNet.
    
    The following example shows the cmdlet with the required parameters. Note that the port value of 8000 is a user-defined value. You can specify any available port number. If you specify port 443, then you do not need to specify the port number when you type the web site URL.
    
    new-AXClaimsAwareEnterprisePortalServer -Credential $Cred -Port 8000 -SSLCertificate $SSLCert
    
    This cmdlet can take several minutes to be completed. After the cmdlet is completed, you can access a new instance of Enterprise Portal at the following URL: https://*ServerName*:*PortNumber*/sites/DynamicsAx.

Browse this site to verify that the command was executed properly. If you viewed the site, then you skip to the section titled “Install the ASP.NET database” in this topic. If you were not able to view the site, see the section titled “Troubleshooting issues with a claims-aware site”.

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
    
    This cmdlet can take several minutes to be completed. After the cmdlet is completed, you can access a new instance of Enterprise Portal at the following URL: https://*ServerName*:*PortNumber*/sites/DynamicsAx. Browse this site to verify that the command was executed properly. If you viewed the site, then you skip to the section titled “Install the ASP.NET database” in this topic. If you were not able to view the site, see the section titled “Troubleshooting issues with a claims-aware site”.

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

## Install the ASP.NET database

Enterprise Portal users who are external to your business or organization will enter their credentials during sign-up, and those credentials will be stored in an ASP.NET database. Use the following procedure to create the ASP.NET database.


> [!NOTE]
> <P>You can install the ASP.NET database on a separate server. If you do install this database on a separate server, then you must specify a SQL connection string that will permit access to the database. You can specify the connection string by using the -ConnectionString parameter when you execute the Add-AXSharepointClaimsAuthenticationProvider PowerShell cmdlet later in this document.</P>



Open a Command Prompt window by using an administrator account on the server. Execute the following command.

1.  %windir%\\Microsoft.NET\\Framework64\\v4.0.30319\\aspnet\_regsql.exe

2.  The ASP.NET SQL Server Setup Wizard opens.

3.  Accept all default values, and complete the wizard. The wizard creates a new database in Microsoft SQL Server called **aspnetdb**.

## Grant the Business Connector proxy access to the ASP.NET database

Complete the following procedure to add the .NET Business Connector proxy to the ASP.NET database.

1.  Open SQL Server Manager on the server where you installed the ASP.NET database.

2.  Expand then ASP.NET database in the left column, and then expand the **Security** node.

3.  Right-click the **Users** node and select **New User**.

4.  Enter the domain/user\_name of the .NET Business Connector proxy.

5.  In the **Database Role Membership** section, click **db\_owner**.

6.  Save your changes.

## Create a signing certificate to establish trust between the Enterprise Portal site and the forms-based site

This section describes how to create a signing certificate that is used to establish trust between the claims-aware Enterprise Portal site and the forms-based site. The makecert.exe command in the following procedures creates a self-signed certificate and registers that certificate with the local computer. For the following procedures, refer to Option A if Visual Studio is installed on the Enterprise Portal server, or refer to Option B if Visual Studio is installed on a separate server and you need to export the certificate after you create it.

## Option A: Visual Studio is installed on the Enterprise Portal server

Use this procedure to create a signing certificate. You must use Visual Studio to create the certificate. This procedure describes how to create the certificate when Visual Studio is installed on the Enterprise Portal server. If Visual Studio is not installed on the Enterprise Portal server, go to Option B.

1.  On the Enterprise Portal server, click **Start** \> **All Programs**.

2.  Click **Microsoft Visual Studio 2010**.

3.  Click **Visual Studio Tools** \> **Visual Studio Command Prompt**.

4.  Execute following command, replacing \<string\> with a name for your certificate. For example: FORMS-CERT. Make a note of the name of this string because you will specify it again in the next procedure.
    
    makecert.exe -r -pe -a sha1 -n "CN=\<string\>" -ss My -sr LocalMachine -sky exchange -len 2048 -sp "Microsoft Enhanced RSA and AES Cryptographic Provider" -sy 24 c:\\certs\\\<string\>.cer

After the command completes go to the section titled “Grant the .NET Business Connector proxy access to the signing certificate”.

## Option B: Visual Studio is not installed on the Enterprise Portal server

Use this procedure to create a signing certificate. You must use Visual Studio to create the certificate. This procedure describes how to create the certificate with Visual Studio and then import the certificate to the Enterprise Portal server.

1.  On the Visual Studio server, click **Start** \> **All Programs**.

2.  Click **Microsoft Visual Studio 2010**.

3.  Click **Visual Studio Tools** \> **Visual Studio Command Prompt**.

4.  Execute following command, replacing \<string\> with a name for your certificate. For example: FORMS-CERT. Make a note of the name of this string because you will specify it again in the next procedure.
    
    makecert.exe -r -pe -a sha1 -n "CN=\<string\>" -ss My -sr LocalMachine -sky exchange -len 2048 -sp "Microsoft Enhanced RSA and AES Cryptographic Provider" -sy 24 c:\\certs\\\<string\>.cer

5.  Click **Start** \> **Run**, type **mmc** and press Enter.

6.  In the Microsoft Management Console, click **File** \> **Add/Remove snap-in**.

7.  Add the **Certificates** snap-in and click **OK**.

8.  Click **Computer** account and then click **Next**.

9.  Click **Local computer** and then click **Finish**.

10. Click **OK** to close the **Add or Remove Snap-ins** dialog box.

11. Expand the **Certificates (Local Computer)** node.

12. Expand the **Trusted Root Certification Authorities** \> **Certificates** node.

13. Right-click the certificate that you created in Step 4 of this procedure and click **All Tasks/Export**.

14. Click **Next**, and then click **Yes, Export the private key**.

15. Click **Next**, and then enter a password for the certificate. Make a note of the password because you will need to specify it when you import the certificate in the next procedure.

16. Click **Next**, and then specify a location and name for the certificate.

17. Click **Finish**.

18. Copy the certificate file (.PFX file) to a location that is accessible by the Enterprise Portal server. You can now import the certificate to the Enterprise Portal server.

## Import the certificate to the Enterprise Portal server

Use this procedure to import the signing certificate that you created in the previous procedure to the Enterprise Portal server.

1.  On the Enterprise Portal server, click **Start** \> **Run**, type **mmc** and press Enter.

2.  In the Microsoft Management Console, click **File** \> **Add/Remove snap-in**.

3.  Add the **Certificates** snap-in and click **OK**.

4.  Click **Computer account**, and then click **Next**.

5.  Click **Local computer**, and then click **Finish**.

6.  Click **OK** to close the **Add or Remove Snap-ins** dialog box.

7.  Expand the **Certificates (Local Computer)** node.

8.  Right-click **Trusted Root Certification Authorities**, and then click **All tasks\\Import**.

9.  Click **Next**, and then specify the file location.

10. Click **Next**, and then enter the password for the pfx certificate.

11. Select the **Mark this key as exportable** option, and then click **Next**.

12. Click **Next**, and then click **Finish**.

13. You are now ready to grant the .NET Business Connector proxy access to the signing certificate.

## Grant the .NET Business Connector proxy access to the signing certificate

Use the following procedure to grant the .NET Business Connector proxy access to the signing certificate you created in the previous section.

1.  On the Enterprise Portal server, click **Start** \> **Run**, type **mmc** and press Enter.

2.  In the Microsoft Management Console, click **File** \> **Add/Remove snap-in**.

3.  Add the **Certificates** snap-in and click **OK**.

4.  Click **Computer account**, and then click **Next**.

5.  Click **Local computer**, and then click **Finish**.

6.  Click **OK** to close the **Add or Remove Snap-ins** dialog box.

7.  Expand the **Certificates (Local Computer)** \> **Personal** \> **Certificates** node.

8.  Right-click the certificate you created in the previous section and select **All Tasks** \> **Manage Private Keys**.

9.  Add the .NET Business Connector as a user and grant **Full control** permissions.

10. Save your changes.

## Create a forms-based Security Token Service site

An Enterprise Portal site can support multiple identity providers. When a user selects the forms authentication provider, they are redirected to the Security Token Service (STS) site that you will create in this section. The user can then login to Enterprise Portal using their forms-based credentials.

1.  Click **Start** \> **Administrative Tools**.

2.  Click **Microsoft Dynamics Ax 2012 Management Shell**.

3.  Execute the following command, replacing “PathToSSLCert2” with the path of the SSL certificate that you registered earlier in this document.
    
    $SSLCert = Get-PfxCertificate "PathToSSLCert2"

4.  Execute the following command. Note that the value of \<string\>.cer is the same value you specified for the “Create a signing certificate to establish trust between the Enterprise Portal site and the forms-based site” procedure.
    
    $SigningCert = Get-PfxCertificate c:\\certs\\\<string\>.cer

5.  On the Enterprise Portal server, execute the **Add-AXSharepointClaimsAuthenticationProvider** cmdlet. For descriptions of the required parameters and syntax, see [Add-AXSharepointClaimsAuthenticationProvider](https://go.microsoft.com/fwlink/?linkid=217572) on TechNet.
    
    The following example shows the cmdlet with the required parameters. Note that the name FormsAuth and the port value 8088 are user-specified values. You can specify any name and available port.
    
    Add-AXSharepointClaimsAuthenticationProvider -Type Forms -Name FormsAuth -SigningCertificate $SigningCert -Credential $Cred -Port 8088 -SSLCertificate $SSLCert
    

    > [!NOTE]
    > <P>The command assumes that the ASP.NET database is installed on the Enterprise Portal server. If the ASP.NET database is installed on a separate server, you must also specify the –ConnectionString parameter.</P>
    > <P></P>
    > <P>-ConnectionString "Data Source=&lt;AspNetDbMachineName&gt;;Initial Catalog=aspnetdb;Trusted_Connection=true"</P>



6.  On the Enterprise Portal server, execute the **Add-AXEnterprisePortalClaimsAuthenticationProvider** cmdlet. For descriptions of the required parameters and syntax, see [Add-AXEnterprisePortalClaimsAuthenticationProvider](https://go.microsoft.com/fwlink/?linkid=217571) on TechNet.
    
    The following example shows the cmdlet with the required parameters.
    
    Add-AXEnterprisePortalClaimsAuthenticationProvider -URL "https://ServerName:PortNumber" -Name FormsAuth
    
    This cmdlet adds the forms-based authentication trusted identity provider to the claims-aware Enterprise Portal site. The URL must be the URL of the Enterprise Portal site that you created earlier in this document: https://*ServerName*:*PortNumber*. Users should now see this provider in the providers list when they navigate to the site (https://*ServerName*:*PortNumber*/sites/DynamicsAx).

## Force new users to change their password at first logon

By default, the forms-based authentication provider does not require new users to change the default password that was specified when the user account was enabled. As a security best practice, we recommend that you force new users to change their password at first logon.

1.  Open the forms-based authentication provider web.config file. By default, the file path is:
    
    C:\\Program Files\\Common Files\\Microsoft Shared\\Web Server Extensions\\14\\template\\layouts\\FormsAuth\\web.config

2.  Locate the **enableForceChangePasswordOnce** key.

3.  Change the key setting to “true”. For example:
    
    \<add key="enableForceChangePasswordOnce" value="true" /\>

4.  Save your changes in the file.

5.  Restart the web service.


> [!IMPORTANT]
> <P>By default, the maxinvalidPasswordAttempts property in the web.config file is configured to allow unlimited logon attempts. We recommend that you configure the property to limit the number of logon attempts. For more information, see <A href="https://msdn.microsoft.com/library/system.web.security.sqlmembershipprovider.maxinvalidpasswordattempts.aspx">SqlMembershipProvider.MaxInvalidPasswordAttempts</A> Property.</P>



## Create a new user for forms-based authentication

The New-AXUser cmdlet creates a new user in the System user role in Microsoft Dynamics AX. After you create the new user using the following command, add the user to other roles, if needed. For more information about adding users to Microsoft Dynamics AX or configuring user roles, see [Set up user security in Microsoft Dynamics AX](set-up-user-security-in-microsoft-dynamics-ax.md).

If you are creating a claims user, specify the name of the claims provider in the *UserDomain* parameter. If you are using forms-based claims authentication, you can also create a new user in the provider.

1.  Click **Start**> **Administrative Tools**.

2.  Click **Microsoft Dynamics Ax 2012 Management Shell**.

3.  On the Enterprise Portal server, execute the **New-AXUser** cmdlet. For descriptions of the required parameters and syntax, see [New-AXUser](https://go.microsoft.com/fwlink/?linkid=217580) on TechNet.
    
    The following example shows the cmdlet with the required parameters. The *AXUserId*, *UserName*, *UserDomain*, and *Password* are user-specified values. The *UserDomain* is the same value specified for Name in Step 7 of the previous procedure.
    
    New-AXUser -AccountType ClaimsUser -AXUserId jdd -UserName johndoe -UserDomain FormsAuth -CreateInProvider -ClearTextPassword "Yukon\!\!90"

4.  Assign security roles for the user by using the [Add-AXSecurityRoleMember](add-axsecurityrolemember.md) cmdlet or by using the **Users** form in the Microsoft Dynamics AX client.

## Logon to the site using forms-based authentication

If you browse the Enterprise Portal site by using the following URL: https://ServerName:PortNumber/sites/DynamicsAx, the Sign In page prompts you to select a logon option from the drop-down list. If you select FormsAuth, you are redirected to the forms-based authentication logon site, such as https://ServerName.contoso.com:PortNumber/_Layouts/Login.aspx. Verify that you can logon to the site using forms-based authentication.

  


