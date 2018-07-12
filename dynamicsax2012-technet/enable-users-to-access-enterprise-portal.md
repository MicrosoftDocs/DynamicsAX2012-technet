---
title: Enable users to access Enterprise Portal
TOCTitle: Enable users to access Enterprise Portal
ms:assetid: 2adbf75e-a599-45ca-a849-765185bf7897
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd309631(v=AX.60)
ms:contentKeyID: 36607345
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- access EP
- EP access
- EP users
---

# Enable users to access Enterprise Portal 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to grant users and groups access to Enterprise Portal for Microsoft Dynamics AX.

## Grant users access to Enterprise Portal

Use the following procedure to grant users and groups access to one of the following:

  - Enterprise Portal with Role Centers

  - Employee self-service portal

  - Vendor self-service portal

  - Customer self-service portal

To grant users access to an unsolicited vendor portal or a public portal, see “Grant users access to a public site” later in this topic.

## Add users to SharePoint

You must add users or groups to SharePoint before users can access Enterprise Portal or view content in Role Centers.

1.  Open the Enterprise Portal site in a Web browser. By default, the URL is http://*server\_name*/sites/DynamicsAX.

2.  On the menu bar, click **Site Actions** \> **Site Permissions**.

3.  Click **Grant Permissions**.

4.  In the **Users/Groups** text box, enter the name of each user or group, and then click **Check Names**.

5.  Under **Grant permissions**, click the permission level that you want to set. At a minimum, users and groups must have Read permissions.
    
      - If you do not want users to be able to personalize their Role Center pages or modify the shared view of a Web part, assign Read permissions.
    
      - If you want users to be able to personalize their Role Center pages and modify the shared view of a Web part, assign Contribute permissions.
    
      - If you want users to be able to personalize their Role Center pages, but you do not want them to be able to modify the shared view of a Web part, assign Read permissions, and then configure the set of Read permissions in SharePoint. From the Enterprise Portal site, click **Site Actions** \> **Site Permissions** \> **Permission Levels**. Click the **Read** permission link. Under **Personal Permissions**, select the options that you want.
    
      - If you want users to be able to filter reports using a custom parameter value, assign Design permissions.
        
        For more information about how to work with reports, see [Manage reports](manage-reports.md).
    
      - If you want users to be able to add and modify indicators and key performance indicators (KPIs), assign Design permissions.
        
        For more information about how to work with indicators and key performance indicators, see [Manage business overview information](manage-business-overview-information.md).

6.  Click **OK**.

Internal users can now view Enterprise Portal in a Web browser. If you granted users access to an Enterprise Portal with Role Centers, then those users can now view content in their Role Centers. Page access and the content that is displayed in Enterprise Portal and Role Centers are automatically trimmed according to both the user's security role in Microsoft Dynamics AX and the permissions that you specified in SharePoint.


> [!NOTE]
> <P>If users are prompted to enter their credentials when they view the Enterprise Portal site, they can automate authentication by adding the site to the list of local intranet sites. In Internet Explorer, click <STRONG>Tools</STRONG> &gt; <STRONG>Internet Options</STRONG> &gt; <STRONG>Security</STRONG> &gt; <STRONG>Local intranet</STRONG> &gt; <STRONG>Sites</STRONG>.</P>



## Grant users access to a public site

To grant users access to a public site, you must create the site and configure anonymous authentication. For more information, see [Create a public Enterprise Portal site](create-a-public-enterprise-portal-site.md). After you create the site and configure anonymous authentication, you must assign the **Guest** user account to the **Guest** security role in the **Users** form. For more information, see [Assign users to security roles](assign-users-to-security-roles.md).

## See also

[Checklist: Deploy an internal Enterprise Portal site that has Role Centers](checklist-deploy-an-internal-enterprise-portal-site-that-has-role-centers.md)

[Checklist: Deploy an employee self-service portal](checklist-deploy-an-employee-self-service-portal.md)

[Checklist: Deploy an unsolicited vendor portal](checklist-deploy-an-unsolicited-vendor-portal.md)

[Checklist: Deploy a vendor registration portal](checklist-deploy-a-vendor-registration-portal.md)

  


