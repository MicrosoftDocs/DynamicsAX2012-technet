---
title: Trial balance report (LedgerTrialBalance)
TOCTitle: Trial balance report (LedgerTrialBalance)
ms:assetid: adfc67a0-4681-4ad4-afe3-2dfb4e12fd0f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa589532(v=AX.60)
ms:contentKeyID: 36060211
ms.date: 01/20/2016
mtps_version: v=AX.60
f1_keywords:
- trial balance
- SSRS_Reports.Reports.LedgerTrialBalance
- balance report
- trial balance report
---

# Trial balance report (LedgerTrialBalance) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Trial balance** report displays full details of the ledger accounts. The report information includes opening balances, debits, credits, and the resulting balances for a given date range.

The general purpose of the trial balance is to expose any errors for account balances. All accounts that have debit balances must equal all accounts that have credit balances.


> [!NOTE]
> <P>We recommend that you use Management Reporter for Microsoft Dynamics ERP to create, maintain, deploy, and view financial reports. Management Reporter lets you design financial reports based on ledger accounts and financial dimensions, drill down to transaction-level detail, and use web-based report viewing. For more information about how to print financial reports by using Management Reporter, see <A href="http://go.microsoft.com/fwlink/?linkid=324762">Management Reporter for Microsoft Dynamics ERP</A>.</P>



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
<td><p><strong>Primary financial dimension set</strong></p></td>
<td><p>Select the primary financial dimension set for the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Secondary financial dimension set</strong></p></td>
<td><p>Select the secondary financial dimension set for the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Date interval</strong></p></td>
<td><p>Select the current date interval for the report.</p></td>
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
<td><p>Select this check box to insert a page break between each account.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Posting layer</strong></p></td>
<td><p>Select how the posting layer or posting layer combination should be included for the selected column.</p>
<ul>
<li><p><strong>Current</strong> – The column will contain transactions that are included in the <strong>Current</strong> posting layer.</p></li>
<li><p><strong>Operations</strong> – The column will contain transactions that are included in the <strong>Current</strong> or <strong>Operations</strong> posting layers.</p></li>
<li><p><strong>Tax</strong> – The column will contain transactions that are included in the <strong>Current</strong> or <strong>Tax</strong> posting layers.</p></li>
<li><p><strong>Operations minus tax</strong> – The column will contain the net transactions from the <strong>Operations</strong> posting layer, minus the <strong>Tax</strong> posting layer.</p></li>
<li><p><strong>Only operations</strong> – The column will contain transactions that are included in the <strong>Operations</strong> posting layer.</p></li>
<li><p><strong>Only tax</strong> – The column will contain transactions that are included in the <strong>Tax</strong> posting layer.</p></li>
<li><p><strong>Operations plus tax</strong> – The column will contain transactions that are included in the <strong>Operations</strong> or <strong>Tax</strong> posting layers.</p></li>
<li><p><strong>Total</strong> – The column will contain transactions that are included in the <strong>Current</strong>, <strong>Operations</strong>, or <strong>Tax</strong> posting layers.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Include opening transaction amounts in detail</strong></p></td>
<td><p>Select this check box to exclude opening transactions from the line of the report that lists the opening balance. Opening transactions are displayed in the report detail.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Closing transactions</strong></p></td>
<td><p>Select this check box to display closing transactions as transactions.</p></td>
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
<td><p>LedgerTrialBalance</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerTrialBalance</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerProvisionalBalance</p>
<p>LedgerTrialBalance</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Detailed trial balance</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DimensionAttributeValueCombination table

  - DimensionFocusBalance table

  - GeneralJournalAccountEntry table

  - LedgerTrialBalanceTmp table


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the LedgerTrialBalanceDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


