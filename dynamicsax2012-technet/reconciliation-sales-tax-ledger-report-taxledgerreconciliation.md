---
title: Reconciliation sales tax/ledger report (TaxLedgerReconciliation)
TOCTitle: Reconciliation sales tax/ledger report (TaxLedgerReconciliation)
ms:assetid: f2358031-c7da-4469-9e99-6c7ddd160b18
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa620735(v=AX.60)
ms:contentKeyID: 43894493
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.TaxLedgerReconciliation
---

# Reconciliation sales tax/ledger report (TaxLedgerReconciliation) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Prepare a report that helps you reconcile the balances of sales tax and main accounts.

The sum of all sales tax transactions is compared with the sum of all the ledger transactions that are posted on the related sales tax summary accounts.

You can specify intervals for dates, vouchers, and main accounts.

If you do not select a main account, only the summary accounts that are defined in the **Transaction posting definitions** form are displayed on the report.


> [!NOTE]
> <P>If you clear the <STRONG>Include details</STRONG> check box and select the <STRONG>Differences only</STRONG> check box, the report displays lines with balance differences, including the transaction date, voucher number, tax balance, main account balance, and balance difference.</P>
> <P>If you have converted the accounting currency for the legal entity by using the <STRONG>Ledger accounting currency conversion</STRONG> form, penny differences may occur and are ignored on this report.</P>



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
<td><p><strong>From</strong> <strong>Date</strong></p></td>
<td><p>Enter the beginning of the date interval of the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>From</strong> <strong>Voucher</strong></p></td>
<td><p>Enter the beginning of the voucher interval to run the report for.</p></td>
</tr>
<tr class="odd">
<td><p><strong>From</strong> <strong>Main account</strong></p></td>
<td><p>Enter the beginning of the main account interval to run the report for.</p></td>
</tr>
<tr class="even">
<td><p><strong>To</strong> <strong>Date</strong></p></td>
<td><p>Enter the end of the date interval of the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To</strong> <strong>Voucher</strong></p></td>
<td><p>Enter the end of the voucher interval to run the report for.</p></td>
</tr>
<tr class="even">
<td><p><strong>To</strong> <strong>Main account</strong></p></td>
<td><p>Enter the end of the main account interval to run the report for.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Include details</strong></p></td>
<td><p>Select this check box if the report should show the lines that do not balance when sorted by main account and amount.</p></td>
</tr>
<tr class="even">
<td><p><strong>Differences only</strong></p></td>
<td><p>Select this check box to show the lines with differences only. Clear the check box to show all lines, including those that balance.</p></td>
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
<td><p>\SSRS Reports\Reports\TaxLedgerReconciliation</p></td>
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

  - TaxLedgerReconciliationTmp table


> [!NOTE]
> <P>To find out where the data in the temp tables comes from, view the cross-references for the TaxLedgerReconciliationDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

