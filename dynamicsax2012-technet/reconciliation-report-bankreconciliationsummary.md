---
title: Reconciliation report (BankReconciliationSummary)
TOCTitle: Reconciliation report (BankReconciliationSummary)
ms:assetid: d5b2e6f1-1cf2-42b4-b6f3-9565b4186f56
ms:mtpsurl: https://technet.microsoft.com/library/Hh556872(v=AX.60)
ms:contentKeyID: 39509607
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.BankReconciliationSummary
---

# Reconciliation report (BankReconciliationSummary) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to print a summary of the bank account reconciliation information. You can specify the date up to which to display information. You can include the number of reconciled bank transactions, total amounts for transactions, and a summary of all transactions.

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
<td><p><strong>Checking date</strong></p></td>
<td><p>Enter the ending date for the information to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Cleared transaction detail</strong></p></td>
<td><p>Select this check box to display the number of reconciled bank transactions.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Reconciliation summary</strong></p></td>
<td><p>Select this check box to display the total amounts for each type of reconciled and unreconciled bank transaction, such as checks, deposits, and transfers. The total amounts for balances are also displayed. These amounts include the opening balance and ending balance.</p></td>
</tr>
<tr class="even">
<td><p><strong>Uncleared transaction detail</strong></p></td>
<td><p>Select this check box to display each check, deposit, and transfer that has not yet cleared the bank.</p></td>
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
<td><p>BankReconciliationSummary</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\BankReconciliationSummary</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BankReconciliationSummary</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Cash and bank management</strong> &gt; <strong>Common</strong> &gt; <strong>Bank accounts</strong>. Select a bank account. On the <strong>Action Pane</strong>, click <strong>Account reconciliation</strong>. Select a bank statement date. Click <strong>Print</strong> &gt; <strong>Reconciliation summary</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - BankReconciliationSummaryTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the BankReconciliationSummaryDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


