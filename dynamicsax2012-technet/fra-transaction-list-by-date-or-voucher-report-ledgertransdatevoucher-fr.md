---
title: (FRA) Transaction list by date or voucher report (LedgerTransDateVoucher_FR)
TOCTitle: (FRA) Transaction list by date or voucher report (LedgerTransDateVoucher_FR)
ms:assetid: 5c249880-03c2-422f-a5c7-101ffe72c363
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh335152(v=AX.60)
ms:contentKeyID: 36687363
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.LedgerTransDateVoucher_FR
- (FRA)
- Transaction list by date or voucher report
- Voucher report
---

# (FRA) Transaction list by date or voucher report (LedgerTransDateVoucher\_FR) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Transaction list by date or voucher** report displays a list of vouchers, sorted by voucher type or date. The journal entries are recorded chronologically. Each entry shows debit and credit amounts, the account number, the date, and a short description. The report includes the following information:

  - On the first page, a summary of the parameters that are used to generate the report. For example, the starting and ending dates, and a summary of the selected editing options.

  - The entries that include the date, the account, and whether the entry is a debit or a credit. The entries are classified by period and by document number.

  - The totals for each period, and the grand total.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for cumulative update 7 or later for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3.</P>



This report is used by account managers.


> [!NOTE]
> <P>(FRA) This report is available only to legal entities whose primary address is in France.</P>



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
<td><p><strong>From date</strong></p></td>
<td><p>Select a starting date for the date range.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Select an ending date for the date range.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Voucher filter</strong></p></td>
<td><p>Enter a voucher number. The transactions for only this voucher are included in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Posting layer</strong></p></td>
<td><p>Select a posting layer that has transactions to be included in the report.</p>
<div class="alert">

> [!NOTE]
> <P>This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Sorting</strong></p></td>
<td><p>Select the method to use to sort transactions in the report. You can select <strong>Date</strong> or <strong>Voucher</strong>. You must select <strong>Voucher</strong> to print the totals of the transaction amounts that are sorted by voucher numbers.</p></td>
</tr>
<tr class="even">
<td><p><strong>Total for first characters in voucher</strong></p></td>
<td><p>Enter a number. For example, enter <strong>2</strong> to print a total of the transaction amounts for the first two digits in the specified voucher.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Total by voucher</strong></p></td>
<td><p>Select this check box to print a total of the transaction amounts for each voucher.</p></td>
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
<td><p>LedgerTransDateVoucher_FR</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerTransDateVoucher_FR</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerReport_TransDateVoucher_Fr</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>France</strong> &gt; <strong>Transaction list by date or voucher</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DimensionAttributeValueCombination table

  - GeneralJournalAccountEntry table

  - GeneralJournalEntry table

  - MainAccount table

  - SubledgerVoucherGeneralJournalEntry table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

