---
title: Create an Enterprise Portal site
TOCTitle: Create an Enterprise Portal site
ms:assetid: da9149f8-9bb8-4d95-b392-4c6954a60b5f
ms:mtpsurl: https://technet.microsoft.com/library/Dd362092(v=AX.60)
ms:contentKeyID: 35133077
author: Khairunj
ms.author: daxcpft
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# Create an Enterprise Portal site 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to create a site for Enterprise Portal for Microsoft Dynamics AX. After you create the site, you can configure it as an internal Microsoft Dynamics AX site, an employee self-service portal, a customer self-service portal, or a vendor self-service portal. For more information about how to configure the various kinds of portals, see the following topics:

  - [Checklist: Deploy an internal Enterprise Portal site that has Role Centers](checklist-deploy-an-internal-enterprise-portal-site-that-has-role-centers.md)

  - [Checklist: Deploy an employee self-service portal](checklist-deploy-an-employee-self-service-portal.md)

  - [Checklist: Deploy a vendor registration portal](checklist-deploy-a-vendor-registration-portal.md)

If you want to create an unsolicited vendor portal, you must create a public Enterprise Portal site. For more information, see [Create a public Enterprise Portal site](create-a-public-enterprise-portal-site.md) and [Checklist: Deploy an unsolicited vendor portal](checklist-deploy-an-unsolicited-vendor-portal.md).

By default, when you install Enterprise Portal, Setup creates a new Enterprise Portal intranet site on the SharePoint-80 web application. This site uses the **Microsoft Dynamics AX Enterprise Portal** template. This template includes all available modules, reports, and features. However, the information that is displayed for each user is determined by the user's role. For a complete description of the modules, reports, and features that are available in the **Microsoft Dynamics AX Enterprise Portal** template, see [Overview of Enterprise Portal for Microsoft Dynamics AX](overview-of-enterprise-portal-for-microsoft-dynamics-ax.md).

## Before you begin

Before you create a site, be aware of the following guidelines:

  - Use SharePoint Central Administration to create a new Web application on the Enterprise Portal server. Then deploy Enterprise Portal on the Web application by using Microsoft Dynamics AX Setup. For more information, see [Install Enterprise Portal on a single server](install-enterprise-portal-on-a-single-server.md).
    
    If you want to install multiple Enterprise Portals on the same server and you want portals to access different Application Object Servers, then you must edit the web.config file as described in [Install multiple Enterprise Portals on the same server](install-multiple-enterprise-portals-on-the-same-server.md).

  - If you create a new Web application in SharePoint Central Administration, do not select the **Negotiate (Kerberos)** authentication provider in the SharePoint **Create New Web Application** form. Enterprise Portal cannot complete the necessary Web request to create a new site if **Negotiate (Kerberos)** is selected as the authentication provider.

  - You cannot create separate Enterprise Portal intranet sites for different companies. If users have access to multiple companies, they can select the company that they want to view information for by using the **Company** list in Enterprise Portal.

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


3.  Deploy Enterprise Portal on the Web server, but clear the **Create Web site** option in the Microsoft Dynamics AX Setup wizard.

4.  Create the Web site as described in this topic.

You do not need to create portals for specific languages. After you install the SharePoint language packs and create a site as described in this topic, portals are displayed in the language specified for the user on the **Options** form if the language is listed here.

## Create an Enterprise Portal site

1.  In SharePoint Central Administration, under **Application Management**, click **Create site collections**.

2.  In the **Web Application** list, click **Change Web Application**, and then select **SharePoint–80** or another Web application.

3.  Enter appropriate information in the **Title and Description** and **Web Site Address** sections.
    

    > [!IMPORTANT]
    > <P>You must enter a unique title and description for each Enterprise Portal site. If you create a new Web site by using SharePoint Services or IIS Manager, and the title or site description matches an existing site, Enterprise Portal cannot be deployed on the new site.</P>



4.  If you downloaded and installed SharePoint language packs on the Web server the **Select a language** list is displayed in the **Create Site Collection** form. Select a language for this site.

5.  Under **Select a template**, click the **Custom** tab.

6.  Select the **Microsoft Dynamics Enterprise Portal** template.

7.  Enter information in the **Site Collection Administrators** and **Quota** sections, and then click **OK**.

**Additional steps for Microsoft Dynamics AX 2012 R3**

If you created the Enterprise Portal site with Microsoft Dynamics AX 2012 R3, then you must complete the following steps to view an Enterprise Portal site in a language other than English.

1.  Open the Enterprise Portal site that you just created.

2.  In the top left corner, click **Site Actions** \> **Site Settings**.

3.  Click **Language Settings**. Language settings display if language packs are installed.

4.  Select the language for this site.

5.  Save your changes.

6.  Close and reopen the site.

## Enable the Web server in Windows Firewall

After you install Enterprise Portal, enable **Web Server (HTTP)** in Windows Firewall. If you do not enable the Web server in Windows Firewall, you can view the site on the local server, but no other users can view the site. By default, when you enable **Web Server (HTTP)** in Windows Firewall, you enable port 80. If you configured the Enterprise Portal site for a port other than port 80, enable that port in Windows Firewall.

## Next steps

After you create a portal you must configure security, user access, and portal-wide settings. For more information, see [Checklists for deploying Enterprise Portal sites](checklists-for-deploying-enterprise-portal-sites.md).

## See also

[Checklist: Configure Role Centers](checklist-configure-role-centers.md)

[Install multiple Enterprise Portals on the same server](install-multiple-enterprise-portals-on-the-same-server.md)

  


