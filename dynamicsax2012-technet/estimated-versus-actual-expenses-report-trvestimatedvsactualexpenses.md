---
title: Estimated versus actual expenses report (TrvEstimatedVsActualExpenses)
TOCTitle: Estimated versus actual expenses report (TrvEstimatedVsActualExpenses)
ms:assetid: 22011d2b-8bb8-465d-b9f4-3338ac7a1eb5
ms:mtpsurl: https://technet.microsoft.com/library/Hh412242(v=AX.60)
ms:contentKeyID: 36916351
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.TrvEstimatedVsActualExpenses
---

# Estimated versus actual expenses report (TrvEstimatedVsActualExpenses) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view the estimated expense costs submitted in a travel requisition versus the actual expense costs submitted on the corresponding expense report.

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
<td><p>The expense report to be viewed on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Expense category</strong></p></td>
<td><p>The expense category of the expenses that are being evaluated.</p></td>
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
<td><p>TrvEstimatedVsActualExpenses</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\TrvEstimatedVsActualExpenses</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TrvEstimatedVsActualExpensesReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Travel and expense</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Estimated versus actual expenses</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - Ledger

  - TrvExpTable

  - TrvExpTrans

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


