---
title: Grant users access to reports
TOCTitle: Grant users access to reports
ms:assetid: 08d399b0-92b0-49b2-8e7b-9404ee227251
ms:mtpsurl: https://technet.microsoft.com/library/Aa496432(v=AX.60)
ms:contentKeyID: 35132533
author: Khairunj
ms.date: 04/14/2015
mtps_version: v=AX.60
---

# Grant users access to reports 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains how to give users access to reports. Two procedures are described in this topic. The procedure that you should use depends on whether you are running Microsoft SQL Server Reporting Services in native mode or SharePoint integrated mode.


> [!NOTE]
> <P>SharePoint integrated mode is supported if you are using Microsoft Dynamics AX 2012 R2 or later.</P>



## Assign users to the DynamicsAXBrowser role on the Report Manager site

If you are running Reporting Services in native mode, you must assign users or groups to the DynamicsAXBrowser role on the Report Manager site. The following procedure explains how to complete this task.

1.  Open the Report Manager website for the Reporting Services instance. By default, the URL is http://\[SSRSServerName\]:80/Reports.

2.  Click the **DynamicsAX** folder.

3.  Click **Folder Settings**.

4.  Click **Security**.

5.  Click **New Role Assignment**.

6.  Enter the Active Directory user name or group to assign to the DynamicsAXBrowser role.

7.  Select the **DynamicsAXBrowser** role.

8.  Click **OK**.


> [!NOTE]
> <P>If users want to save a report output file with Microsoft Excel format, the DynamicsAXBrowser role also needs to be assigned to the Home folder, as well.</P>



## Grant users permission to view reports in SharePoint

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
    > <P>If you want users of Enterprise Portal for Microsoft Dynamics AX to be able to filter reports by using a custom parameter value, select the <STRONG>Design</STRONG> check box. For more information about the permissions that are required to use Enterprise Portal, see <A href="enable-users-to-access-enterprise-portal.md">Enable users to access Enterprise Portal</A>.</P>



7.  Click **OK**.

## See also

[Security settings for reports](security-settings-for-reports.md)

  


