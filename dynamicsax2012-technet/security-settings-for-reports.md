---
title: Security settings for reports
TOCTitle: Security settings for reports
ms:assetid: fd45fcf5-f9c7-4f28-98c9-be021a6cbfe2
ms:mtpsurl: https://technet.microsoft.com/library/Hh271484(v=AX.60)
ms:contentKeyID: 36384115
author: Khairunj
ms.date: 06/04/2014
mtps_version: v=AX.60
---

# Security settings for reports 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To grant users access to reports, you must configure security settings in Microsoft Dynamics AX, Microsoft SQL Server Reporting Services or Microsoft SharePoint, and Microsoft SQL Server Analysis Services. This topic describes the tasks that you must complete in each product.

## Configure security settings in Microsoft Dynamics AX

To configure security settings in Microsoft Dynamics AX, complete the following tasks:

  - Verify that each Microsoft Dynamics AX role is assigned the correct duties and privileges, so that users (who are assigned to the roles) can access the appropriate reports. For more information, see [Create or modify a security role](create-or-modify-a-security-role.md).

  - Assign users to Microsoft Dynamics AX roles. For more information, see [Assign users to security roles](assign-users-to-security-roles.md).

  - Help secure the data that is displayed on reports. For more information, see [Data security in Microsoft Dynamics AX](data-security-in-microsoft-dynamics-ax.md).

## Configure security settings in Reporting Services

If you are running Reporting Services in native mode, complete the following tasks to configure security settings in Reporting Services.

## Assign users and groups to the DynamicsAXBrowser role

Follow these steps to assign users and groups to the DynamicsAXBrowser role on the Report Manager website.

1.  Open the Report Manager website for the Reporting Services instance. By default, the URL is http://\[SSRSServerName\]:80/Reports\_\[SSRSInstanceName\].

2.  Click the **DynamicsAX** folder.

3.  Click **Folder Settings**.

4.  Click **Security**.

5.  Click **New Role Assignment**.

6.  Enter the Active Directory user name or group to assign to the DynamicsAXBrowser role.

7.  Select the **DynamicsAXBrowser** role.

8.  Click **OK**.

## Restrict access to report folders and reports

We recommend that you use the security features and tools that are included in Reporting Services to help control access to report folders and published reports. For detailed conceptual information and step-by-step tutorials that can help you administer security in Reporting Services, see the SQL Server documentation.

## Configure security settings in SharePoint

If you are running Reporting Services in SharePoint integrated mode, you must grant users permission to view reports in SharePoint. To grant this permission, grant users **Read** permission to the document library that stores the reports. Alternatively, if the document library inherits permissions from the site, you can grant users **Read** permission to the site. The following procedure describes how to grant users **Read** permission to the site.


> [!IMPORTANT]
> <P>If the SharePoint site is configured for claims-based authentication, you must also grant the following accounts <STRONG>Read</STRONG> permission to the document library or site:</P>
> <UL>
> <LI>
> <P>The account that is used as the Business Connector proxy</P>
> <LI>
> <P>The account that is used to run the Microsoft Dynamics AX Application Object Server (AOS) service.</P></LI></UL>



1.  Open your browser and navigate to the SharePoint site that contains the document library that stores the reports.

2.  Click **Site Actions** \> **Site Permissions**.

3.  Click **Grant Permissions**. The **Grant Permissions** window is displayed.

4.  In the **Users/Groups** field, enter the Active Directory names of the users or groups that you want to view reports.

5.  In the **Grant Permissions** area, select the **Grant users permission directly** option.

6.  Select the **Read** check box.
    

    > [!NOTE]
    > <P>If you want Enterprise Portal users to be able to filter reports using a custom parameter value, select the <STRONG>Design</STRONG> check box. For more information about the permissions required to use Enterprise Portal, see <A href="enable-users-to-access-enterprise-portal.md">Enable users to access Enterprise Portal</A>.</P>



7.  Click **OK**.

## Configure security settings in Analysis Services

Some reports use Analysis Services cubes to access data. Before users can view data on these reports, you must assign the users to roles in Analysis Services. For more information, see [Grant users access to cubes](grant-users-access-to-cubes.md).

  


