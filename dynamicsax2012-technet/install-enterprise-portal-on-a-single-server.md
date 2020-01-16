---
title: Install Enterprise Portal on a single server
TOCTitle: Install Enterprise Portal on a single server
ms:assetid: bd70dc6c-4a58-4097-a3cb-0e235528d60e
ms:mtpsurl: https://technet.microsoft.com/library/Gg731916(v=AX.60)
ms:contentKeyID: 35132843
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Install Enterprise Portal on a single server 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to install Enterprise Portal for Microsoft Dynamics AX on a single server. Businesses and organizations typically use a single-server deployment for development environments or testing.

For information about scale-out deployments, see [Install Enterprise Portal in a Web farm](install-enterprise-portal-in-a-web-farm.md). For information about how to install Enterprise Portal in an environment with two domain controllers and two firewalls for extranet deployments, see [Install Enterprise Portal in a traditional perimeter network](install-enterprise-portal-in-a-traditional-perimeter-network.md).

This topic includes the following sections.

  - Before you install Enterprise Portal

  - Pre-installation tasks

  - Install Enterprise Portal

  - Next steps

## Before you install Enterprise Portal

Complete the following tasks before you install Enterprise Portal and Role Centers:

  - If you installed a non-SYS layer model file in the Microsoft Dynamics AX environment, compile Microsoft Dynamics AX before you install Enterprise Portal. If you do not compile Microsoft Dynamics AX, the Enterprise Portal installation might fail.

  - If you want to deploy Enterprise Portal in multiple languages, you must download and deploy SharePoint language packs onto the web server before you install Enterprise Portal. You can download SharePoint language packs from Microsoft.com. Enterprise Portal is currently supported in the following languages:
    
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

  - Verify that the name of the server that will host Enterprise Portal does not include an underscore, for example EPserver\_1. If an Enterprise Portal server includes an underscore in the server name, lookups and web pages might display errors.

  - On the computer where you will install Enterprise Portal, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](http://go.microsoft.com/fwlink/?linkid=165377).

  - Verify that you have the appropriate permissions to install Enterprise Portal. If you are installing Enterprise Portal on a server that already hosts an Enterprise Portal deployment and you want to overwrite that deployment, you must have Full Control permission in SharePoint for the existing Enterprise Portal site collection. If you do not have Full Control permission, you will not be able to delete the existing site collection by using Setup. For more information about permissions, see [Verify that you have the required permissions for installation](verify-that-you-have-the-required-permissions-for-installation.md).

  - If you intend to deploy multiple Enterprise Portals on the same server and those portals will connect to different Application Object Servers, then you must update the web.config file. For more information, see [Install multiple Enterprise Portals on the same server](install-multiple-enterprise-portals-on-the-same-server.md).

  - For Secure Sockets Layer (SSL) encryption, you cannot install Enterprise Portal on a Web application that is already configured to use HTTP and HTTPS bindings. You must remove the HTTP binding from the site by using Internet Information Services (IIS) Manager before you install Enterprise Portal.

  - If you plan to use host headers, review the SharePoint documentation about host headers and Web farms before you install Enterprise Portal.
    

    > [!IMPORTANT]
    > <P>If you attempt to install Enterprise Portal on an existing Internet Information Services (IIS) site that is already configured to use a host header, the installation fails, unless you create a <A href="http://go.microsoft.com/fwlink/?linkid=194948">BackConnectionHostNames</A> registry entry.</P>



## Pre-installation tasks

Perform the following tasks to verify that you can deploy Enterprise Portal on the Web server.

1.  Verify that you can open SharePoint 2010 Central Administration on the Enterprise Portal server.

2.  Verify that you have the appropriate permissions to create sites by using SharePoint 2010 Central Administration to create a SharePoint team site.

3.  Verify that you can browse the team site without prompts and resolve the URL without proxy errors or other problems.

4.  If you intend to deploy or configure Enterprise Portal at a command prompt, verify that you can start the SharePoint 2010 Management Shell.

## Install Enterprise Portal

This section describes how to install Enterprise Portal by using Setup. If you are installing other Microsoft Dynamics AX components at the same time, the installation pages vary, based on the components that you are installing.


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

12. On the **Configure a Web site for Enterprise Portal** page, select a web site. If no web sites are available in the list, you must cancel Setup, create a web site by using SharePoint Central Administration, and then try the installation again.
    
    We recommend that you select the **Configure for Windows SharePoint Services** option. If you select this option, Setup verifies that the site is a SharePoint site. If the site is not a SharePoint site, Setup extends the site in SharePoint. Setup also sets the application pool to run under the service account and sets the authentication method to Windows NTLM.
    

    > [!IMPORTANT]
    > <P>Note the following important information about the <STRONG>Create Web site</STRONG> option:</P>
    > <UL>
    > <LI>
    > <P>Clear this option if you are installing Enterprise Portal for a public site, such as an unsolicited vendor portal. For public sites, you must create the Enterprise Portal site by using the public site template. For more information, see <A href="create-a-public-enterprise-portal-site.md">Create a public Enterprise Portal site</A>.</P>
    > <LI>
    > <P>If you are installing Enterprise Portal for a stand-alone installation select the <STRONG>Create Web site</STRONG> option to create a site at the following URL: http://<EM>ServerName</EM>/sites/DynamicsAX. Setup creates a new site that uses port 80.</P></LI></UL>

    
    Click **Next**.
    

    > [!NOTE]
    > <P>If your business or organization purchased a developer license for Microsoft Dynamics AX, you can change the URL for the web site, title, and description before you complete the installation. Modify the EPSetupParams file in the Application Object Tree (AOT) (<STRONG>Web</STRONG> &gt; <STRONG>Web Files</STRONG> &gt; <STRONG>Static Files</STRONG> &gt; <STRONG>EPSetupParams</STRONG>).</P>



13. On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

14. On the **Ready to install** page, click **Install**.

15. After the installation is complete, click **Finish** to close the wizard.

## Next steps

**Configure the firewall on the Enterprise Portal server**: For information about the recommended firewall settings on an Enterprise Portal server, see [Firewall settings for Microsoft Dynamics AX components](firewall-settings-for-microsoft-dynamics-ax-components.md).

## See also

[Enterprise Portal architecture](enterprise-portal-architecture.md)

[Checklists for deploying Enterprise Portal sites](checklists-for-deploying-enterprise-portal-sites.md)

  


