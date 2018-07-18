---
title: Statement by dimensions report (LedgerTransStatement)
TOCTitle: Statement by dimensions report (LedgerTransStatement)
ms:assetid: 0b9d9372-873d-44d4-ac8f-c0c5dde0d6d8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242203(v=AX.60)
ms:contentKeyID: 36056610
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.LedgerTransStatement
---

# Statement by dimensions report (LedgerTransStatement) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Dimension statement** report displays account and transaction information by account.

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
<td><p><strong>Transactions</strong></p></td>
<td><p>Select the origin of the transactions to be reported.</p></td>
</tr>
<tr class="even">
<td><p><strong>Primary financial dimension set</strong></p></td>
<td><p>Select the primary financial dimension set.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Secondary financial dimension set</strong></p></td>
<td><p>Select the secondary financial dimension set.</p></td>
</tr>
<tr class="even">
<td><p><strong>Group per secondary dimension set</strong></p></td>
<td><p>Select this this check box to print the subtotal amount for the primary financial dimension set.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Date interval</strong></p></td>
<td><p>Select the date interval for the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong></p></td>
<td><p>Enter or select the start of the date range to print transactions for.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Enter or select the end of the date range to print transactions for.</p></td>
</tr>
<tr class="even">
<td><p><strong>New page</strong></p></td>
<td><p>Select this check box to insert a page break after each primary financial dimension set.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Specification</strong></p></td>
<td><p>Select the level when the transactions should be totaled. For example, if you select <strong>Month</strong>, a line including the total sum is displayed per month.</p></td>
</tr>
<tr class="even">
<td><p><strong>Posting layer</strong></p></td>
<td><p>Select the posting layer to print on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Sales tax specification</strong></p></td>
<td><p>Select this check box to include the sales tax specification for each transaction line.</p></td>
</tr>
<tr class="even">
<td><p><strong>Offset account</strong></p></td>
<td><p>Select this check box to print the offset account on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Currency total</strong></p></td>
<td><p>Select this check box to print the currency total for each financial dimension on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Empty periods</strong></p></td>
<td><p>Select the check box to display empty periods on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Without transactions</strong></p></td>
<td><p>Select this check box to include on the report financial dimension sets that do not have transactions.</p></td>
</tr>
<tr class="even">
<td><p><strong>Include opening transaction amounts in detail</strong></p></td>
<td><p>Select this check box to exclude opening transactions in the line of the report that lists the opening balance. Opening transactions are displayed in the report detail.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Include closing</strong></p></td>
<td><p>Select this check box to include closing transactions on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Include reversed</strong></p></td>
<td><p>Select this check box to include any reversed transactions on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Cash flow forecasts</strong></p></td>
<td><p>The information displayed in this field group is determined by your selections when you create a query.</p></td>
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
<td><p>LedgerTransStatement</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ LedgerTransStatement</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerAccountTransStatement</p>
<p>LedgerAccountTransStatementAction</p>
<p>LedgerDimensionTransStatement</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Dimension statement</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - BudgetTransactionHeader table

  - BudgetTransactionLine table

  - GeneralJournalAccountEntry table

  - LedgerCov table

  - LedgerTransStatementTmp table


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the LedgerTransStatementDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


