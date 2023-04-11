---
title: Statistics on cost groups report (TrvCostStatistics)
TOCTitle: Statistics on cost groups report (TrvCostStatistics)
ms:assetid: fb3328c4-a28a-40af-a80a-88500132a33c
ms:mtpsurl: https://technet.microsoft.com/library/Hh394892(v=AX.60)
ms:contentKeyID: 36916375
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.TrvCostStatistics
---

# Statistics on cost groups report (TrvCostStatistics) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view expense amounts categorized by cost group.

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
<td><p><strong>Expense report number</strong></p></td>
<td><p>The expense report that includes the costs that have been categorized into a cost group.</p></td>
</tr>
<tr class="even">
<td><p><strong>Statistics group</strong></p></td>
<td><p>The cost groups to include on the report.</p></td>
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
<td><p>TrvCostStatistics</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS reports\Reports\TrvCostStatistics</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TrvCostTypeStat</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Travel and expense</strong> &gt; <strong>Reports</strong> &gt; <strong>Statistics</strong> &gt; <strong>Statistics on cost groups</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CompanyInfo

  - DirPartyTable

  - HcmWorker

  - Ledger

  - TrvCostType

  - TrvCostTypeStatistics

  - TrvExpTable

  - TrvExpTrans

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


