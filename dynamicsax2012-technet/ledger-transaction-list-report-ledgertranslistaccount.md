---
title: Ledger transaction list report (LedgerTransListAccount)
TOCTitle: Ledger transaction list report (LedgerTransListAccount)
ms:assetid: 1bf8d065-bbee-4765-8e80-912171ced1c6
ms:mtpsurl: https://technet.microsoft.com/library/Aa572864(v=AX.60)
ms:contentKeyID: 36057111
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.LedgerTransListAccount
---

# Ledger transaction list report (LedgerTransListAccount) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Ledger transaction list** report displays a list of transactions for selected ledger accounts. You can select to include sales tax codes for each transaction and include reversed transactions on the report.

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
<td><p><strong>Sales tax specification</strong></p></td>
<td><p>Select this check box to print sales tax codes and posted sales tax for each transaction.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Include reversed</strong></p></td>
<td><p>Select this check box to include reversed transactions on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>General journal entry</strong></p></td>
<td><p>The information displayed in this field group is determined by your selections when you create a query.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Main account ledger dimension</strong></p></td>
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
<td><p>LedgerTransListAccount</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerTransListAccount</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerTransListAccount</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Ledger transaction list</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - GeneralJournalAccountEntry table

  - GeneralJournalEntry table

  - MainAccountLedgerDimensionView table

  - SubledgerVoucherGeneralJournalEntry table

  - TransactionReversalTrans table

  - LedgerTransactionListTmp table


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the LedgerTransListAccountDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


