---
title: Customer currency conversion reconciliation report (CustLedgerReconciliation)
TOCTitle: Customer currency conversion reconciliation report (CustLedgerReconciliation)
ms:assetid: f24fbb18-fe41-45bb-816a-3eb1fb9e5270
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa620739(v=AX.60)
ms:contentKeyID: 36956720
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustLedgerReconciliation
---

# Customer currency conversion reconciliation report (CustLedgerReconciliation) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to help you reconcile the balances of customer and ledger accounts.

The sum of all customer transactions is compared with the sum of all the ledger transactions that are posted to the related customer summary accounts.

You can specify intervals for dates, vouchers, and customer accounts, according to the customer posting profile.


> [!NOTE]
> <P>If you clear the <STRONG>Include details</STRONG> check box and select the <STRONG>Differences only</STRONG> check box, the report displays lines that have balance differences. These lines include the transaction date, voucher number, customer account, ledger balance, and balance difference.</P>



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
<td><p>(<strong>From</strong>)</p>
<p><strong>Date</strong></p></td>
<td><p>Enter the start of the date interval of the report.</p></td>
</tr>
<tr class="even">
<td><p>(<strong>From</strong>)</p>
<p><strong>Voucher</strong></p></td>
<td><p>Enter the start of the voucher interval to run the report for.</p></td>
</tr>
<tr class="odd">
<td><p>(<strong>From</strong>)</p>
<p><strong>Posting profile</strong></p></td>
<td><p>Enter the start of the customer posting profile interval to run the report for.</p>
<div class="alert">

> [!NOTE]
> <P>Information on the report uses the information that is found in the summary account for the posting profile that is used for the customer. It does not use the summary account from the general journal that is created for the document.</P>


</div></td>
</tr>
<tr class="even">
<td><p>(<strong>To</strong>)</p>
<p><strong>Date</strong></p></td>
<td><p>Enter the end of the date interval of the report.</p></td>
</tr>
<tr class="odd">
<td><p>(<strong>To</strong>)</p>
<p><strong>Voucher</strong></p></td>
<td><p>Enter the end of the voucher interval to run the report for.</p></td>
</tr>
<tr class="even">
<td><p>(<strong>To</strong>)</p>
<p><strong>Posting profile</strong></p></td>
<td><p>Enter the end of the customer posting profile interval to run the report for.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Include details</strong></p></td>
<td><p>Select this check box to show the lines, sorted by date.</p></td>
</tr>
<tr class="even">
<td><p><strong>Differences only</strong></p></td>
<td><p>Select this check box to show only the lines that have differences, and any lines for which the vendor account and ledger account are both 0 (zero). Clear this check box to show all lines, even those that balance.</p></td>
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
<td><p>CustLedgerReconciliation</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustLedgerReconciliation</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustLedgerReconciliation</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Reconciliation</strong> &gt; <strong>Customer</strong> &gt; <strong>Customer</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustLedgerReconciliationTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the CustLedgerReconciliationDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Close the general ledger at month end](close-the-general-ledger-at-month-end.md)

  


