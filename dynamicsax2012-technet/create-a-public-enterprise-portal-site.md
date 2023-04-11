---
title: Create a public Enterprise Portal site
TOCTitle: Create a public Enterprise Portal site
ms:assetid: 5fe392a4-5683-469e-bcfe-ecfaa6e24883
ms:mtpsurl: https://technet.microsoft.com/library/Hh285823(v=AX.60)
ms:contentKeyID: 36607347
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Create a public Enterprise Portal site 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to create a public Enterprise Portal website that uses anonymous authentication. With a public Enterprise Portal site you can deploy an unsolicited registration portal so that potential vendors can register with your business or organization.

## Before you install Enterprise Portal

Complete the following tasks before you install Enterprise Portal and Role Centers:

  - If you installed a non-SYS layer model file in the Microsoft Dynamics AX environment, compile Microsoft Dynamics AX before you install Enterprise Portal. If you do not compile Microsoft Dynamics AX, the Enterprise Portal installation might fail.

  - Verify that the name of the server that will host Enterprise Portal does not include an underscore, for example EPserver\_1. If an Enterprise Portal server includes an underscore in the server name, lookups and web pages might display errors.

  - On the computer where you will install Enterprise Portal, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).
    
    For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377).

  - Verify that you have the appropriate permissions to install Enterprise Portal. If you are installing Enterprise Portal on a server that already hosts an Enterprise Portal deployment and you want to overwrite that deployment, you must have Full Control permission in SharePoint for the existing Enterprise Portal site collection. If you do not have Full Control permission, you will not be able to delete the existing site collection by using Setup. For more information about permissions, see [Verify that you have the required permissions for installation](verify-that-you-have-the-required-permissions-for-installation.md).

  - If you intend to deploy multiple Enterprise Portals on the same server and those portals will connect to different Application Object Servers, then you must update the web.config file. For more information, see [Install multiple Enterprise Portals on the same server](install-multiple-enterprise-portals-on-the-same-server.md).

  - For Secure Sockets Layer (SSL) encryption, you cannot install Enterprise Portal on a Web application that is already configured to use HTTP and HTTPS bindings. You must remove the HTTP binding from the site by using Internet Information Services (IIS) Manager before you install Enterprise Portal.

  - If you plan to use host headers, review the SharePoint documentation about host headers and Web farms before you install Enterprise Portal.
    

    > [!IMPORTANT]
    > <P>If you attempt to install Enterprise Portal on an existing Internet Information Services (IIS) site that is already configured to use a host header, the installation fails, unless you create a <A href="https://go.microsoft.com/fwlink/?linkid=194948">BackConnectionHostNames</A> registry entry.</P>



## About Enterprise Portal sites for multiple languages

If you want to deploy Enterprise Portal in multiple languages, you must complete the following tasks before you create the site, as described in this topic.

1.  Install SharePoint on the Web server.

2.  If you want to deploy Enterprise Portal in multiple languages, you must download and deploy SharePoint language packs onto the web server before you install Enterprise Portal. You can download SharePoint language packs from Microsoft.com. Enterprise Portal is currently supported in the following languages:
    
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
    <p>Danish</p>
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
    </tbody>
    </table>


3.  Create the web site as described in this topic.

## Create a new Web application in SharePoint Central Administration

By default, when you install the Enterprise Portal framework by using Setup, the system creates a Web application and a web site that use Integrated Windows authentication. You cannot use the default web application and web site for an Enterprise Portal public site, because a public site requires anonymous authentication. The following procedures describe how to create a new Web application with either SharePoint 2010 products or SharePoint Server 2013.

**Create a new web application with SharePoint 2010 products**

1.  Open SharePoint Central Administration (**Start** \> **Programs** \> **Microsoft SharePoint Products** \> **SharePoint Central Administration**).

2.  Create a new Web application (**Application Management** \> **Manage Web applications** \> **New**).

3.  In the **Authentication** section, verify that **Classic Mode Authentication** is selected.

4.  In the **IIS Web Site** section, click **Create a new IIS Web site**. You can adjust the **Port**, **Host Header**, and **Path** settings, as necessary, or you can leave the default settings.

5.  In the **Security Configuration** section, leave the default settings. You will configure authentication later in this topic.

6.  In the **Public URL** section, enter the information that you want.

7.  In the **Application Pool** section, click **Create a new application pool**, and then click **Configurable**. In the drop-down menu, select the name of the Business Connector proxy account. You can view the name of the Business Connector proxy account in the Microsoft Dynamics AX client on the **Administration** module, under **Setup** \> **Security** \> **System Service accounts**.

8.  Enter information in the remaining sections, and then click **OK**. SharePoint creates the new Web application.

**Create a new web application with SharePoint Server 2013**

Perform the following procedure in the SharePoint 2013 Management Shell to create a web application that uses classic mode authentication.


> [!WARNING]
> <P>When you execute the following command, SharePoint warns you that classic mode authentication is not recommended. You can ignore this warning for an Enterprise Portal public site because the site requires classic mode authentication.</P>



1.  Start the SharePoint 2013 Management Shell.

2.  At the command prompt, type the following command and press Enter:
    
    New-SPWebApplication -Name \<Name\> -ApplicationPool \<ApplicationPool\> -AllowAnonymousAccess -ApplicationPoolAccount \<ApplicationPoolAccount\> -Port \<Port\> -URL \<URL\>

Where:

\<Name\> is the name of the new web application. Specify any logical name.

\<ApplicationPool\> is the name of the application pool. Specify any logical name.

\-AllowAnonymousAccess is a parameter that enables anonymous access on the web application. This is required for a public site.

\<ApplicationPoolAccount\> is the user account that this application pool will run as. You must specify the .NET Business Connector proxy account.

\<Port\> is the port on which the web application will be created in IIS. Specify any available port.

\<URL\> is the public URL for production sites or the server name for test environments. For example: http://www.contoso.com or http://ContosoTestServer1

Examples

New-SPWebApplication -Name "Contoso Public Site" -ApplicationPool "ContosoAppPool" -AllowAnonymousAccess -ApplicationPoolAccount (Get-SPManagedAccount "contoso\\testuser1") -Port 2000 -URL "http://www.contoso.com"

New-SPWebApplication -Name "Contoso Public Site" -ApplicationPool "ContosoAppPool" -AllowAnonymousAccess -ApplicationPoolAccount (Get-SPManagedAccount "contoso\\testuser1") -Port 2525 -URL "http://ContosoTestServer1"

After you successfully create the web application, when you open the Central Administration page, you see a health rule warning that indicates that one or more web applications is enabled with classic authentication mode. This is warning reflects the recommendation to use claims-based authentication instead of classic mode authentication.

## Deploy Enterprise Portal on the new Web application

Use Microsoft Dynamics AX Setup to deploy Enterprise Portal binaries to the new Web application. If you previously installed Enterprise Portal on the server, you still need to run Setup to deploy binaries and files to the new web application. You must clear the **Create Web site** option in Setup. You will create the site later in this topic. For more information about how to deploy Enterprise Portal binaries to the web application, see [Install Enterprise Portal on a single server](install-enterprise-portal-on-a-single-server.md).

![Enterprise Portal Setup options](images/Hh285823.EPWebsiteSetup3(AX.60).png "Enterprise Portal Setup options")

## Create a site collection that uses the public template

Enterprise Portal includes separate templates for internal sites and public sites. Use this procedure to create a new site collection that uses the public template.

1.  In **SharePoint Central Administration** under **Application Management**, click **Create site collections**.

2.  In the **Web Application** section, select the Web applications that you created earlier in this document.

3.  Enter a title and description.
    

    > [!IMPORTANT]
    > <P>You must enter a unique title and description for each Enterprise Portal site. If you create a new web site by using SharePoint Services or IIS Manager, and a title or site description matches an existing site, Enterprise Portal will not deploy on the new site.</P>



4.  Specify a URL.

5.  **SharePoint Server 2013 only**: Select **2010** in the **Select experience version** list.

6.  In the **Template Selection** section, click **Custom**, and then click **Microsoft Dynamics Public**.

7.  Specify collection administrators and quota details.

8.  Click **OK**.

9.  After the new SharePoint site collection is created, open a command prompt, type iisreset /noforce, and then press ENTER.

## Configure anonymous authentication in IIS

You must configure the web site to use anonymous authentication in IIS.

1.  Open IIS manager (**Start** \> **Administrative Tools** \> **Internet Information Services (IIS) Manager**).

2.  Expand the local computer, expand the **Sites** directory, and then click the Web application that you created earlier in this topic.

3.  In the center pane under **IIS**, double-click **Authentication**.

4.  Click **Anonymous Authentication**, and then click **Enable**. Disable all other types of authentication.

## Configure anonymous authentication in SharePoint

You must configure the web site to use anonymous authentication in SharePoint.

1.  In **SharePoint Central Administration** under **Application Management**, click **Manage Web applications**.

2.  In the **Web Application** section, select the Web applications that you created earlier.

3.  Click **Authentication Providers**.

4.  Under **Zone**, click **Default**.

5.  Under **Anonymous Authentication**, click **Enable anonymous access**.

6.  Click **OK**.

## Enable guest user access in Microsoft Dynamics AX

Perform the following procedure in the Microsoft Dynamics AX client to enable the guest user account.

1.  Click **System administration**.

2.  Under **Common**, expand **Users** and then click the **Users** form.

3.  In the **User ID** column, click the **Guest** account and then click **Edit**.

4.  Select **Enabled**.

5.  In the **User's roles** section, click **Assign roles** and add the **Vendor anonymous (external)** role.

6.  Click **OK**.

## Prevent company navigation from displaying in the public site

By default, any new Enterprise Portal site includes a drop-down list that enables users to navigate among different companies if they have the appropriate permissions. Although guest users have no permissions to navigate companies, and the public site displays no company-specific information, we recommend that you disable the company navigation. This way, guest users cannot see the naming that is associated with your different companies.

1.  Click **System administration** \> **Setup** \> **Enterprise Portal** \> **Web sites**.

2.  Select the site that you created earlier, and then click the **General** tab.

3.  Clear the **Company independent** option.

4.  Click **Close**.

5.  Open a command prompt, type iisreset /noforce, and then press ENTER.

## View the site as an anonymous user

After you have enabled the guest-user account in Microsoft Dynamics AX and assigned the account to the appropriate roles, as described in [Enable users to access Enterprise Portal](enable-users-to-access-enterprise-portal.md), you can view the site as an anonymous user. To do this, enable anonymous-logon user authentication in a Web browser. The following procedure describes how to enable anonymous-logon user authentication for Internet Explorer. If you are using a Web browser other than Internet Explorer, see that product's documentation for information about how to enable anonymous-logon user authentication.

1.  Open Internet Explorer.

2.  Click **Tools** \> **Internet Options** \> **Security** \> **Internet** or **Local intranet** \> **Custom level**.

3.  Under **User Authentication**, select **Anonymous logon**, and then click **OK**.

4.  Open the site in a Web browser.

## See also

[Install multiple Enterprise Portals on the same server](install-multiple-enterprise-portals-on-the-same-server.md)

  


