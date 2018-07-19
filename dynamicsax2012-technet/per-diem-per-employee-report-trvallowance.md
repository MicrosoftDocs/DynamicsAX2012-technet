---
title: Per diem per employee report (TrvAllowance)
TOCTitle: Per diem per employee report (TrvAllowance)
ms:assetid: f3eb38e1-2946-4d94-9fc9-1751d26f8902
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh394890(v=AX.60)
ms:contentKeyID: 36916373
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.TrvAllowance
---

# Per diem per employee report (TrvAllowance) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view the per diems given to an employee in a specified time period or on a specific expense report.

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
<td><p><strong>Per diem from date</strong></p></td>
<td><p>Select the date to start viewing the per diems given to an employee.</p></td>
</tr>
<tr class="even">
<td><p><strong>Per diem to date</strong></p></td>
<td><p>Select the date to stop viewing the per diems given to an employee.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Expense report number</strong></p></td>
<td><p>The number of the expense report that includes a per diem.</p></td>
</tr>
<tr class="even">
<td><p><strong>Expense category</strong></p></td>
<td><p>The expense categories that the per diem allowances are assigned to.</p></td>
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
<td><p>TrvAllowance</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\TrvAllowance</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TrvAllowance</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Travel and expense</strong> &gt; <strong>Reports</strong> &gt; <strong>Statistics</strong> &gt; <strong>Per diem per employee</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CompanyInfo

  - HcmWorker

  - Ledger

  - TrvExpTable

  - TrvExpTrans

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


