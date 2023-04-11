---
title: Install Enterprise Portal in a Web farm
TOCTitle: Install Enterprise Portal in a Web farm
ms:assetid: 7e3b53f7-ba5e-4492-ac69-70b796e2711d
ms:mtpsurl: https://technet.microsoft.com/library/Dd309729(v=AX.60)
ms:contentKeyID: 39555374
author: tonyafehr
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# Install Enterprise Portal in a Web farm 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to install and configure Enterprise Portal for Microsoft Dynamics AX in a Web farm. A Web farm distributes Enterprise Portal requests and processing across multiple servers, which can improve performance and availability. This topic includes the following sections.

  - Before you begin

  - Topology overview

  - Install and configure SharePoint

  - Before you install Enterprise Portal

  - Install Enterprise Portal

  - Optional: Specify machineKey values in web.config files for sites in a Web farm

  - Configure firewall settings on Enterprise Portal servers

  - Next steps

For information about how to install Enterprise Portal in an environment with two domain controllers and two firewalls for extranet deployments, see [Install Enterprise Portal in a traditional perimeter network](install-enterprise-portal-in-a-traditional-perimeter-network.md).


> [!NOTE]
> <P>If you are upgrading Enterprise Portal between Microsoft Dynamics AX 2012, Microsoft Dynamics AX 2012 Feature Pack, and Microsoft Dynamics AX 2012 R2, you should review <A href="scenario-perform-in-place-upgrade-to-ax-2012-r2-or-ax-2012-r3.md">Scenario: Perform in-place upgrade to AX 2012 R2 or AX 2012 R3</A>.</P>



## Before you begin

Complete the following tasks before you install Enterprise Portal in a Web farm:

  - Install and configure Windows Server AppFabric in your server farm. For more information, see [Install and configure Windows AppFabric for Enterprise Portal](install-and-configure-windows-appfabric-for-enterprise-portal.md)

  - If you installed a non-SYS layer model file in the Microsoft Dynamics AX environment, compile Microsoft Dynamics AX before you install Enterprise Portal. If you do not compile Microsoft Dynamics AX, the Enterprise Portal installation might fail.

  - Verify that the name of each server in the Enterprise Portal Web farm does not include an underscore, for example EPserver\_1. If an Enterprise Portal server includes an underscore in the server name, lookups and Web pages might display errors.

  - On each computer where you will install Enterprise Portal, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377).

  - Verify that you have the appropriate permissions to install Enterprise Portal.
    
      - Member of the Administrator group in Windows on each server in the farm.
    
      - Member of the dbcreator and securityadmin roles in the Microsoft Dynamics AX SQL Server instance.
    
      - Member of the System administrator role in Microsoft Dynamics AX.
    
      - Member of the SharePoint farm administrators group (if SharePoint is already installed on each server)
        
        If you are installing Enterprise Portal on a server that already hosts an Enterprise Portal deployment and you want to overwrite that deployment, you must have Full Control permission in SharePoint for the existing Enterprise Portal site collection. If you do not have Full Control permission, you will not be able to delete the existing site collection by using Setup.

  - For Secure Sockets Layer (SSL) encryption, you cannot install Enterprise Portal on a Web application that is already configured to use HTTP and HTTPS bindings. You must remove the HTTP binding from the site by using IIS Manager before you install Enterprise Portal.

  - If you plan to deploy multiple Enterprise Portals on the same server and those portals will connect to different Application Object Servers, you must update the web.config file. For more information, see [Install multiple Enterprise Portals on the same server](install-multiple-enterprise-portals-on-the-same-server.md).

  - If you plan to use host headers, review the SharePoint documentation about host headers and Web farms before you install Enterprise Portal.
    

    > [!IMPORTANT]
    > <P>If you attempt to install Enterprise Portal on an existing Internet Information Services (IIS) site that is already configured to use a host header, the installation fails, unless you create a <A href="https://go.microsoft.com/fwlink/?linkid=194948">BackConnectionHostNames</A> registry entry.</P>



## Topology overview

This topic uses the following Web server topology. The database, Application Object Server (AOS), and report server are not included in this list. Your Web server topology might differ.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Server</p></th>
<th><p>Description</p></th>
<th><p>Notes</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Administration Server</p></td>
<td><p>The following components and services are installed and running:</p>
<ul>
<li><p>Internet Information Services (IIS)</p></li>
<li><p>Microsoft SharePoint Server</p></li>
<li><p>SharePoint Central Administration Service</p></li>
<li><p>Microsoft SharePoint Foundation Web Application service</p></li>
<li><p>Microsoft Dynamics AX Enterprise Portal</p></li>
</ul></td>
<td><ul>
<li><p>This server is the SharePoint farm administration server.</p></li>
<li><p>The Microsoft SharePoint Foundation Web Application service must be running. You must configure this service in SharePoint Central Administration.</p></li>
<li><p>You must install Enterprise Portal on each front-end Web server before you install Enterprise Portal on this server.</p></li>
<li><p>When you install Enterprise Portal on this server by using Microsoft Dynamics AX Setup, you can select the <strong>Create Web site</strong> option or you can create the site later using SharePoint Central Administration. You must not select the <strong>Create Web site</strong> option on any front-end Web server.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Web front-end servers</p></td>
<td><ul>
<li><p>IIS</p></li>
<li><p>SharePoint Server</p></li>
<li><p>Microsoft SharePoint Foundation Web Application service</p></li>
<li><p>Microsoft Dynamics AX Enterprise Portal</p></li>
</ul></td>
<td><ul>
<li><p>SharePoint is installed on each server as a Web front-end.</p></li>
<li><p>You must install Enterprise Portal on each front-end Web server before you install Enterprise Portal on the SharePoint farm administration server.</p></li>
<li><p>When you install Enterprise Portal on each Web front-end server by using Microsoft Dynamics AX Setup, you must clear the <strong>Create Web site</strong> option.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Install and configure SharePoint

Install and configure SharePoint on each farm in the server.

Note the following requirements for the SharePoint installation.

1.  If you are using a load balancer, specify a site name in the **Load Balanced URL** field on the Web application that will host the Enterprise Portal site.

2.  The Microsoft SharePoint Foundation Web Application service must be running on the farm administration server. You must configure this service in SharePoint Central Administration.

3.  Configure the Web application to use the Business Connector proxy account. This means you must select the **Configurable** option and then enter the proxy credentials.

## Supported languages

If you want to deploy Enterprise Portal in multiple languages, you must download and deploy SharePoint language packs onto the web server before you install Enterprise Portal. You can download SharePoint language packs from Microsoft.com. Enterprise Portal is currently supported in the following languages:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Arabic</p>
<p>Chinese (Simplified)</p>
<p>Czech</p>
<p>Danish - 1030</p>
<p>Dutch (Netherlands)</p>
<p>Dutch (Belgium)</p>
<p>English</p>
<p>English (Australia)</p>
<p>English (Canada)</p>
<p>English (India)</p>
<p>English (Ireland)</p>
<p>English (Malaysia)</p>
<p>English (New Zealand)</p>
<p>English (Singapore)</p>
<p>English (South Africa)</p>
<p>English (UK)</p>
<p>English (US)</p>
<p>Estonian</p>
<p>Finnish</p>
<p>French (France)</p>
<p>French (Canada)</p></td>
<td><p>French (Belgium)</p>
<p>French (Switzerland)</p>
<p>German (Germany)</p>
<p>German (Austria)</p>
<p>German (Switzerland)</p>
<p>Hungarian</p>
<p>Icelandic</p>
<p>Italian</p>
<p>Italian (Switzerland)</p>
<p>Japanese</p>
<p>Latvian</p>
<p>Lithuanian</p>
<p>Norwegian</p>
<p>Polish</p>
<p>Portuguese (Brazilian)</p>
<p>Russian</p>
<p>Spanish (international)</p>
<p>Spanish (Mexico)</p>
<p>Swedish</p>
<p>Thai</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


To deploy Enterprise Portal in one of the languages list here, you must create a Web application in SharePoint and specify the new language. For more information, see [Create an Enterprise Portal site](create-an-enterprise-portal-site.md).

You do not have to create portals for specific languages. You just have to install SharePoint language packs, and then create a site as described in [Create an Enterprise Portal site](create-an-enterprise-portal-site.md). Portals are then displayed in the language that is specified for each user in the **Options** form in Microsoft Dynamics AX.

## Before you install Enterprise Portal

Perform the following tasks to verify that you can deploy Enterprise Portal in the SharePoint server farm.

  - Verify that you can open SharePoint Central Administration on the Enterprise Portal administration server.

  - Verify that you have the appropriate permissions to create sites by using SharePoint Central Administration to create a SharePoint team site.

  - Verify that you can browse the team site without prompts and resolve the URL without proxy errors or other problems.

## Install Enterprise Portal

This section describes how to install Enterprise Portal by using Setup. You must install Enterprise Portal on each Web front-end server before you install on the farm administration server. When you install Enterprise Portal on the Web front-end servers, you clear the option to create a site. This means that when you install Enterprise Portal on the Web front-end servers, Setup deploys files and configures settings on the server, but no site is created. When you install Enterprise Portal on the farm administration server, you select the option to create a site.


> [!TIP]
> <P>By default, when you install SharePoint, the system creates a Web application on port 80. Microsoft Dynamics AX Setup deploys an Enterprise Portal site on the port 80 Web application unless you specify a different Web application. If you do not intend to deploy Enterprise Portal on the default port-80 Web application, you must use SharePoint Central Administration to create a new Web application before you install Enterprise Portal. Also note, if you intend to deploy Enterprise Portal on a Web application that is already configured to use a host header, you must use SharePoint Central Administration to create a new Web application using the host header before you install Enterprise Portal. For any new Web application, you must specify the Business Connector proxy account as the application pool account in the <STRONG>Configurable</STRONG> list.</P>



1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on the computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Enter a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you’re installing AX 2012 R3, in the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Enterprise Portal (EP)**, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  On the **Select a file location** page, select the location where you want to install 32-bit versions of Microsoft Dynamics AX files, and then click **Next**.

9.  On the **Specify a location for configuration settings** page, specify whether you want Enterprise Portal to access configuration information from the registry on the local computer or from a shared configuration file. If you select to use a shared configuration file, you must enter the network location of the file. Click **Next**.

10. On the **Connect to an AOS instance** page, enter the name of the computer that is running the Application Object Server (AOS) instance that you want to connect to. You can optionally specify the name of the AOS instance, the TCP/IP port number, and the WSDL port for services. Click **Next**.
    

    > [!NOTE]
    > <P>If you entered AOS connection information for other Microsoft Dynamics AX components that are installed on this computer, this screen is not displayed. Subsequent installations on this computer reuse the existing AOS connection.</P>



11. On the **Specify Business Connector proxy account information** page, enter the password for the proxy account that is used by the .NET Business Connector. Click **Next**.

12. On the **Configure a Web site for Enterprise Portal** page, select a web site. If no Web sites are available in the list, you must cancel Setup, create a web site by using SharePoint Central Administration, and then try the installation again.
    
    We recommend that you select the **Configure for Windows SharePoint Services** option. If you select this option, Setup verifies that the site is a SharePoint site. If the site is not a SharePoint site, Setup extends the site in SharePoint. Setup also sets the application pool to run under the service account and sets the authentication method to Windows NTLM.
    

    > [!IMPORTANT]
    > <P>Note the following important information about the <STRONG>Create Web site</STRONG> option:</P>
    > <UL>
    > <LI>
    > <P>When you install Enterprise Portal on Web front-end servers in a server farm, you must clear this option. The site must be created only on the administration server for the Web farm.</P>
    > <LI>
    > <P>If you are installing Enterprise Portal on an administration server for a Web farm, select the <STRONG>Create Web site</STRONG> option to create a site at the following URL: http://<EM>ServerName</EM>/sites/DynamicsAX. Setup creates a new site that uses port 80.</P>
    > <LI>
    > <P>Clear this option if you are installing Enterprise Portal for a public site, such as an unsolicited vendor portal. For public sites, you must create the Enterprise Portal site by using the public site template. For more information, see <A href="create-a-public-enterprise-portal-site.md">Create a public Enterprise Portal site</A>.</P></LI></UL>

    
    Click **Next**.
    

    > [!NOTE]
    > <P>If your business or organization purchased a developer license for Microsoft Dynamics AX, you can change the URL for the web site, title, and description before you complete the installation. Modify the EPSetupParams file in the Application Object Tree (AOT) (<STRONG>Web</STRONG> &gt; <STRONG>Web Files</STRONG> &gt; <STRONG>Static Files</STRONG> &gt; <STRONG>EPSetupParams</STRONG>).</P>



13. On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

14. On the **Ready to install** page, click **Install**.

15. After the installation is complete, click **Finish** to close the wizard.

16. Repeat this procedure on every Web server in the server farm.

## Optional: Specify machineKey values in web.config files for sites in a Web farm

If Enterprise Portal pages display authentication and access errors after you installed Enterprise Portal on each server in the Web farm, you might have to specify values for machineKey properties in the web.config file of each server in the Web farm. MachineKey properties, validationKey and decryptionKey, are used to hash and decrypt authentication tickets and cookies. Values for machineKey properties must be the same on all servers in the Web farm.

1.  On the administration server for the Web farm, open the web.config file in a text editor such as Notepad. By default, the file is located in the following directory: C:\\Inetpub\\wwwroot\\wss\\VirtualDirectories\\*PortNumber*.

2.  Locate the machineKey section, and copy the validationKey and decryptionKey values to a separate text file. The following is an example of a machineKey section:
    
        <machineKey validationKey="4785A9C8F5FA32B47E5245AC48671291F1CE55735A475EB7" decryptionKey="D961976E181646326D64E01AB2052F5D076F0ABDE2C702FB" validation="SHA1" />

3.  Edit the web.config files on the other servers in the Web farm. Replace the existing machineKey values with the values that you copied from the administration server for the Web farm.

For more information about how to configure machineKey properties, see [How to: Configure MachineKey in ASP.Net 2.0](https://go.microsoft.com/fwlink/?linkid=117441), especially the "Web Farm Deployment Considerations" section.

## Configure firewall settings on Enterprise Portal servers

For information about the recommended firewall settings on an Enterprise Portal server, see [Firewall settings for Microsoft Dynamics AX components](firewall-settings-for-microsoft-dynamics-ax-components.md).

## Next steps

After you deploy Enterprise Portal in the Web farm, you must enable users to access the Enterprise Portal site. For more information, see [Enable users to access Enterprise Portal](enable-users-to-access-enterprise-portal.md). For information about other Enterprise Portal deployment and configuration tasks, see [Checklists for deploying Enterprise Portal sites](checklists-for-deploying-enterprise-portal-sites.md).

## See also

[Install and configure Windows AppFabric for Enterprise Portal](install-and-configure-windows-appfabric-for-enterprise-portal.md)

[Troubleshoot installation issues with Enterprise Portal and Role Centers](troubleshoot-installation-issues-with-enterprise-portal-and-role-centers.md)

  


