---
title: (HUN) Cash order (report)
TOCTitle: (HUN) Cash order (report)
ms:assetid: 4c2121e4-ea94-4b80-a876-c07e7d8e7202
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ889272(v=AX.60)
ms:contentKeyID: 50626613
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (HUN) Cash order (report) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Generate and print a report that displays a list of cash documents for a cash account. The information in the report is based on selected criteria including the cash account, transaction date, and cash document type.

Click **Select** to specify the cash account, transaction date, and cash document type.

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
<td><p><strong>Original/copy</strong></p></td>
<td><p>Select whether the printing setup is used for the original report or for a copy.</p></td>
</tr>
<tr class="even">
<td><p><strong>Cash</strong></p></td>
<td><p>The code of the cash account that will be calculated in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Date</strong></p></td>
<td><p>The transaction date that will be calculated in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Order number</strong></p></td>
<td><p>The number of reimbursement slips and disbursement cash slips that will be calculated in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Document type</strong></p></td>
<td><p>The cash document type that will be used in the calculation of the report.</p></td>
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
<td><p>CashOrder_HU</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Report\CashOrder_HU</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>RCashOrderDispatcher</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Cash and bank management</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>Cash order</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CashOrderHeaderTmp

  - CashOrderLinesTmp

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


