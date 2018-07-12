---
title: (FRA) Transaction list by account report (LedgerTransAccountVoucher_FR)
TOCTitle: (FRA) Transaction list by account report (LedgerTransAccountVoucher_FR)
ms:assetid: 5295c02b-a872-4b79-96d0-405bd1dac30e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh335147(v=AX.60)
ms:contentKeyID: 36687358
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.LedgerTransAccountVoucher_FR
- (FRA)
- Transaction list by account
---

# (FRA) Transaction list by account report (LedgerTransAccountVoucher\_FR) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Transaction list by account** report displays the transaction list for a specified date interval and a ledger account interval. The report includes the following information:

  - On the first page, a summary of the parameters that are used to generate the report. For example, the starting and ending dates, the ledger account range, the posting layer, and a summary of the selected editing options.

  - The following, in the order of the accounting: The recording date, number of the relevant document, wording of the relevant document, description, corresponding debit or credit amounts, and the resulting balance for each account.

  - The totals for each page, and the grand total.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for cumulative update 7 or later for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3.</P>



This report is used to review the statuses of general ledger processes. This report is used by chief executive officers, chief financial officers, compliance managers, accounting managers, accounting supervisors, and financial controllers.


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
<td><p>Select the starting date of the date range.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Select the ending date of the date range.</p></td>
</tr>
<tr class="odd">
<td><p><strong>From</strong></p></td>
<td><p>Select the starting account for the ledger account range.</p></td>
</tr>
<tr class="even">
<td><p><strong>To</strong></p></td>
<td><p>Select the ending account for the ledger account range.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Posting layer</strong></p></td>
<td><p>Select a posting layer that has transactions to be included in the report.</p>
<div>

> [!NOTE]
> <P>This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Use total by period</strong></p></td>
<td><p>Select this check box to print totals by period (for example, by month) in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Include settled</strong></p></td>
<td><p>Select this check box to include transactions that have been settled in the <strong>Ledger settlements</strong> form in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Total by voucher</strong></p></td>
<td><p>Select this check box to print totals by voucher number on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Include Total main accounts</strong></p></td>
<td><p>Select this check box to include ledger accounts that have an account type of <strong>Total</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Include opening transaction amounts in detail</strong></p></td>
<td><p>Select this check box to include the details of the opening transaction amounts in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Include closing transactions</strong></p></td>
<td><p>Select this check box to include closing transactions in the report.</p></td>
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
<td><p>LedgerTransAccountVoucher_Fr</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerTransAccountVoucher_Fr</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerReport_TransAccountVoucher_Fr</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>France</strong> &gt; <strong>Transaction list by account</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - LedgerTransAccountVoucherTmp\_FR Table


> [!NOTE]
> <P>To find out where the data in the temp table comes from, view the cross-references for the LedgerTransAccountVoucherDP_FR.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

