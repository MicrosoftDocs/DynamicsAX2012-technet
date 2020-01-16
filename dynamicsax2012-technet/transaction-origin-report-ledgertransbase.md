---
title: Transaction origin report (LedgerTransBase)
TOCTitle: Transaction origin report (LedgerTransBase)
ms:assetid: f6f57c7b-85ba-4d86-813c-ecc876fc4c28
ms:mtpsurl: https://technet.microsoft.com/library/Hh692485(v=AX.60)
ms:contentKeyID: 41702382
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.LedgerTransBase
---

# Transaction origin report (LedgerTransBase) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This report displays general ledger transactions and transaction origin information.

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
<td><p><strong>New page</strong></p></td>
<td><p>Select this check box to insert a page break between each account.</p></td>
</tr>
<tr class="even">
<td><p><strong>Ledger</strong></p></td>
<td><p>Select this check box to include transactions from general journals, Fixed assets, and Budgeting.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Accounts receivable</strong></p></td>
<td><p>Select this check box to include transactions from Accounts receivable, such as customer invoices and payments.</p></td>
</tr>
<tr class="even">
<td><p><strong>Accounts payable</strong></p></td>
<td><p>Select this check box to include transactions from Accounts payable, such as vendor invoices and payments, and promissory notes.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Inventory management</strong></p></td>
<td><p>Select this check box to include transactions from Inventory and warehouse management, such as item movement transactions and item receipts.</p></td>
</tr>
<tr class="even">
<td><p><strong>Production</strong></p></td>
<td><p>Select this check box to include transactions from Product information management, such as item consumption and work center consumption transactions.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Bank</strong></p></td>
<td><p>Select this check box to include transactions from Cash and bank management, such as check reversals and deposit slip payment cancellations.</p></td>
</tr>
<tr class="even">
<td><p><strong>Sales tax</strong></p></td>
<td><p>Select this check box to include transactions that have a sales tax reference, such as customer invoices that include a sales tax percentage.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Project</strong></p></td>
<td><p>Select this check box to include transactions from Project management and accounting, such as hour, expense, fee, and on-account transactions, which can be charged to customers.</p></td>
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
<td><p>LedgerTransBase</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\LedgerTransBase</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerTransBase</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Reconciliation</strong> &gt; <strong>Specification</strong> &gt; <strong>Transaction origin</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - LedgerTransBaseTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the LedgerTransBaseDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


