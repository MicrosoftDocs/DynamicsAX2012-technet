---
title: (CHN) General ledger reports
TOCTitle: (CHN) General ledger reports
ms:assetid: a570d784-54c5-41a2-b299-a60a7c7942e7
ms:mtpsurl: https://technet.microsoft.com/library/JJ733507(v=AX.60)
ms:contentKeyID: 49685471
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: China (PRC)
---

# (CHN) General ledger reports 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic provides a list of country/region-specific reports for China. These reports are located in the General ledger area of Microsoft Dynamics AX. For more information about how to work with reports, see [Microsoft Dynamics AX reports](microsoft-dynamics-ax-reports.md).

## Daily summary report (China)

Generate and print a report that displays the daily total debit and credit amount for each ledger account. The report also displays the number of vouchers that are processed each day.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>LedgerDailySummaryReport_CN</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ LedgerDailySummaryReport_CN</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerDailySummaryReport_CN</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Reports (China)</strong> &gt; <strong>Daily summary report (China)</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Where the data in this report comes from</p></td>
<td><p>LedgerDailySummaryReportTmp_CN</p></td>
</tr>
</tbody>
</table>


## Cash daily report (China)

Generate and print a report that displays the daily total debit and credit amount for the cash ledger accounts. The report also displays the number of vouchers that are processed each day.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>LedgerCashDailyStatus</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerCashDailyStatus</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerCashDaily</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Reports (China)</strong> &gt; <strong>Cash daily report (China)</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Where the data in this report comes from</p></td>
<td><p>LedgerCashDailyStatusTmp</p></td>
</tr>
</tbody>
</table>


## Cash status report (China)

Generate and print a report that displays the beginning balance, debit and credit amount, and ending balance for cash and bank accounts for a specified period.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>LedgerCashStatus</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerCashStatus</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerCashStatus</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Reports (China)</strong> &gt; <strong>Cash status report (China)</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Where the data in this report comes from</p></td>
<td><p>LedgerCashStatus</p></td>
</tr>
</tbody>
</table>


## Matrix account report (China)

Generate and print a report that displays information about a parent account and the attached subaccounts. The report also identifies the account format as debit or credit.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>LedgerMatrixAccount_CN</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ LedgerMatrixAccount_CN</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerMatrixAccount_CN</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Reports (China)</strong> &gt; <strong>Matrix account report (China)</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Where the data in this report comes from</p></td>
<td><p>LedgerMatrixReportTmp_CN</p></td>
</tr>
</tbody>
</table>


## Matrix dimension report

Define the sublevel dimensions for a selected dimension type. Then generate and print a report that displays the transaction details for the selected sublevel dimensions in a horizontal format.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>LedgerMatrixDimension_CN</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ LedgerMatrixDimension_CN</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerMatrixDimension_CN</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Reports (China)</strong> &gt; <strong>Matrix dimension</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Where the data in this report comes from</p></td>
<td><p>LedgerMatrixReportTmp_CN</p></td>
</tr>
</tbody>
</table>


## Matrix report with dimensions

Generate and print a report that displays the transaction details for a selected range of dimensions for an account matrix during a specified period.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>LedgerMatrixReportWithDim_CN</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ LedgerMatrixReportWithDim_CN</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerMatrixReportWithDim_CN</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Reports (China)</strong> &gt; <strong>Matrix report with dimensions</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Where the data in this report comes from</p></td>
<td><p>LedgerMatrixReportTmp_CN</p></td>
</tr>
</tbody>
</table>


## Account analysis by dimensions report

Generate and print a report that displays the dimension values for the account balances of selected accounts during a specified period.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>LedgerAccountAnalysisByDimension</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ LedgerAccountAnalysisByDimension</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerAccountAnalysisByDimension</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Reports (China)</strong> &gt; <strong>Account analysis by dimensions</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Where the data in this report comes from</p></td>
<td><p>LedgerAccountAnalysisByDimensionTmp</p></td>
</tr>
</tbody>
</table>


## Chart of accounts by dimensions report

Generate and print a report that displays the ledger accounts for a specified dimension value during a specified period.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>LedgerChartofAccountsbyDimensions_CN</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ LedgerChartofAccountsbyDimensions_CN</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerChartofAccountsbyDimensions_CN</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Reports (China)</strong> &gt; <strong>Chart of accounts by dimensions</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Where the data in this report comes from</p></td>
<td><p>LedgerChartofAccountsbyDimensionsTmp_CN</p></td>
</tr>
</tbody>
</table>


## Ledger transactions by dimensions report

Generate and print a report that displays the dimension values for ledger transactions during a specified period.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>LedgerTransactionsbyDimension_CN</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ LedgerTransactionsbyDimension_CN</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerTransactionsbyDimension_CN</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Reports (China)</strong> &gt; <strong>Ledger transactions by dimensions</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Where the data in this report comes from</p></td>
<td><p>LedgerTransactionsbyDimensionTmp_CN</p></td>
</tr>
</tbody>
</table>


## Ledger transactions including dimensions details report

Generate and print a report that displays ledger transactions that are grouped together based on ledger accounts and dimension values for a specified period.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>LedgerDetailedTransactionsByDimension_CN</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerDetailedTransactionsByDimension_CN</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerDetailedTransactionsbyDim_CN</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Reports (China)</strong> &gt; <strong>Ledger transactions including dimension details</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Where the data in this report comes from</p></td>
<td><p>LedgerDetailedTransByDimensionsTmp_CN</p></td>
</tr>
</tbody>
</table>


## Account balance sheet by dimensions report

Generate and print a report that displays the ledger account balances and dimension values for selected accounts during a specified period.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>LedgerAccountBalSheetByDim</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerAccountBalSheetByDim</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerAccountBalSheetByDim</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Reports (China)</strong> &gt; <strong>Account balance sheet by dimensions</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Where the data in this report comes from</p></td>
<td><p>LedgerAccountBalSheetByDimTmp</p></td>
</tr>
</tbody>
</table>


## Chart of accounts report

Generate and print a report that displays journal and transaction information and provides an overview of the account structures.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>LedgerAccountSched</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ LedgerAccountSched</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerAccountSched</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Base data</strong> &gt; <strong>Chart of accounts</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Where the data in this report comes from</p></td>
<td><p>LedgerAccountSchedTmp</p></td>
</tr>
</tbody>
</table>


## Print journal report

Generate and print a report that displays all journalized transactions, sorted by journal number.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>LedgerJournal</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ LedgerJournal</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerJournal</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Journals</strong> &gt; <strong>Print journal</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Where the data in this report comes from</p></td>
<td><p>LedgerJournal</p></td>
</tr>
</tbody>
</table>


## Bank reconciliation statement report

Generate and print a report that displays the summary information from the last reconciliation and the current reconciliation in the **Bank reconciliation** form. The report also displays detailed transactions that are grouped by transaction types.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>BankReconciliationHeader</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>SSRS Reports\Reports\BankReconciliationHeader</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BankReconciliationHeaderReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Reconciliation</strong> &gt; <strong>Bank</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Where the data in this report comes from</p></td>
<td><p>BankReconciliationHeaderTmp</p></td>
</tr>
</tbody>
</table>


## Balance list report

Generate and print a report that analyzes account balances for a specific date interval. You can also specify a range of main accounts.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>LedgerTotalAndBalanceList</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ LedgerTotalAndBalanceList</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerTotalAndBalanceList</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Balance list</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Where the data in this report comes from</p></td>
<td><p>LedgerTotalAndBalanceListTmp</p></td>
</tr>
</tbody>
</table>


## Ledger transactions list report

Generate and print a report that displays a list of transactions for selected ledger accounts. You can include sales tax codes for each transaction and reversed transactions on the report.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>LedgerTransListAccount</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
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
<tr class="odd">
<td><p>Where the data in this report comes from</p></td>
<td><p>LedgerTransactionListTmp</p></td>
</tr>
</tbody>
</table>


## Chinese voucher continuity check report

Generate and print a report to verify that the Chinese voucher numbers in a fiscal period are sequential and do not contain gaps.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>LedgerVoucherRenumberLog_CN</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>Forms\LedgerVoucherRenumberLog_CN</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerVoucherRenumberLog_CN</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Transactions</strong> &gt; <strong>Chinese voucher continuity check report</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Where the data in this report comes from</p></td>
<td><p>GeneralJournalEntry</p></td>
</tr>
</tbody>
</table>


## Trial balance report

Generate and print a report to analyze the following ledger trial balance information for a specified period:

  - Opening and closing balance

  - Debits and credits

  - Profit and loss

  - Revenue

  - Cost

  - Assets

  - Liability

  - Balance

  - Total accounts
    
    The total account is the sum total of all of the accounts that are set up to be included in the total.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>LedgerTrialBalance_CN</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>Forms\LedgerTrialBalance_CN</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerTrialBalance_CN</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Inquiries</strong> &gt; <strong>Trial balance</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Where the data in this report comes from</p></td>
<td><p>TmpGeneralLedger_CN</p></td>
</tr>
</tbody>
</table>


## Chinese voucher print report

Generate and print a report that displays ledger journal transactions that share the same voucher number. The report is displayed in the Chinese special format.

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
<td><p>Name of the report in the AOT</p></td>
<td><p>LedgerVoucher_CN</p></td>
</tr>
<tr class="even">
<td><p>Location of the report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerVoucher_CN</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerVoucher_CN</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Periodic</strong> &gt; <strong>China</strong> &gt; <strong>Chinese voucher print</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Where the data in this report comes from</p></td>
<td><p>LedgerVoucherTmp_CN</p></td>
</tr>
</tbody>
</table>

  


