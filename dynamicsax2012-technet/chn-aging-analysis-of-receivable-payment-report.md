---
title: (CHN) Aging analysis of receivable payment (report)
TOCTitle: (CHN) Aging analysis of receivable payment (report)
ms:assetid: 1c05705d-97b3-4cc0-9380-78cd239b052f
ms:mtpsurl: https://technet.microsoft.com/library/JJ945388(v=AX.60)
ms:contentKeyID: 51442779
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CHN) Aging analysis of receivable payment (report) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Generate and print a report that displays a customer’s payment aging details, including prepayment and payments that were made during various periods.

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
<td><p><strong>From period</strong></p></td>
<td><p>The start date for the report based on the selected period.</p></td>
</tr>
<tr class="even">
<td><p><strong>To period</strong></p></td>
<td><p>The end date for the report based on the selected period.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Aging period 1</strong></p></td>
<td><p>Enter the length, in the number of days, of aging period 1.</p></td>
</tr>
<tr class="even">
<td><p><strong>Aging period 2</strong></p></td>
<td><p>Enter the length, in the number of days, of aging period 2.</p></td>
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
<td><p>CustAgingAnalysisofPayment_CN</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustAgingAnalysisofPayment_CN</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustAgingAnalysisofPayment_CN</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Reports</strong> &gt; <strong>Reports (China)</strong> &gt; <strong>Aging analysis of receivable payment</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustAgingAnalysisofPayment\_CN

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


