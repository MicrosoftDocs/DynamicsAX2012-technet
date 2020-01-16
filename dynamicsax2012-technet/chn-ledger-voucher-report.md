---
title: (CHN) Ledger voucher (report)
TOCTitle: (CHN) Ledger voucher (report)
ms:assetid: 8bd64632-8f6c-4f86-9f50-9058b19171b7
ms:mtpsurl: https://technet.microsoft.com/library/JJ874411(v=AX.60)
ms:contentKeyID: 50619727
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CHN) Ledger voucher (report) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Generate a report that displays all of the vouchers included in the selected journal.

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
<td><p><strong>Voucher type</strong></p></td>
<td><p>Select the voucher type to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Journal number</strong></p></td>
<td><p>Select the number of the journal for the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Chinese voucher</strong></p></td>
<td><p>Enter a Chinese voucher number for the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Transactions</strong></p></td>
<td><p>Select the transaction type to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Pre-printed paper</strong></p></td>
<td><p>Select this option if you are using pre-printed paper to print the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Print layout code</strong></p></td>
<td><p>Select the print layout code of the voucher type.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Blank paper</strong></p></td>
<td><p>Select this option if you are using blank paper to print the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Print layout currency</strong></p></td>
<td><p>Select the currency layout for the printed report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Maximum lines</strong></p></td>
<td><p>Select the maximum number of lines that a printed report page can contain.</p></td>
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
<td><p>LedgerJournalTable</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>Forms\LedgerJournalTable</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerJournalTable3</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Journals</strong> &gt; <strong>General journal</strong>. Select a journal, and click <strong>Lines</strong>. In the <strong>Journal voucher</strong> form, click <strong>Print</strong> &gt; <strong>Voucher</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - LedgerJournalTable

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


