---
title: 'How to: Add Reports to Microsoft Dynamics AX'
TOCTitle: 'How to: Add Reports to Microsoft Dynamics AX'
ms:assetid: ba9d6e8c-86c1-4c66-8740-3885c9cf0f5c
ms:mtpsurl: https://technet.microsoft.com/library/Cc574427(v=AX.60)
ms:contentKeyID: 28119576
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Add Reports to Microsoft Dynamics AX 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following procedure describes how to add a report to a report model in Microsoft Visual Studio. You must also add the report project to the AOT to access the report from the AOT. In the AOT, you can see the report was added in the **SSRS Reports** \> **Reports** node.

### To add a report

1.  Open a reporting project in Microsoft Visual Studio.

2.  In Solution Explorer, right-click the reporting project that you want to add a report to and then click **Add Report**.

### To add a report project to the AOT

1.  Open a reporting project in Microsoft Visual Studio.

2.  In Solution Explorer, right-click the reporting project that contains a report that you want to add into Microsoft Dynamics AX, and then click **Add \[ReportProjectName\] to AOT**. The report design is now stored in the AOT.

The report can be used within the Microsoft Dynamics AX application. Add a menu item to run a report in the Microsoft Dynamics AX client. For more information, see [How to: Create a Menu Item for a Report](how-to-create-a-menu-item-for-a-report.md). As long as a report is stored in the AOT, you can define menu items for the reports. The reports do not need to be deployed to the report server until the reports need to be viewed. You can deploy the report to a report server from the AOT. In the AOT, go to **SSRS Reports** \> **Reports**, right-click the report to deploy and select **Deploy Element**.

There is a distinction between managing reports versus managing report projects. Storing a report in the AOT happens when you add a report to a Microsoft Dynamics AX Report Model. If you want to store your reporting project or business logic assemblies for your reports in the AOT, then you must add the report project into Microsoft Dynamics AX. When you add a report project to the AOT, the reporting project is added to the **Visual Studio Projects** \> **Dynamics AX Model Projects**. The following table summarizes the distinction between reports and report projects.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>AOT element</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Reports</p></td>
<td><ul>
<li><p>Stored and available in the AOT when it is added to a Microsoft Dynamics AX Report Model in Visual Studio.</p></li>
<li><p>Can be included in any number of reporting projects.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Report projects</p></td>
<td><ul>
<li><p>Stored and available in the AOT when you right-click the reporting project and click <strong>Add [project name] to AOT</strong>.</p></li>
<li><p>Used to manage a collection of reports or report business logic assemblies.</p></li>
</ul></td>
</tr>
</tbody>
</table>


For more information, see [Reporting Project Overview](reporting-project-overview.md). node.

## See also

[Report Integration and Customization Overview](report-integration-and-customization-overview.md)

[How to: Deploy Reports to a Report Server](how-to-deploy-reports-to-a-report-server.md)

[How to: Create a Menu Item for a Report](how-to-create-a-menu-item-for-a-report.md)

[How to: Customize a Report](how-to-customize-a-report.md)

