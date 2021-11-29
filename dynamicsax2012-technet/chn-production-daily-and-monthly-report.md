---
title: (CHN) Production daily and monthly (report)
TOCTitle: (CHN) Production daily and monthly (report)
ms:assetid: 4fba8595-e3ca-4efd-b199-44b54c10e1b2
ms:mtpsurl: https://technet.microsoft.com/library/Dn169458(v=AX.60)
ms:contentKeyID: 53865948
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CHN) Production daily and monthly (report) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Generate a report that displays the planned and actual work time and efficiency for a selected work center and resource or working group during a specified time period.

## How to filter the data on this report

When you generate this report, the following default parameters are displayed. You can use these parameters to filter the data that will be displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>From date:</strong></p></td>
<td><p>Select the start date.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date:</strong></p></td>
<td><p>Select the end date.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Production unit:</strong></p></td>
<td><p>Select the production unit to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Resource group</strong></p></td>
<td><p>For the selected production unit, select the resource group or working group to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Resource:</strong></p></td>
<td><p>Select the resource to include on the report.</p></td>
</tr>
</tbody>
</table>


## How to work with reports

The following topics explain how to print a report and how to filter and sort the data on a report.

  - [Print or email a report](print-or-email-a-report.md)

  - [Filter the data on a report](filter-the-data-on-a-report.md)

  - [Sort the data on a report](sort-the-data-on-a-report.md)

## Details of this report

The following table explains where to find the report in the Application Object Tree (AOT) and how to navigate to the report in the Microsoft Dynamics AX client.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Detail</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Name of report in the AOT</p></td>
<td><p>ProdDailyMonthly_CN</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ProdDailyMonthly_CN</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ProdDailyMonthly_CN</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Production control</strong> &gt; <strong>Reports</strong> &gt; <strong>Reports (China)</strong> &gt; <strong>Production daily &amp; monthly report</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ProdDailyMonthlyTmp\_CN

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


