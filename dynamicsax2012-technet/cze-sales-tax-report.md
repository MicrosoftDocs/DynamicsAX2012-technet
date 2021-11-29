---
title: (CZE) Sales tax (report)
TOCTitle: (CZE) Sales tax (report)
ms:assetid: 9274925d-6406-45a4-9576-4b93475cb90a
ms:mtpsurl: https://technet.microsoft.com/library/JJ874410(v=AX.60)
ms:contentKeyID: 50619726
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CZE) Sales tax (report) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Generate a report that displays the sales tax transaction information from selected accounts within a specified time frame. You can also select to reconcile, on the report, the sales tax transactions and the main accounts based on the value-added tax (VAT) register date.

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
<td><p><strong>Date</strong> <br />
(In the <strong>From</strong> field group)</p></td>
<td><p>Select the earliest date for the transactions to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Voucher</strong> <br />
(In the <strong>From</strong> field group)</p></td>
<td><p>Enter the starting voucher number for transactions to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Main account</strong> <br />
(In the <strong>From</strong> field group)</p></td>
<td><p>Select the main account to start from for the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Date</strong> <br />
(In the <strong>To</strong> field group)</p></td>
<td><p>Select the last date for the transactions to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Voucher</strong> <br />
(In the <strong>To</strong> field group)</p></td>
<td><p>Enter the last voucher number to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Main account</strong> <br />
(In the <strong>To</strong> field group)</p></td>
<td><p>Select the last main account to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Include details</strong></p></td>
<td><p>Select this check box to include VAT reconciliation details on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Reconcile by VAT register date</strong></p></td>
<td><p>Select this check box to include a reconciliation of sales tax transactions for the main accounts based on the VAT registration date.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Differences only</strong></p></td>
<td><p>Select this check box to show only the sales tax transaction differences on the report.</p></td>
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
<td><p>TaxLedgerReconciliation</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\TaxLedgerReconciliation</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxReport_LedgerReconciliation</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Reconciliation</strong> &gt; <strong>Sales tax</strong> &gt; <strong>Sales tax</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TaxLedgerReconciliationTmp

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


