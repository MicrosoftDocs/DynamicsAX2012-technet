---
title: Deploy Microsoft Dynamics AX Web parts to a SharePoint site
TOCTitle: Deploy Microsoft Dynamics AX Web parts to a SharePoint site
ms:assetid: d0481af6-10c3-48ac-bec3-a8a68c3accc8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh575250(v=AX.60)
ms:contentKeyID: 39555413
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deploy Microsoft Dynamics AX Web parts to a SharePoint site 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to deploy Web parts for Enterprise Portal for Microsoft Dynamics AX to sites for SharePoint. For example, if your organization uses a standard SharePoint team site, you can use the procedure in this topic to deploy an Enterprise Portal Web part to that team site.

## Before you begin

Install Enterprise Portal on the web application that hosts the site, such as SharePoint 80. In Microsoft Dynamics AX Setup, clear the **Create Web site** option. By clearing the **Create Web site** option, you install the required files on the web application, but you do not create a new website that uses the Enterprise Portal template. For more information about how to install Enterprise Portal, see [Install Enterprise Portal on a single server](install-enterprise-portal-on-a-single-server.md).

## Deploy a Microsoft Dynamics AX Web part to a SharePoint site

1.  Click **System administration** \> **Setup** \> **Enterprise Portal** \> **Web sites**.

2.  Click **New** to add the SharePoint site to the list of sites. In the **Internal URL** field, enter the address of the SharePoint site.

3.  In the **Type** list, click **Web parts only**.

4.  Click the **General** tab.

5.  If this site can be viewed only by users in a specific partition or company, configure the **Partition independent** and **Company independent** options.

6.  Close the form to save your changes.

7.  Open the SharePoint v4.master style sheet from the following location. This path applies to Microsoft SharePoint 2010 products. For Microsoft SharePoint 2013 Products, change ‘14’ in the file path to ‘15’:
    
    C:\\Program Files\\Common Files\\Microsoft Shared\\Web Server Extensions\\14\\TEMPLATE\\GLOBAL\\v4.master

8.  Add the following element to the v4.master style sheet:
    
    \<SharePoint:CSSRegistration name= "/\_LAYOUTS/1033/STYLES/Themable/AXEP.css" runat="server"/\>
    

    > [!IMPORTANT]
    > <P>To enable a Microsoft Dynamics AX unified work list Web part in a standard SharePoint site, you also must add the following Java script elements to the v4.master style sheet:</P>
    > <P>&lt;script type="text/javascript" src="/_layouts/ep/scripts/jquery-min.js"&gt; &lt;/script&gt;</P>
    > <P>&lt;script type="text/javascript"&gt; var $jQ = jQuery.noConflict();&lt;/script&gt;</P>



9.  Save your changes, and close the file.

10. On the SharePoint site, create a new Web part page or edit an existing page, and then click **Add a Web part**.

11. Beneath the **Categories** list, click **Upload a Web part**.

12. Browse to the following location, and then click the Web part to add. For SharePoint 2013, change ‘14’ in the file path to ‘15’:
    
    C:\\Program Files\\Common Files\\Microsoft Shared\\Web Server Extensions\\14\\TEMPLATE\\FEATURES\\DynamicsAxWebParts\\WebParts

13. Click **Upload**. The site automatically updates the list. Click **Add a Web part** again, and then locate the **Imported Web parts** folder in the **Categories** list.

14. In the **Web Parts** list, click the Web part to add, and then click **Add**.

## See also

[Deploy Enterprise Portal and Role Centers](deploy-enterprise-portal-and-role-centers.md)

[Create an Enterprise Portal site](create-an-enterprise-portal-site.md)

  


