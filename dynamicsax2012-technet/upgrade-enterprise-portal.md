---
title: Upgrade Enterprise Portal
TOCTitle: Upgrade Enterprise Portal
ms:assetid: 9d80163e-7c4c-44bb-8240-b3e0e9505077
ms:mtpsurl: https://technet.microsoft.com/library/Aa548623(v=AX.60)
ms:contentKeyID: 35132784
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- EP upgrade
---

# Upgrade Enterprise Portal 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to upgrade Enterprise Portal for Microsoft Dynamics AX. You must meet all of the prerequisites and complete the procedures in this topic to upgrade an Enterprise Portal deployment to Microsoft Dynamics AX 2012 R2.

## Important details about Enterprise Portal upgrades

This section describes the changes to Enterprise Portal data, code, pages, and other objects when you run the Microsoft Dynamics AX 2012 R2 **Data upgrade checklist**.


> [!NOTE]
> <P>The <STRONG>Data upgrade checklist</STRONG> automatically upgrades Enterprise Portal from Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack to Microsoft Dynamics AX 2012 R2. You do not need to complete the tasks in this topic if you are upgrading Enterprise Portal from Microsoft Dynamics AX 2012 or Microsoft Dynamics AX 2012 Feature Pack to Microsoft Dynamics AX 2012 R2.</P>



  - The **Data upgrade checklist** automatically upgrades Enterprise Portal ASP.NET pages from Microsoft Dynamics AX 2009 to Microsoft Dynamics AX 2012 R2.

  - If your business or organization currently uses Enterprise Portal on Microsoft Dynamics AX 4.0 or earlier versions, you must upgrade to Microsoft Dynamics AX 2009 before you can upgrade to Microsoft Dynamics AX 2012 R2. Also be aware that the Enterprise Portal framework in Microsoft Dynamics AX 4.0 supported X++ objects, whereas the Enterprise Portal framework in Microsoft Dynamics AX 2012 R2 supports only ASP.NET objects, not X++ objects. After you upgrade to Microsoft Dynamics AX 2012 R2, the **Data upgrade checklist** creates a list of all X++ objects that you must manually convert to ASP.NET before the objects can work with the Enterprise Portal framework in Microsoft Dynamics AX 2012. For more information, see [Framework Changes](https://go.microsoft.com/fwlink/?linkid=229073).

  - The **Data upgrade checklist** does not change any Enterprise Portal parameters.

  - The **Data upgrade checklist** and Enterprise Portal Setup manage all changes to the Web.config file. If your earlier implementation of Enterprise Portal was configured to connect to a different Application Object Server (AOS) by using an .axc file, this configuration is upgraded automatically.

  - Enterprise Portal Setup automatically upgrades themes and style sheets. If you modified a style sheet for your earlier implementation of Enterprise Portal, merge the changes when you run the **Data upgrade checklist**, before you run Enterprise Portal Setup.

  - The **Data upgrade checklist** identifies proxy files and user controls that must be updated before they can work with Enterprise Portal for Microsoft Dynamics AX 2012 R2. You must resolve code differences in the proxy files and recompile user controls so that the proxy files and user controls work with Enterprise Portal.

  - Settings for end user personalization and customization of Enterprise Portal must be reset after the upgrade.

## Before you upgrade

You must complete the following tasks before you upgrade Enterprise Portal. Otherwise, the upgrade fails.

1.  Verify that you are a site administrator in SharePoint for the existing Enterprise Portal site.

2.  Use Internet Information Services (IIS) manager to configure the site for Integrated Windows authentication, or NTLM authentication. The upgrade process for Enterprise Portal fails if an Enterprise Portal site is configured to use anonymous authentication. After the site is upgraded, you can configure the site for anonymous authentication. For information about how to configure authentication in IIS, see the online documentation for IIS.

3.  You must complete the Microsoft Dynamics AX 2012 R2 **Data upgrade checklist** before you upgrade Enterprise Portal. The **Data upgrade checklist** makes important changes to data and Enterprise Portal objects. These changes are described later in this topic.

4.  Enterprise Portal for Microsoft Dynamics AX 2012 R2 requires either Microsoft SharePoint Foundation 2010 or Microsoft SharePoint Server 2010. You must upgrade earlier versions of SharePoint to one of these versions before you upgrade Enterprise Portal. For more information, see [Upgrading to SharePoint Foundation 2010](https://go.microsoft.com/fwlink/?linkid=198146) or [Upgrading to SharePoint Server 2010](https://go.microsoft.com/fwlink/?linkid=198148).

## Upgrade Enterprise Portal

This section describes how to upgrade an Enterprise Portal site. You must complete the procedures in this section in the following order:

1.  Use SharePoint Central Administration to create a new Web application.

2.  Install Enterprise Portal on the new Web application.

3.  Attach the content database from your Microsoft Dynamics AX 2009 Enterprise Portal site to the new Web application.

4.  Resolve URL conflicts.

5.  Reinstall Enterprise Portal to start the code upgrade.

## Create a new Web application

Use SharePoint 2010 Central Administration to create a new Web application. For more information, see [Create a Web application (SharePoint Server 2010)](https://go.microsoft.com/fwlink/?linkid=205797).

## Install Enterprise Portal on the new Web application

Use the following procedure to install Enterprise Portal on the new Web application.

1.  Start Microsoft Dynamics AX Setup.

2.  Advance through the first wizard pages.

3.  On the **Modify Microsoft Dynamics AX installation** page, select **Add or modify components**. Click **Next**.

4.  On the **Add or modify components** page, expand **Server Components**, expand **Web Server Components**, and then select **Enterprise Portal (EP)**. Click **Next**.

5.  On the **Specify Business Connector proxy account information** page, enter the domain\\username and password for the service account. Click **Next**.

6.  On the **Configure a Web site for Enterprise Portal** page, select the existing Microsoft Dynamics AX 2009 Enterprise Portal site.

7.  Select the **Configure for Windows SharePoint Services** option so that Setup can configure the application pool to run under the Business Connector proxy account. Setup can also set the authentication method to Windows NTLM.

8.  Clear the **Create Web site** option. If you select this option, Setup upgrades your Microsoft Dynamics AX 2009 Enterprise Portal site and creates an additional site.

9.  On the **Ready to install** page, click **Install**.

10. Complete the wizard. Setup can take up to one hour to complete the upgrade and installation.

## Attach the content database from your Microsoft Dynamics AX 2009 Enterprise Portal site to the new Web application

To retain content from an earlier version of Enterprise Portal and display that content in your Microsoft Dynamics AX 2012 R2 Enterprise Portal site, you must attach the old content database to your new Web application. For more information, see [Attach databases and upgrade to SharePoint Server 2010](https://go.microsoft.com/fwlink/?linkid=205805).

## Resolve URL conflicts

Delete the old site in the Microsoft Dynamics AX client by using the **Web sites** form. Click **System administration** \> **Setup** \> **Enterprise Portal** \> **Web sites**.

After you delete the old site, click **Register site**, and then enter the information about the new site. Repeat this process until you have registered each site. If you need help finding information about your sites, open SharePoint Central Administration, and then click **Application Management** \> **View all site collections**. If necessary, use the **Web Application** list to select the application that hosts your Enterprise Portal sites.

## Reinstall Enterprise Portal to upgrade the code

Reinstall Enterprise Portal on the new Web application so that the site upgrades the Enterprise Portal code. Repeat the installation process that is described earlier in this topic.

## After you upgrade Enterprise Portal

After the installation and upgrade are finished, follow these steps:

1.  If you upgraded an Enterprise Portal site that uses anonymous authentication, and you configured the site for Integrated Windows, or NTLM, authentication at the start of the upgrade process, you can now reconfigure the site for anonymous authentication. For information about how to configure authentication, see the online documentation for IIS.

2.  Verify that existing permissions for SharePoint and Microsoft Dynamics AX were retained during the upgrade process.

3.  Test the upgraded site on a staging server before you move the site into a production environment.

## See also

[Troubleshoot installation issues with Enterprise Portal and Role Centers](troubleshoot-installation-issues-with-enterprise-portal-and-role-centers.md)

  


