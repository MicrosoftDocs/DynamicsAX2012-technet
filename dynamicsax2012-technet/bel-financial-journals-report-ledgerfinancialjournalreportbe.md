---
title: (BEL) Financial journals report (LedgerFinancialJournalReportBE)
TOCTitle: (BEL) Financial journals report (LedgerFinancialJournalReportBE)
ms:assetid: be05a8e9-de7e-41e2-a339-79d76034a1e3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh527156(v=AX.60)
ms:contentKeyID: 37823207
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- journal
- SSRS_Reports.Reports.LedgerFinancialJournalReportBE
- BEL
- Financial journals
---

# (BEL) Financial journals report (LedgerFinancialJournalReportBE) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Financial journals** report displays and prints a summary of financial transactions, such as customer payments and vendor payments, that are posted to the general ledger account. This report summarizes the following:

1.  The payment transactions per voucher and general ledger account.

2.  The overall debits and credits per general ledger account.

3.  The tax details per tax code and voucher number, including the tax base amount and tax amount distribution against goods, services, and investments.

4.  A list of the tax postings sorted by their corresponding tax reporting codes.

This report is typically used by chief executive officers, chief financial officers, compliance managers, accounting managers, accounting supervisors, and financial controllers to review the status of the general ledger process.


> [!NOTE]
> <P>(BEL) This report is available only to legal entities whose primary address is in Belgium.</P>



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
<td><p><strong>Journal</strong></p></td>
<td><p>Select the name of the financial journal that is used to post transactions to the general ledger account.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong></p></td>
<td><p>Select or enter the starting date of the reporting period.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Select or enter the ending date of the reporting period.</p></td>
</tr>
<tr class="even">
<td><p><strong>Final print</strong></p></td>
<td><p>Select this check box to print the final version of the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Compress</strong></p></td>
<td><p>Select this check box to compress the details of the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Amount</strong></p></td>
<td><p>The transaction amount in the accounting currency.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Main account</strong></p></td>
<td><p>The main account number used for the transactions.</p></td>
</tr>
<tr class="even">
<td><p><strong>Date</strong></p></td>
<td><p>The transaction date.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Voucher</strong></p></td>
<td><p>The voucher number in the ledger.</p></td>
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
<td><p>LedgerFinancialJournalReportBE</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerFinancialJournalReportBE</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerFinancialJournalReportBE</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Journals</strong> &gt; <strong>Financial journals</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - LegFinJourRepTmpLegTransBE table

  - TmpAccountTotalsBE table

  - TmpTaxJournalReport\_BE table

  - TmpTaxPurchLedger table

  - TmpTaxSalesLedger table

  - TmpTaxTransTotalsBE table


> [!NOTE]
> <P>To find out where the data in the temp tables comes from, view the cross-references for the LedgerFinancialJournalReportDPBE.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(BEL) Generate journal, sales tax, and purchase sales tax transaction reports](bel-generate-journal-sales-tax-and-purchase-sales-tax-transaction-reports.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

