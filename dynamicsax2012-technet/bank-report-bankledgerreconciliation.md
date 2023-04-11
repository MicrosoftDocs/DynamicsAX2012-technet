---
title: Bank report (BankLedgerReconciliation)
TOCTitle: Bank report (BankLedgerReconciliation)
ms:assetid: 37e017a5-52f0-42a0-aca8-2d31cbb47e35
ms:mtpsurl: https://technet.microsoft.com/library/Aa553503(v=AX.60)
ms:contentKeyID: 39509595
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.BankLedgerReconciliation
---

# Bank report (BankLedgerReconciliation) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view the reconciliation differences between the balances of bank accounts and the balances of main accounts.

The sum of all bank transactions is compared with the sum of all the general ledger transactions that are posted to the related bank summary accounts.

You can specify intervals for dates, vouchers, and main accounts.

If the **Main account** fields are empty, only the summary accounts that are defined in the **Bank accounts** form are shown on the report.

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
<td><p>The start of the date interval for the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>From</strong> <strong>Voucher</strong></p></td>
<td><p>The start of the voucher interval for the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>From</strong> <strong>Main account</strong></p></td>
<td><p>The start of the main account interval for the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>To</strong> <strong>Date</strong></p></td>
<td><p>The end of the date interval for the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To</strong> <strong>Voucher</strong></p></td>
<td><p>The end of the voucher interval for the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>To</strong> <strong>Main account</strong></p></td>
<td><p>The end of the main account interval for the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Include details</strong></p></td>
<td><p>Select this check box to show the transaction date, voucher, journal number, bank account, bank account name, bank balance, general ledger balance, and balance difference.</p></td>
</tr>
<tr class="even">
<td><p><strong>Differences only</strong></p></td>
<td><p>Select this check box to show only the lines that had reconciliation differences. Clear this check box to show all lines. This includes the lines that balance.</p></td>
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
<td><p>BankLedgerReconciliation</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\BankLedgerReconcilliation</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BankLedgerReconciliation</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Reconciliation</strong> &gt; <strong>Bank</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - BankLedgerReconciliationTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the BankLedgerReconciliationDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


