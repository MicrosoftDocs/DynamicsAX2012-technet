---
title: Mapping Microsoft Dynamics AX 2009 Reports to the Microsoft Dynamics AX 2012 Version
TOCTitle: Mapping Microsoft Dynamics AX 2009 Reports to the Microsoft Dynamics AX 2012 Version
ms:assetid: 23bc97b8-2236-48ca-8eff-9b6f7e1a023d
ms:mtpsurl: https://technet.microsoft.com/library/Gg731909(v=AX.60)
ms:contentKeyID: 35132831
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Mapping Microsoft Dynamics AX 2009 Reports to the Microsoft Dynamics AX 2012 Version 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides a mapping of the reports from Microsoft Dynamics AX 2009 to a similar representation of data in Microsoft Dynamics AX 2012. The following implementations were used to show similar data:

  - [Reports were converted](development-tasks-for-reporting.md) to run on SQL Server Reporting Services

  - [List pages](https://technet.microsoft.com/library/cc616937\(v=ax.60\))

Some reports will not be provided in this release. For more information, see [Deprecated Microsoft Dynamics AX 2009 Reports in Microsoft Dynamics AX 2012](deprecated-microsoft-dynamics-ax-2009-reports-in-microsoft-dynamics-ax-2012.md). For information about the reports that will be provided, see [Report catalog for Microsoft Dynamics AX](report-catalog-for-microsoft-dynamics-ax.md). For a Microsoft Excel version of the report list, see [Microsoft Dynamics AX 2012 and 2009 Report List](https://go.microsoft.com/fwlink/?linkid=232938).

## Report Mapping to Reporting Services Reports

The following table provides the mapping of a Microsoft Dynamics AX 2009 report to the report in Microsoft Dynamics AX 2012.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Microsoft Dynamics AX 2009 Report Name</p></th>
<th><p>Microsoft Dynamics AX 2012 Report Name</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>SysCompanySize</p></td>
<td><p>SysCompanySize</p></td>
</tr>
<tr class="even">
<td><p>SysDataAreaPrintCollections</p></td>
<td><p>SysDataAreaPrintCollections</p></td>
</tr>
<tr class="odd">
<td><p>SysDatabaseLog</p></td>
<td><p>SysDatabaseLog</p></td>
</tr>
<tr class="even">
<td><p>SysSqlSyncInfo</p></td>
<td><p>SysSqlSyncInfo</p></td>
</tr>
<tr class="odd">
<td><p>SysTableDefinition</p></td>
<td><p>SysTableDefinition</p></td>
</tr>
<tr class="even">
<td><p>SysUsersOnline</p></td>
<td><p>SysUsersOnline</p></td>
</tr>
<tr class="odd">
<td><p>BankPaymAdviceVend</p></td>
<td><p>BankPaymAdviceVend</p></td>
</tr>
<tr class="even">
<td><p>PurchEUVatInvoice</p></td>
<td><p>PurchEUVATInvoice</p></td>
</tr>
<tr class="odd">
<td><p>PurchInvoice</p></td>
<td><p>PurchInvoice</p></td>
</tr>
<tr class="even">
<td><p>VendAccountStatementInt</p></td>
<td><p>VendAccountStatementInt</p></td>
</tr>
<tr class="odd">
<td><p>VendCheckSettlement</p></td>
<td><p>VendCheckSettlement</p></td>
</tr>
<tr class="even">
<td><p>VendExchRateAdjSimulation</p></td>
<td><p>VendExchRateAdjSimulation</p></td>
</tr>
<tr class="odd">
<td><p>VendExchRateAdjustment</p></td>
<td><p>VendExchRateAdjustment</p></td>
</tr>
<tr class="even">
<td><p>VendInvoice</p></td>
<td><p>VendInvoice</p></td>
</tr>
<tr class="odd">
<td><p>VendInvoicePoolNotposted</p></td>
<td><p>VendInvoicePoolNotposted</p></td>
</tr>
<tr class="even">
<td><p>VendInvoiceSpec</p></td>
<td><p>VendInvoiceSpec</p></td>
</tr>
<tr class="odd">
<td><p>VendInvoiceVolume</p></td>
<td><p>VendInvoiceVolume</p></td>
</tr>
<tr class="even">
<td><p>VendLedgerTrans</p></td>
<td><p>VendLedgerTrans</p></td>
</tr>
<tr class="odd">
<td><p>VendOutAttendingNote_PNRemittance</p></td>
<td><p>VendOutAttendingNote_PNRemittance</p></td>
</tr>
<tr class="even">
<td><p>VendPromissoryNoteReport</p></td>
<td><p>VendPromissoryNoteReport</p></td>
</tr>
<tr class="odd">
<td><p>VendProvisionalBalance</p></td>
<td><p>VendProvisionalBalance</p></td>
</tr>
<tr class="even">
<td><p>VendReportApproveCollection</p></td>
<td><p>VendReportApproveCollection</p></td>
</tr>
<tr class="odd">
<td><p>VendAgingreport</p></td>
<td><p>VendAgingreport (detail or summary version)</p></td>
</tr>
<tr class="even">
<td><p>VendBalanceList</p></td>
<td><p>VendBalanceList</p></td>
</tr>
<tr class="odd">
<td><p>VendDueReportDetail_NA</p></td>
<td><p>VendDueReportDetail_NA</p></td>
</tr>
<tr class="even">
<td><p>VendLedgerReconciliation</p></td>
<td><p>VendLedgerReconciliation</p></td>
</tr>
<tr class="odd">
<td><p>VendPurchOpenOrders_NA</p></td>
<td><p>VendPurchOpenOrders_NA</p></td>
</tr>
<tr class="even">
<td><p>VendTransList</p></td>
<td><p>VendTransListReport</p></td>
</tr>
<tr class="odd">
<td><p>VendInvoiceJour</p></td>
<td><p>VendInvoiceJour</p></td>
</tr>
<tr class="even">
<td><p>BankPaymAdviceCust</p></td>
<td><p>BankPaymAdviceCust</p></td>
</tr>
<tr class="odd">
<td><p>CustAccountStatementInt</p></td>
<td><p>CustAccountStatementInt</p></td>
</tr>
<tr class="even">
<td><p>CustAuditor</p></td>
<td><p>CustAuditor</p></td>
</tr>
<tr class="odd">
<td><p>CustBillOfExchangeReport</p></td>
<td><p>CustBillOfExchangeReport</p></td>
</tr>
<tr class="even">
<td><p>CustCheckSettlement</p></td>
<td><p>CustCheckSettlement</p></td>
</tr>
<tr class="odd">
<td><p>CustCOD</p></td>
<td><p>CustCOD</p></td>
</tr>
<tr class="even">
<td><p>CustCollectionJour</p></td>
<td><p>CustCollectionJour</p></td>
</tr>
<tr class="odd">
<td><p>CustCollectionLetterOverview</p></td>
<td><p>CustCollectionLetterOverview</p></td>
</tr>
<tr class="even">
<td><p>CustExchRateAdjSimulation</p></td>
<td><p>CustExchRateAdjSimulation</p></td>
</tr>
<tr class="odd">
<td><p>CustExchRateAdjustment</p></td>
<td><p>CustExchRateAdjustment</p></td>
</tr>
<tr class="even">
<td><p>CustInvoice</p></td>
<td><p>CustInvoice</p></td>
</tr>
<tr class="odd">
<td><p>CustInvoiceSpec</p></td>
<td><p>CustInvoiceSpec</p></td>
</tr>
<tr class="even">
<td><p>CustInvoiceVolume</p></td>
<td><p>CustInvoiceVolume</p></td>
</tr>
<tr class="odd">
<td><p>CustLedgerTrans</p></td>
<td><p>CustLedgerTrans</p></td>
</tr>
<tr class="even">
<td><p>CustOutAttendingNote_BillRemittance</p></td>
<td><p>CustOutAttendingNote_BillRemittance</p></td>
</tr>
<tr class="odd">
<td><p>CustPaymManFeeHist</p></td>
<td><p>CustPaymManFeeHist</p></td>
</tr>
<tr class="even">
<td><p>CustPaymManOutputReport</p></td>
<td><p>CustPaymManOutputReport</p></td>
</tr>
<tr class="odd">
<td><p>CustPaymManStepPosting</p></td>
<td><p>CustPaymManStepPosting</p></td>
</tr>
<tr class="even">
<td><p>CustPaymManUnpaid</p></td>
<td><p>CustPaymManUnpaid</p></td>
</tr>
<tr class="odd">
<td><p>CustProvisionalBalance</p></td>
<td><p>CustProvisionalBalance</p></td>
</tr>
<tr class="even">
<td><p>CustReimbursement</p></td>
<td><p>CustReimbursement</p></td>
</tr>
<tr class="odd">
<td><p>CustTransOpenPerDate</p></td>
<td><p>CustTransOpenPerDate</p></td>
</tr>
<tr class="even">
<td><p>CustTransTaxTrans</p></td>
<td><p>CustTransTaxTrans</p></td>
</tr>
<tr class="odd">
<td><p>CustVendAgingStaticticsAutoReport</p></td>
<td><p>CustVendAgingStaticticsAutoReport</p></td>
</tr>
<tr class="even">
<td><p>CustVendPaymJournal</p></td>
<td><p>CustVendPaymJournal</p></td>
</tr>
<tr class="odd">
<td><p>CustVendPaymProposal</p></td>
<td><p>CustVendPaymProposal</p></td>
</tr>
<tr class="even">
<td><p>FreeTextInvoice</p></td>
<td><p>FreeTextInvoice</p></td>
</tr>
<tr class="odd">
<td><p>SalesInvoice</p></td>
<td><p>SalesInvoice</p></td>
</tr>
<tr class="even">
<td><p>CustAccountStatementExt</p></td>
<td><p>CustAccountStatementExt</p></td>
</tr>
<tr class="odd">
<td><p>CustAgingReport</p></td>
<td><p>CustAgingReport</p></td>
</tr>
<tr class="even">
<td><p>CustBalanceList</p></td>
<td><p>CustBalanceList</p></td>
</tr>
<tr class="odd">
<td><p>CustLedgerReconciliation</p></td>
<td><p>CustLedgerReconciliation</p></td>
</tr>
<tr class="even">
<td><p>CustSalesOpenOrders_NA</p></td>
<td><p>CustSalesOpenOrders_NA</p></td>
</tr>
<tr class="odd">
<td><p>CustTransList</p></td>
<td><p>CustTransList</p></td>
</tr>
<tr class="even">
<td><p>CustInvoiceJour</p></td>
<td><p>CustInvoiceJour</p></td>
</tr>
<tr class="odd">
<td><p>CustDueReportDetail</p></td>
<td><p>CustDueReportDetail</p></td>
</tr>
<tr class="even">
<td><p>BankAccountStatement</p></td>
<td><p>BankAccountStatement</p></td>
</tr>
<tr class="odd">
<td><p>BankBillOfExchange</p></td>
<td><p>BankBillOfExchange</p></td>
</tr>
<tr class="even">
<td><p>BankDepositByCustomer</p></td>
<td><p>BankDepositbyCustomer</p></td>
</tr>
<tr class="odd">
<td><p>BankDepositByDate</p></td>
<td><p>BankDepositByDate</p></td>
</tr>
<tr class="even">
<td><p>BankDepositSlip</p></td>
<td><p>BankDepositSlip</p></td>
</tr>
<tr class="odd">
<td><p>BankPaymAdviceCheque</p></td>
<td><p>BankPaymAdviceCheque</p></td>
</tr>
<tr class="even">
<td><p>BankPaymentByDate</p></td>
<td><p>BankPaymentByDate</p></td>
</tr>
<tr class="odd">
<td><p>BankPaymentByVendor</p></td>
<td><p>BankPaymentbyVendor</p></td>
</tr>
<tr class="even">
<td><p>BankReconciliation</p></td>
<td><p>BankReconciliation</p></td>
</tr>
<tr class="odd">
<td><p>BankReconciliationSummary</p></td>
<td><p>BankReconciliationSummary</p></td>
</tr>
<tr class="even">
<td><p>BankAccountReconciliation</p></td>
<td><p>BankAccountReconciliation</p></td>
</tr>
<tr class="odd">
<td><p>BankLedgerReconciliation</p></td>
<td><p>BankLedgerReconciliation</p></td>
</tr>
<tr class="even">
<td><p>AssetAcquisition</p></td>
<td><p>AssetAcquisition</p></td>
</tr>
<tr class="odd">
<td><p>AssetAddition</p></td>
<td><p>AssetAddition</p></td>
</tr>
<tr class="even">
<td><p>AssetBalanceReportColumns</p></td>
<td><p>AssetBalanceReportColumns</p></td>
</tr>
<tr class="odd">
<td><p>AssetBalancesPeriod</p></td>
<td><p>AssetBalancesPeriod</p></td>
</tr>
<tr class="even">
<td><p>AssetBarcode</p></td>
<td><p>AssetBarcode</p></td>
</tr>
<tr class="odd">
<td><p>AssetBasis</p></td>
<td><p>AssetBasis</p></td>
</tr>
<tr class="even">
<td><p>AssetBookCompare</p></td>
<td><p>AssetBookCompare</p></td>
</tr>
<tr class="odd">
<td><p>AssetConsumptionProposal</p></td>
<td><p>AssetConsumptionProposal</p></td>
</tr>
<tr class="even">
<td><p>AssetDepBookMassUpdate</p></td>
<td><p>AssetDepBookMassUpdate</p></td>
</tr>
<tr class="odd">
<td><p>AssetDisposal</p></td>
<td><p>AssetDisposal</p></td>
</tr>
<tr class="even">
<td><p>AssetFutureValue</p></td>
<td><p>AssetFutureValue</p></td>
</tr>
<tr class="odd">
<td><p>AssetInsurance</p></td>
<td><p>AssetInsurance</p></td>
</tr>
<tr class="even">
<td><p>AssetLending</p></td>
<td><p>AssetLending</p></td>
</tr>
<tr class="odd">
<td><p>AssetLendingHistory</p></td>
<td><p>AssetLendingHistory</p></td>
</tr>
<tr class="even">
<td><p>AssetListing</p></td>
<td><p>AssetListing</p></td>
</tr>
<tr class="odd">
<td><p>AssetMidQuarter</p></td>
<td><p>AssetMidQuarter</p></td>
</tr>
<tr class="even">
<td><p>AssetReserveTransactions</p></td>
<td><p>AssetReserveTransactions</p></td>
</tr>
<tr class="odd">
<td><p>AssetsInAssetStatement</p></td>
<td><p>AssetsInAssetStatement</p></td>
</tr>
<tr class="even">
<td><p>AssetStatement</p></td>
<td><p>AssetStatement</p></td>
</tr>
<tr class="odd">
<td><p>AssetStatementRowSetup</p></td>
<td><p>AssetStatementRowSetup</p></td>
</tr>
<tr class="even">
<td><p>AssetTaxStatistic</p></td>
<td><p>AssetTaxStatistic</p></td>
</tr>
<tr class="odd">
<td><p>AssetTransactionListing</p></td>
<td><p>AssetTransactionListing</p></td>
</tr>
<tr class="even">
<td><p>AssetBalances</p></td>
<td><p>AssetBalances</p></td>
</tr>
<tr class="odd">
<td><p>IntrastatFormLetter</p></td>
<td><p>IntrastatFormLetter</p></td>
</tr>
<tr class="even">
<td><p>IntrastatList</p></td>
<td><p>IntrastatList</p></td>
</tr>
<tr class="odd">
<td><p>LedgerAccountSched</p></td>
<td><p>LedgerAccountSched</p></td>
</tr>
<tr class="even">
<td><p>LedgerAllocationRules</p></td>
<td><p>LedgerAllocationRules</p></td>
</tr>
<tr class="odd">
<td><p>LedgerBalanceControl</p></td>
<td><p>LedgerBalanceControl</p></td>
</tr>
<tr class="even">
<td><p>LedgerCheckTrans</p></td>
<td><p>LedgerCheckTrans</p></td>
</tr>
<tr class="odd">
<td><p>LedgerCheckVoucher</p></td>
<td><p>LedgerCheckVoucher</p></td>
</tr>
<tr class="even">
<td><p>LedgerClosing</p></td>
<td><p>LedgerClosing</p></td>
</tr>
<tr class="odd">
<td><p>LedgerEliminationRules</p></td>
<td><p>LedgerEliminationRules</p></td>
</tr>
<tr class="even">
<td><p>LedgerJournalAccountMovement</p></td>
<td><p>LedgerJournalAccountMovement</p></td>
</tr>
<tr class="odd">
<td><p>LedgerJournalCashReport</p></td>
<td><p>LedgerJournalCashReport</p></td>
</tr>
<tr class="even">
<td><p>LedgerJournalizeReport</p></td>
<td><p>LedgerJournalizeReport</p></td>
</tr>
<tr class="odd">
<td><p>LedgerJournalizeReport2</p></td>
<td><p>LedgerJournalizeReportTransLog</p></td>
</tr>
<tr class="even">
<td><p>LedgerJournalPostControlByJournalType</p></td>
<td><p>LedgerJournalPostControlByJournalType</p></td>
</tr>
<tr class="odd">
<td><p>LedgerJournalPostControlByUser</p></td>
<td><p>LedgerJournalPostControlByUser</p></td>
</tr>
<tr class="even">
<td><p>LedgerRowDefinitionPrint</p></td>
<td><p>LedgerRowDefinitionPrint</p></td>
</tr>
<tr class="odd">
<td><p>LedgerRowStructureWhereUsed</p></td>
<td><p>LedgerRowStructureWhereUsed</p></td>
</tr>
<tr class="even">
<td><p>LedgerTotalAndBalanceList</p></td>
<td><p>LedgerTotalAndBalanceList</p></td>
</tr>
<tr class="odd">
<td><p>LedgerTransferOpening</p></td>
<td><p>LedgerTransferOpening</p></td>
</tr>
<tr class="even">
<td><p>LedgerTransListAccount</p></td>
<td><p>LedgerTransListAccount</p></td>
</tr>
<tr class="odd">
<td><p>LedgerTransListDate</p></td>
<td><p>LedgerTransListDate</p></td>
</tr>
<tr class="even">
<td><p>LedgerTransOpen</p></td>
<td><p>LedgerTransOpen</p></td>
</tr>
<tr class="odd">
<td><p>LedgerTransPerJournal</p></td>
<td><p>LedgerTransPerJournal</p></td>
</tr>
<tr class="even">
<td><p>LedgerTransStatement</p></td>
<td><p>LedgerTransStatement</p></td>
</tr>
<tr class="odd">
<td><p>TaxAmountByCustomer</p></td>
<td><p>TaxAmountByCustomer</p></td>
</tr>
<tr class="even">
<td><p>TaxAmountByVendor</p></td>
<td><p>TaxAmountByVendor</p></td>
</tr>
<tr class="odd">
<td><p>TaxCodeReportSetup</p></td>
<td><p>TaxCodeReportSetup</p></td>
</tr>
<tr class="even">
<td><p>TaxDeviation</p></td>
<td><p>TaxDeviation</p></td>
</tr>
<tr class="odd">
<td><p>TaxLedgerReconciliation</p></td>
<td><p>TaxLedgerReconciliation</p></td>
</tr>
<tr class="even">
<td><p>TaxList</p></td>
<td><p>TaxList</p></td>
</tr>
<tr class="odd">
<td><p>TaxPackagingTaxItem</p></td>
<td><p>TaxPackagingTaxItem</p></td>
</tr>
<tr class="even">
<td><p>TaxReportById</p></td>
<td><p>TaxReportById</p></td>
</tr>
<tr class="odd">
<td><p>TaxReportInclAdjustment</p></td>
<td><p>TaxReportInclAdjustment</p></td>
</tr>
<tr class="even">
<td><p>TaxReporting</p></td>
<td><p>TaxReporting</p></td>
</tr>
<tr class="odd">
<td><p>TaxSpecPerLedgerTrans</p></td>
<td><p>TaxSpecPerLedgerTrans</p></td>
</tr>
<tr class="even">
<td><p>TaxTable</p></td>
<td><p>TaxTable</p></td>
</tr>
<tr class="odd">
<td><p>TaxTrans</p></td>
<td><p>TaxTrans</p></td>
</tr>
<tr class="even">
<td><p>TaxTransCode</p></td>
<td><p>TaxTransCode</p></td>
</tr>
<tr class="odd">
<td><p>TaxTransDetail</p></td>
<td><p>TaxTransDetail</p></td>
</tr>
<tr class="even">
<td><p>TaxWithholdTrans</p></td>
<td><p>TaxWithholdTrans</p></td>
</tr>
<tr class="odd">
<td><p>LedgerAccountStatementPerCurrency</p></td>
<td><p>LedgerAccountStatementPerCurrency</p></td>
</tr>
<tr class="even">
<td><p>LedgerOpenTransactions</p></td>
<td><p>LedgerOpenTransactions</p></td>
</tr>
<tr class="odd">
<td><p>LedgerProvisionalBalance</p></td>
<td><p>LedgerTrialBalance</p></td>
</tr>
<tr class="even">
<td><p>LedgerTransBase</p></td>
<td><p>LedgerTransBase</p></td>
</tr>
<tr class="odd">
<td><p>LedgerJournal</p></td>
<td><p>LedgerJournal</p></td>
</tr>
<tr class="even">
<td><p>LedgerTrialBalance</p></td>
<td><p>LedgerTrialBalance</p></td>
</tr>
<tr class="odd">
<td><p>LedgerAuditTrail</p></td>
<td><p>LedgerAuditTrail</p></td>
</tr>
<tr class="even">
<td><p>BankReconciliation</p></td>
<td><p>BankReconciliation</p></td>
</tr>
<tr class="odd">
<td><p>VendAccountStatement_FR</p></td>
<td><p>VendAccountStatement_FR</p></td>
</tr>
<tr class="even">
<td><p>VendAccruedPurchases_NA</p></td>
<td><p>VendAccruedPurchases_NA</p></td>
</tr>
<tr class="odd">
<td><p>VendInvoiceSettled_TransDate_ES</p></td>
<td><p>VendInvoiceSettled_TransDate_ES</p></td>
</tr>
<tr class="even">
<td><p>VendOpenPaymDocu_ES</p></td>
<td><p>VendOpenPaymDocu_ES</p></td>
</tr>
<tr class="odd">
<td><p>VendOutAttendingNote_ATEDIFACT</p></td>
<td><p>VendOutAttendingNote_ATEDIFACT</p></td>
</tr>
<tr class="even">
<td><p>VendOutAttendingNote_DEDTAUS</p></td>
<td><p>VendOutAttendingNoteDE_DTAUS</p></td>
</tr>
<tr class="odd">
<td><p>VendOutAttendingNote_DEDTAZV</p></td>
<td><p>VendOutAttendingNote_DEDTAZV</p></td>
</tr>
<tr class="even">
<td><p>VendOutCoveringLetter_DEDTAUS</p></td>
<td><p>VendOutCoveringLetter_DEDTAUS</p></td>
</tr>
<tr class="odd">
<td><p>VendOutCoveringLetter_DEDTAZV</p></td>
<td><p>VendOutCoveringLetter_DEDTAZV</p></td>
</tr>
<tr class="even">
<td><p>VendOutPaymAdvice_ATEDIFACT</p></td>
<td><p>VendOutPaymAdvice_ATEDIFACT</p></td>
</tr>
<tr class="odd">
<td><p>VendOutPaymAdvice_CHDTA</p></td>
<td><p>VendOutPaymAdvice_CHDTA</p></td>
</tr>
<tr class="even">
<td><p>VendOutPaymAdvice_CHEZAG</p></td>
<td><p>VendOutPaymAdvice_CHEZAG</p></td>
</tr>
<tr class="odd">
<td><p>VendOutPaymControl</p></td>
<td><p>VendOutPaymControl</p></td>
</tr>
<tr class="even">
<td><p>VendOutPaymControl_DEDTAZV</p></td>
<td><p>VendOutPaymControl_DEDTAZV</p></td>
</tr>
<tr class="odd">
<td><p>VendOutPaymControl_ES</p></td>
<td><p>VendOutPaymControl_ES</p></td>
</tr>
<tr class="even">
<td><p>VendOutPaymControl_FI_FOR</p></td>
<td><p>VendOutPaymControl_FI_FOR</p></td>
</tr>
<tr class="odd">
<td><p>VendOutPaymControl_FI_LM</p></td>
<td><p>VendOutPaymControl_FI_LM</p></td>
</tr>
<tr class="even">
<td><p>VendOutPaymControl_FR</p></td>
<td><p>VendOutPaymControl_FR</p></td>
</tr>
<tr class="odd">
<td><p>VendOutPaymControl_IT</p></td>
<td><p>VendOutPaymControl_IT</p></td>
</tr>
<tr class="even">
<td><p>VendOutPaymControl_SE</p></td>
<td><p>VendOutPaymControl_SE</p></td>
</tr>
<tr class="odd">
<td><p>VendOutPaymOrder_CHDTA</p></td>
<td><p>VendOutPaymOrder_CHDTA</p></td>
</tr>
<tr class="even">
<td><p>VendOutPaymOrder_CHEZAG</p></td>
<td><p>VendOutPaymOrder_CHEZAG</p></td>
</tr>
<tr class="odd">
<td><p>VendPaymentJournal_NA</p></td>
<td><p>VendPaymentJournal_NA</p></td>
</tr>
<tr class="even">
<td><p>VendPaymRefReport_BE</p></td>
<td><p>VendPaymRefReport_BE</p></td>
</tr>
<tr class="odd">
<td><p>VendPostPaymJournal_NA</p></td>
<td><p>VendPostPaymJournal_NA</p></td>
</tr>
<tr class="even">
<td><p>VendPromissoryNoteOpenTrans_ES</p></td>
<td><p>VendPromissoryNoteOpenTrans_ES</p></td>
</tr>
<tr class="odd">
<td><p>VendPromissoryNoteOpenTrans_FR</p></td>
<td><p>VendPromissoryNoteOpenTrans_FR</p></td>
</tr>
<tr class="even">
<td><p>VendPurchaseDistribution_NA</p></td>
<td><p>VendPurchaseDistribution_NA</p></td>
</tr>
<tr class="odd">
<td><p>VendPurchOpenLinesByDelvDate_NA</p></td>
<td><p>VendPurchOpenLinesByDelvDate_NA</p></td>
</tr>
<tr class="even">
<td><p>VendPurchOpenLinesByItem_NA</p></td>
<td><p>VendPurchOpenLinesByItem_NA</p></td>
</tr>
<tr class="odd">
<td><p>VendPurchOpenLinesByVend_NA</p></td>
<td><p>VendPurchOpenLines_NA with three designs:i)ByVend ii) ByItem iii) ByDelvDate</p></td>
</tr>
<tr class="even">
<td><p>VendPurchReceivingLog_NA</p></td>
<td><p>VendPurchReceivingLog_NA</p></td>
</tr>
<tr class="odd">
<td><p>VendTransOpen_PaymMode_ES</p></td>
<td><p>VendTransOpen_PaymMode_ES</p></td>
</tr>
<tr class="even">
<td><p>VendOutPaymAdvice_FRAFB</p></td>
<td><p>VendOutPaymAdvice_FRAFB</p></td>
</tr>
<tr class="odd">
<td><p>CustAccountStatement_FR</p></td>
<td><p>CustAccountStatement_FR</p></td>
</tr>
<tr class="even">
<td><p>CustBalanceList_MY</p></td>
<td><p>CustBalanceList_MY</p></td>
</tr>
<tr class="odd">
<td><p>CustBillOfExchangeOpenTrans_ES</p></td>
<td><p>CustBillOfExchangeOpenTrans_ES</p></td>
</tr>
<tr class="even">
<td><p>CustBillOpenTrans_FR</p></td>
<td><p>CustBillOpenTrans_FR</p></td>
</tr>
<tr class="odd">
<td><p>CustDomStatement_BE</p></td>
<td><p>CustDomStatement_BE</p></td>
</tr>
<tr class="even">
<td><p>CustGrossMarginbyAccount_NA</p></td>
<td><p>CustGrossMarginbyAccount_NA</p></td>
</tr>
<tr class="odd">
<td><p>CustGrossMarginbyItem_NA</p></td>
<td><p>CustGrossMarginbyItem_NA</p></td>
</tr>
<tr class="even">
<td><p>CustInPaymentCH</p></td>
<td><p>CustInPaymentCH</p></td>
</tr>
<tr class="odd">
<td><p>CustInPaymSE</p></td>
<td><p>CustInPaymSE</p></td>
</tr>
<tr class="even">
<td><p>CustInvoiceSettled_TransDate_ES</p></td>
<td><p>CustInvoiceSettled_TransDate_ES</p></td>
</tr>
<tr class="odd">
<td><p>CustInvoiceVolume_BE</p></td>
<td><p>CustInvoiceVolume_BE</p></td>
</tr>
<tr class="even">
<td><p>CustOpenBillId_ES</p></td>
<td><p>CustOpenBillId_ES</p></td>
</tr>
<tr class="odd">
<td><p>CustOutAttendingNoteAT_EDIFACT</p></td>
<td><p>CustOutAttendingNoteAT_EDIFACT</p></td>
</tr>
<tr class="even">
<td><p>CustOutAttendingNoteDE_DTAUS</p></td>
<td><p>CustOutAttendingNoteDE_DTAUS</p></td>
</tr>
<tr class="odd">
<td><p>CustOutCoveringLetterDE_DTAUS</p></td>
<td><p>CustOutCoveringLetterDE_DTAUS</p></td>
</tr>
<tr class="even">
<td><p>CustOutPaymAdviceAT_EDIFACT</p></td>
<td><p>CustOutPaymAdviceAT_EDIFACT</p></td>
</tr>
<tr class="odd">
<td><p>CustOutPaymAdviceCH_DebitDirect</p></td>
<td><p>CustOutPaymAdviceCH_DebitDirect</p></td>
</tr>
<tr class="even">
<td><p>CustOutPaymAdviceCH_LSV</p></td>
<td><p>CustOutPaymAdviceCH_LSV</p></td>
</tr>
<tr class="odd">
<td><p>CustOutPaymControl</p></td>
<td><p>CustOutPaymControl</p></td>
</tr>
<tr class="even">
<td><p>CustOutPaymControl_ES</p></td>
<td><p>CustOutPaymControl_ES</p></td>
</tr>
<tr class="odd">
<td><p>CustOutPaymControl_FR</p></td>
<td><p>CustOutPaymControl_FR</p></td>
</tr>
<tr class="even">
<td><p>CustOutPaymControl_FR_LCR</p></td>
<td><p>CustOutPaymControl_FR_LCR</p></td>
</tr>
<tr class="odd">
<td><p>CustOutPaymControl_IT</p></td>
<td><p>CustOutPaymControl_IT</p></td>
</tr>
<tr class="even">
<td><p>CustOutPaymLetterFR</p></td>
<td><p>CustOutPaymLetter_FR</p></td>
</tr>
<tr class="odd">
<td><p>CustOutPaymOrderCH_DebitDirect</p></td>
<td><p>TaxWithholdCertificationIT</p></td>
</tr>
<tr class="even">
<td><p>CustOutPaymOrderCH_LSV</p></td>
<td><p>TaxWithholdYearlyReportIT</p></td>
</tr>
<tr class="odd">
<td><p>CustPaymentJournal_NA</p></td>
<td><p>TaxWithholdMonthlyReportIT</p></td>
</tr>
<tr class="even">
<td><p>CustPaymReconciliationPrint_DK_BS</p></td>
<td><p>CustPaymReconciliationPrint_DK_BS</p></td>
</tr>
<tr class="odd">
<td><p>CustPostPaymJournal_NA</p></td>
<td><p>CustPostPaymJournal_NA</p></td>
</tr>
<tr class="even">
<td><p>CustSalesAnalysisByInvoice_NA</p></td>
<td><p>CustSalesAnalysisByInvoice_NA</p></td>
</tr>
<tr class="odd">
<td><p>CustSalesDistribution_NA</p></td>
<td><p>CustSalesDistribution_NA</p></td>
</tr>
<tr class="even">
<td><p>CustSalesItemGroupStatistics_NA</p></td>
<td><p>CustSalesItemGroupStatistics_NA</p></td>
</tr>
<tr class="odd">
<td><p>CustSalesOpenLinesByCust_NA</p></td>
<td><p>CustSalesOpenLines_NA with ByCust design</p></td>
</tr>
<tr class="even">
<td><p>CustSalesOpenLinesByDelvDate_NA</p></td>
<td><p>CustSalesOpenLines_NA with ByDelvDate design</p></td>
</tr>
<tr class="odd">
<td><p>CustSalesOpenLinesByItem_NA</p></td>
<td><p>CustSalesOpenLines_NA with ByItem design</p></td>
</tr>
<tr class="even">
<td><p>CustShippedNotInvoiced_NA</p></td>
<td><p>CustShippedNotInvoiced_NA</p></td>
</tr>
<tr class="odd">
<td><p>CustTransOpen_ES</p></td>
<td><p>CustTransOpen_ES</p></td>
</tr>
<tr class="even">
<td><p>RCSalesList_UK</p></td>
<td><p>RCSalesList_UK</p></td>
</tr>
<tr class="odd">
<td><p>CustInPaymNO</p></td>
<td><p>CustInPaymNO</p></td>
</tr>
<tr class="even">
<td><p>FreeTextInvoice</p></td>
<td><p>FreeTextInvoice</p></td>
</tr>
<tr class="odd">
<td><p>SalesInvoice</p></td>
<td><p>SalesInvoice</p></td>
</tr>
<tr class="even">
<td><p>SalesPackingSlip</p></td>
<td><p>SalesPackingSlip</p></td>
</tr>
<tr class="odd">
<td><p>BankReconciliation</p></td>
<td><p>BankReconciliation</p></td>
</tr>
<tr class="even">
<td><p>BankBillOfExchange_FR</p></td>
<td><p>BankBillOfExchange_FR</p></td>
</tr>
<tr class="odd">
<td><p>BankCashflowReport</p></td>
<td><p>BankCashflowReport</p></td>
</tr>
<tr class="even">
<td><p>BankCodaDetails</p></td>
<td><p>BankCodaDetails</p></td>
</tr>
<tr class="odd">
<td><p>BankPaymIdTypesSetup_NO</p></td>
<td><p>BankPaymIdTypesSetup_NO</p></td>
</tr>
<tr class="even">
<td><p>BankPromissoryNote_ES</p></td>
<td><p>BankPromissoryNote_ES</p></td>
</tr>
<tr class="odd">
<td><p>BankPromissoryNote_FR</p></td>
<td><p>BankPromissoryNote_FR</p></td>
</tr>
<tr class="even">
<td><p>Cheque_CA</p></td>
<td><p>Cheque_CA</p></td>
</tr>
<tr class="odd">
<td><p>Cheque_DE</p></td>
<td><p>Cheque_DE</p></td>
</tr>
<tr class="even">
<td><p>Cheque_DK</p></td>
<td><p>Cheque_DK</p></td>
</tr>
<tr class="odd">
<td><p>Cheque_ES</p></td>
<td><p>Cheque_ES</p></td>
</tr>
<tr class="even">
<td><p>Cheque_FR</p></td>
<td><p>Cheque_FR</p></td>
</tr>
<tr class="odd">
<td><p>Cheque_UK</p></td>
<td><p>Cheque_UK</p></td>
</tr>
<tr class="even">
<td><p>Cheque_US</p></td>
<td><p>Cheque_US</p></td>
</tr>
<tr class="odd">
<td><p>BankReconciliationSummary</p></td>
<td><p>BankReconciliationSummary</p></td>
</tr>
<tr class="even">
<td><p>BankReconciliationSummary</p></td>
<td><p>BankReconciliationSummary</p></td>
</tr>
<tr class="odd">
<td><p>EUSalesListAT</p></td>
<td><p>EUSalesListAT</p></td>
</tr>
<tr class="even">
<td><p>EUSalesListDE</p></td>
<td><p>EUSalesListDE</p></td>
</tr>
<tr class="odd">
<td><p>EUSalesListDK</p></td>
<td><p>EUSalesListDK</p></td>
</tr>
<tr class="even">
<td><p>EUSalesListFI</p></td>
<td><p>EUSalesListFI</p></td>
</tr>
<tr class="odd">
<td><p>EUSalesListNL</p></td>
<td><p>EUSalesListNL</p></td>
</tr>
<tr class="even">
<td><p>EUSalesListSE</p></td>
<td><p>EUSalesListSE</p></td>
</tr>
<tr class="odd">
<td><p>EUSalesListUK</p></td>
<td><p>EUSalesListUK</p></td>
</tr>
<tr class="even">
<td><p>LedgerJournal</p></td>
<td><p>LedgerJournal</p></td>
</tr>
<tr class="odd">
<td><p>LedgerAccountSched</p></td>
<td><p>LedgerAccountSched</p></td>
</tr>
<tr class="even">
<td><p>LedgerTotalAndBalanceList</p></td>
<td><p>LedgerTotalAndBalanceList</p></td>
</tr>
<tr class="odd">
<td><p>TaxWithholdReport_TH</p></td>
<td><p>TaxWithholdReport_TH</p></td>
</tr>
<tr class="even">
<td><p>TaxWithholdReportPND_TH</p></td>
<td><p>TaxWithholdReportPND_TH</p></td>
</tr>
<tr class="odd">
<td><p>TaxWithholdSlip_TH</p></td>
<td><p>TaxWithholdSlip_TH</p></td>
</tr>
<tr class="even">
<td><p>AssetDepreciationLedger_IT</p></td>
<td><p>AssetDepreciationLedger_IT</p></td>
</tr>
<tr class="odd">
<td><p>AssetOverviewBE</p></td>
<td><p>AssetOverviewBE</p></td>
</tr>
<tr class="even">
<td><p>AssetStatementLowValuePool_AU</p></td>
<td><p>AssetStatementLowValuePool_AU</p></td>
</tr>
<tr class="odd">
<td><p>LedgerCentralisationJournalReportBE</p></td>
<td><p>LedgerCentralisationJournalReportBE</p></td>
</tr>
<tr class="even">
<td><p>LedgerFinancialJournalReportBE</p></td>
<td><p>LedgerFinancialJournalReportBE</p></td>
</tr>
<tr class="odd">
<td><p>LedgerFiscalJournal_IT</p></td>
<td><p>LedgerFiscalJournal_IT</p></td>
</tr>
<tr class="even">
<td><p>LedgerInAccountStatementDE_DTAUS</p></td>
<td><p>LedgerInAccountStatementDE_DTAUS</p></td>
</tr>
<tr class="odd">
<td><p>LedgerInAccountStatementDE_MT940</p></td>
<td><p>LedgerInAccountStatementDE_MT940</p></td>
</tr>
<tr class="even">
<td><p>LedgerJournalizeReport_DE</p></td>
<td><p>LedgerJournalizeReport_DE</p></td>
</tr>
<tr class="odd">
<td><p>LedgerJournalizeReport_ES</p></td>
<td><p>LedgerJournalizeReport_ES</p></td>
</tr>
<tr class="even">
<td><p>LedgerPeriodSum_FR</p></td>
<td><p>LedgerPeriodSum_FR</p></td>
</tr>
<tr class="odd">
<td><p>LedgerPurchaseJournalReportBE</p></td>
<td><p>LedgerPurchaseJournalReportBE</p></td>
</tr>
<tr class="even">
<td><p>LedgerTransDateVoucher_FR</p></td>
<td><p>LedgerTransDateVoucher_FR</p></td>
</tr>
<tr class="odd">
<td><p>LedgerXBorderActivityAT</p></td>
<td><p>LedgerXBorderActivityAT</p></td>
</tr>
<tr class="even">
<td><p>Tax1099Detail</p></td>
<td><p>Tax1099Detail</p></td>
</tr>
<tr class="odd">
<td><p>Tax1099DupTIN</p></td>
<td><p>Tax1099DupTIN</p></td>
</tr>
<tr class="even">
<td><p>Tax1099Report</p></td>
<td><p>Tax1099Report</p></td>
</tr>
<tr class="odd">
<td><p>Tax1099Summary</p></td>
<td><p>Tax1099Summary</p></td>
</tr>
<tr class="even">
<td><p>TaxAmountByCustomer_BE</p></td>
<td><p>TaxAmountByCustomer_BE</p></td>
</tr>
<tr class="odd">
<td><p>TaxAmountByVendor_BE</p></td>
<td><p>TaxAmountByVendor_BE</p></td>
</tr>
<tr class="even">
<td><p>TaxBookReport_ES</p></td>
<td><p>TaxBookReport_ES</p></td>
</tr>
<tr class="odd">
<td><p>TaxBookReportSum_ES</p></td>
<td><p>TaxBookReportSum_ES</p></td>
</tr>
<tr class="even">
<td><p>TaxList_BE</p></td>
<td><p>TaxList_BE</p></td>
</tr>
<tr class="odd">
<td><p>TaxPurchaseTaxReport</p></td>
<td><p>TaxPurchaseTaxReport</p></td>
</tr>
<tr class="even">
<td><p>TaxPurchLedger</p></td>
<td><p>TaxPurchLedger</p></td>
</tr>
<tr class="odd">
<td><p>TaxReport_AU</p></td>
<td><p>TaxReport_AU</p></td>
</tr>
<tr class="even">
<td><p>TaxReport_BE</p></td>
<td><p>TaxReport_BE</p></td>
</tr>
<tr class="odd">
<td><p>TaxReport_DE</p></td>
<td><p>TaxReport_DE</p></td>
</tr>
<tr class="even">
<td><p>TaxReport_IT</p></td>
<td><p>TaxReport_IT</p></td>
</tr>
<tr class="odd">
<td><p>TaxReport_NL</p></td>
<td><p>TaxReport_NL</p></td>
</tr>
<tr class="even">
<td><p>TaxReport_NO</p></td>
<td><p>TaxReport_NO</p></td>
</tr>
<tr class="odd">
<td><p>TaxReport_SE</p></td>
<td><p>TaxReport_SE</p></td>
</tr>
<tr class="even">
<td><p>TaxReport_SG</p></td>
<td><p>TaxReport_SG</p></td>
</tr>
<tr class="odd">
<td><p>TaxReport_US</p></td>
<td><p>TaxReport_US</p></td>
</tr>
<tr class="even">
<td><p>TaxReport349</p></td>
<td><p>TaxReport349</p></td>
</tr>
<tr class="odd">
<td><p>TaxReportAlandImport_FI</p></td>
<td><p>TaxReportAlandImport_FI</p></td>
</tr>
<tr class="even">
<td><p>TaxReportCorrectionBE</p></td>
<td><p>TaxReportCorrectionBE</p></td>
</tr>
<tr class="odd">
<td><p>TaxReportIntervat</p></td>
<td><p>TaxReportIntervat</p></td>
</tr>
<tr class="even">
<td><p>TaxReportUnrealizedInputOutput</p></td>
<td><p>TaxReportUnrealizedInputOutput</p></td>
</tr>
<tr class="odd">
<td><p>TaxSalesLedger</p></td>
<td><p>TaxSalesLedger</p></td>
</tr>
<tr class="even">
<td><p>TaxTrans_BE</p></td>
<td><p>TaxTrans_BE</p></td>
</tr>
<tr class="odd">
<td><p>TaxTransDetail_BE</p></td>
<td><p>TaxTransDetail_BE</p></td>
</tr>
<tr class="even">
<td><p>TaxWithholdCertificationIT</p></td>
<td><p>TaxWithholdCertification_IT</p></td>
</tr>
<tr class="odd">
<td><p>TaxWithholdYearlyReportIT</p></td>
<td><p>TaxWithholdYearlyReport_IT</p></td>
</tr>
<tr class="even">
<td><p>LedgerPostingJournalList</p></td>
<td><p>LedgerPostingJournalList</p></td>
</tr>
<tr class="odd">
<td><p>LedgerPostingJournalTotal</p></td>
<td><p>LedgerPostingJournalTotal</p></td>
</tr>
<tr class="even">
<td><p>TaxReconciliationReport</p></td>
<td><p>TaxReconciliationReport</p></td>
</tr>
<tr class="odd">
<td><p>TaxReport_FI</p></td>
<td><p>TaxReport_FI</p></td>
</tr>
<tr class="even">
<td><p>TaxYearlyComReport_IT</p></td>
<td><p>TaxYearlyComReport_IT</p></td>
</tr>
<tr class="odd">
<td><p>LedgerTransAccountVoucher_FR</p></td>
<td><p>LedgerTransAccountVoucher_FR</p></td>
</tr>
<tr class="even">
<td><p>LedgerAccountSum_FR</p></td>
<td><p>LedgerAccountSum_FR</p></td>
</tr>
<tr class="odd">
<td><p>TaxWithholdMonthlyReportIT</p></td>
<td><p>TaxWithholdMonthlyReport_IT</p></td>
</tr>
<tr class="even">
<td><p>VendConsultationFees_SA</p></td>
<td><p>VendConsultationFees_SA</p></td>
</tr>
<tr class="odd">
<td><p>VendSubContractor_SA</p></td>
<td><p>VendSubcontractor_SA</p></td>
</tr>
<tr class="even">
<td><p>LedgerMainReportZakat_SA</p></td>
<td><p>LedgerMainReportZakat_SA</p></td>
</tr>
<tr class="odd">
<td><p>InventMovement_TH</p></td>
<td><p>InventMovement_TH</p></td>
</tr>
<tr class="even">
<td><p>InventPhysicalPerWarehouseTrans_IT</p></td>
<td><p>InventPhysicalPerWarehouseTrans_IT</p></td>
</tr>
<tr class="odd">
<td><p>InventProdComGeneral</p></td>
<td><p>InventProdComGeneral</p></td>
</tr>
<tr class="even">
<td><p>InventFiscalLIFOValuation</p></td>
<td><p>InventFiscalLIFOValuation</p></td>
</tr>
<tr class="odd">
<td><p>IntrastatFormLetterAT</p></td>
<td><p>IntrastatFormLetterAT</p></td>
</tr>
<tr class="even">
<td><p>IntrastatFormLetterDE</p></td>
<td><p>IntrastatFormLetterDE</p></td>
</tr>
<tr class="odd">
<td><p>IntrastatFormLetterES</p></td>
<td><p>IntrastatFormLetterES</p></td>
</tr>
<tr class="even">
<td><p>IntrastatFormLetterFI</p></td>
<td><p>IntrastatFormLetterFI</p></td>
</tr>
<tr class="odd">
<td><p>IntrastatFormLetterFR</p></td>
<td><p>IntrastatFormLetterFR</p></td>
</tr>
<tr class="even">
<td><p>IntrastatFormLetterIT</p></td>
<td><p>IntrastatFormLetterIT</p></td>
</tr>
<tr class="odd">
<td><p>IntrastatFormLetterSE</p></td>
<td><p>IntrastatFormLetterSE</p></td>
</tr>
<tr class="even">
<td><p>IntrastatFormLetterUK</p></td>
<td><p>IntrastatFormLetterUK</p></td>
</tr>
<tr class="odd">
<td><p>IntrastatListES</p></td>
<td><p>IntrastatListES</p></td>
</tr>
<tr class="even">
<td><p>IntrastatListNL</p></td>
<td><p>IntrastatListNL</p></td>
</tr>
<tr class="odd">
<td><p>IntrastatListUK</p></td>
<td><p>IntrastatListUK</p></td>
</tr>
<tr class="even">
<td><p>IntrastatPeriodReport_IT</p></td>
<td><p>IntrastatPeriodReport_IT</p></td>
</tr>
<tr class="odd">
<td><p>IntrastatListFI</p></td>
<td><p>IntrastatListFI</p></td>
</tr>
<tr class="even">
<td><p>HRMEPAbsenceTransList</p></td>
<td><p>HcmEPAbsenceTransListThisYear</p></td>
</tr>
<tr class="odd">
<td><p>HRMEPBirthday</p></td>
<td><p>HcmEPBirthdays</p></td>
</tr>
<tr class="even">
<td><p>HRMEPJubilee</p></td>
<td><p>HcmEPAnniversaries</p></td>
</tr>
<tr class="odd">
<td><p>HRMAbsenceAdministration</p></td>
<td><p>HcmAbsenceAdministration</p></td>
</tr>
<tr class="even">
<td><p>HRMAbsenceEmplDue</p></td>
<td><p>HcmAbsenceJournalMissingReport</p></td>
</tr>
<tr class="odd">
<td><p>HRMAbsenceSetup</p></td>
<td><p>HcmAbsenceSetup</p></td>
</tr>
<tr class="even">
<td><p>HRMAbsenceStatusListPrint</p></td>
<td><p>HcmAbsenceStatus </p></td>
</tr>
<tr class="odd">
<td><p>HRMAccommodationtList</p></td>
<td><p>HCMAccommodationtList</p></td>
</tr>
<tr class="even">
<td><p>HRMADARequirement</p></td>
<td><p>HcmADARequirement</p></td>
</tr>
<tr class="odd">
<td><p>HRMApplicantStatus</p></td>
<td><p>HcmApplicantStatusReport</p></td>
</tr>
<tr class="even">
<td><p>HRMBirthday</p></td>
<td><p>HcmBirthday</p></td>
</tr>
<tr class="odd">
<td><p>HRMCourseAgenda</p></td>
<td><p>HcmCourseAgenda</p></td>
</tr>
<tr class="even">
<td><p>HRMCourseAttendeeLine</p></td>
<td><p>HcmCourseAttendeeLine</p></td>
</tr>
<tr class="odd">
<td><p>HRMCourseAttendeeStatusList</p></td>
<td><p>HcmCourseAttendeeStatusList</p></td>
</tr>
<tr class="even">
<td><p>HRMCourseConfirmation</p></td>
<td><p>HcmCourseConfirmation</p></td>
</tr>
<tr class="odd">
<td><p>HRMCourseDesign</p></td>
<td><p>HcmCourseDesign</p></td>
</tr>
<tr class="even">
<td><p>HRMCourseSkills</p></td>
<td><p>HcmCourseSkills</p></td>
</tr>
<tr class="odd">
<td><p>HRMCourseTableInstructor</p></td>
<td><p>HcmCourseTableInstructor</p></td>
</tr>
<tr class="even">
<td><p>HRMEmplLeave</p></td>
<td><p>HcmEmployeeLeave</p></td>
</tr>
<tr class="odd">
<td><p>HRMEmployeeBenefit</p></td>
<td><p>HcmWorkerBenefits </p></td>
</tr>
<tr class="even">
<td><p>HRMGoalAlarm</p></td>
<td><p>HcmGoalAlarm</p></td>
</tr>
<tr class="odd">
<td><p>HRMi9Document</p></td>
<td><p>Hcmi9Document</p></td>
</tr>
<tr class="even">
<td><p>HRMi9DocumentExpireList</p></td>
<td><p>Hcmi9DocumentExpireList</p></td>
</tr>
<tr class="odd">
<td><p>HRMi9DocumentTypeExpireList</p></td>
<td><p>Hcmi9DocumentTypeExpireList</p></td>
</tr>
<tr class="even">
<td><p>HRMi9InspectionList</p></td>
<td><p>Hcmi9InspectionList</p></td>
</tr>
<tr class="odd">
<td><p>HRMJobByOrganization</p></td>
<td><p>HcmPositionsByDepartment </p></td>
</tr>
<tr class="even">
<td><p>HRMJobInformation</p></td>
<td><p>HcmJobInformation</p></td>
</tr>
<tr class="odd">
<td><p>HRMJubilee</p></td>
<td><p>HcmAnniversary</p></td>
</tr>
<tr class="even">
<td><p>HRMMassHireProject</p></td>
<td><p>HcmMassHireProject</p></td>
</tr>
<tr class="odd">
<td><p>HRMOrganizationTotal</p></td>
<td><p>HcmNumberOfWorkersReport</p></td>
</tr>
<tr class="even">
<td><p>HRMRecruiting</p></td>
<td><p>HcmRecruiting</p></td>
</tr>
<tr class="odd">
<td><p>HRMRecruitingApplicationStatus</p></td>
<td><p>HcmRecruitingApplicationStatus</p></td>
</tr>
<tr class="even">
<td><p>HRMSeniority</p></td>
<td><p>HcmSeniorityReport</p></td>
</tr>
<tr class="odd">
<td><p>HRMSkillBySkillType</p></td>
<td><p>HcmSkillBySkillType</p></td>
</tr>
<tr class="even">
<td><p>HRMSkillBySkillTypeCount</p></td>
<td><p>HcmSkillBySkillTypeCount</p></td>
</tr>
<tr class="odd">
<td><p>HRMSkillGapJob</p></td>
<td><p>HcmSkillGapJob</p></td>
</tr>
<tr class="even">
<td><p>HRMSkillProfile</p></td>
<td><p>HcmSkillProfile</p></td>
</tr>
<tr class="odd">
<td><p>HRMSkillType</p></td>
<td><p>HcmSkillType</p></td>
</tr>
<tr class="even">
<td><p>HRMVirtualNetworkCV</p></td>
<td><p>HcmWorkerResume &amp; HcmApplicantResume</p></td>
</tr>
<tr class="odd">
<td><p>HRMVirtualNetworkDueCertificate</p></td>
<td><p>HcmDueCertificate</p></td>
</tr>
<tr class="even">
<td><p>HRMVirtualNetworkIdByOrganization</p></td>
<td><p>HcmPeopleDepartmentReport</p></td>
</tr>
<tr class="odd">
<td><p>HRMVirtualNetworkSkill</p></td>
<td><p>HcmWorkerSkill</p></td>
</tr>
<tr class="even">
<td><p>HRMJobTemplateInformation</p></td>
<td><p>HcmJobTemplateInformation</p></td>
</tr>
<tr class="odd">
<td><p>OrganizationUnit</p></td>
<td><p>HcmDepartmentReport</p></td>
</tr>
<tr class="even">
<td><p>HRMCourseAttendeeCollectionResult</p></td>
<td><p>HcmCourseAttendeeCollectionResult</p></td>
</tr>
<tr class="odd">
<td><p>KMKnowledgeCollector</p></td>
<td><p>KMKnowledgeCollector</p></td>
</tr>
<tr class="even">
<td><p>KMKnowledgeCollectorByCollection</p></td>
<td><p>KMAnswersByQuestionnaire</p></td>
</tr>
<tr class="odd">
<td><p>KMKnowledgeCollectorByVirtualNetworkId</p></td>
<td><p>KMAnswersByPerson</p></td>
</tr>
<tr class="even">
<td><p>KMQuestionAnalyze</p></td>
<td><p>KMQuestionAnalyze</p></td>
</tr>
<tr class="odd">
<td><p>KMQuestionAndAnswer</p></td>
<td><p>KMQuestionandAnswer</p></td>
</tr>
<tr class="even">
<td><p>Cust</p></td>
<td><p>Cust</p></td>
</tr>
<tr class="odd">
<td><p>CustBasedata</p></td>
<td><p>CustBaseData</p></td>
</tr>
<tr class="even">
<td><p>CustRevenue</p></td>
<td><p>smmCustRevenue</p></td>
</tr>
<tr class="odd">
<td><p>SalesItemCustStatistics</p></td>
<td><p>smmSlaesCustStatistics</p></td>
</tr>
<tr class="even">
<td><p>SalesRanking</p></td>
<td><p>smmSalesRanking</p></td>
</tr>
<tr class="odd">
<td><p>smmActivityAnalyses</p></td>
<td><p>smmActivityAnalyses</p></td>
</tr>
<tr class="even">
<td><p>smmCampaignResponseFrequency</p></td>
<td><p>smmCampaignResponseFrequency</p></td>
</tr>
<tr class="odd">
<td><p>smmPhoneAverage</p></td>
<td><p>smmPhoneAverage</p></td>
</tr>
<tr class="even">
<td><p>smmSalesTargets</p></td>
<td><p>smmSalesTarget</p></td>
</tr>
<tr class="odd">
<td><p>smmTMCallListTelemarketingSummary</p></td>
<td><p>smmTMCallListTelemarketingSummary</p></td>
</tr>
<tr class="even">
<td><p>EPProjHourStatement</p></td>
<td><p>EPProjHourStatement</p></td>
</tr>
<tr class="odd">
<td><p>TrvAllowance</p></td>
<td><p>TrvAllowance</p></td>
</tr>
<tr class="even">
<td><p>TrvCost</p></td>
<td><p>TrvCost</p></td>
</tr>
<tr class="odd">
<td><p>TrvCostStatistics</p></td>
<td><p>TrvCostStatistics</p></td>
</tr>
<tr class="even">
<td><p>TrvExpense</p></td>
<td><p>TrvExpense</p></td>
</tr>
<tr class="odd">
<td><p>TrvExpenseSettlementReport</p></td>
<td><p>TrvExpenseSettlementReport</p></td>
</tr>
<tr class="even">
<td><p>TrvMileage</p></td>
<td><p>TrvMileage</p></td>
</tr>
<tr class="odd">
<td><p>TrvPersonalExpenses</p></td>
<td><p>TrvPersonalExpenses</p></td>
</tr>
<tr class="even">
<td><p>ProjCashFlowCategoryReport</p></td>
<td><p>ProjCashFlowCategory</p></td>
</tr>
<tr class="odd">
<td><p>ProjCashFlowEmplItemReport</p></td>
<td><p>ProjCashFlowEmplItem</p></td>
</tr>
<tr class="even">
<td><p>ProjCashFlowProjectReport</p></td>
<td><p>ProjCashFlowProject</p></td>
</tr>
<tr class="odd">
<td><p>ProjListClosingProfile</p></td>
<td><p>ProjClosingProfile</p></td>
</tr>
<tr class="even">
<td><p>ProjEstimateList</p></td>
<td><p>ProjEstimateList</p></td>
</tr>
<tr class="odd">
<td><p>ProjInvoice</p></td>
<td><p>ProjInvoice</p></td>
</tr>
<tr class="even">
<td><p>ProjInvoiceJournal</p></td>
<td><p>ProjInvoiceJournal</p></td>
</tr>
<tr class="odd">
<td><p>ProjJournalEmpl</p></td>
<td><p>ProjJournalEmpl</p></td>
</tr>
<tr class="even">
<td><p>ProjJournalRevenue</p></td>
<td><p>ProjJournalRevenue</p></td>
</tr>
<tr class="odd">
<td><p>ProjListBudget</p></td>
<td><p>ProjListBudget</p></td>
</tr>
<tr class="even">
<td><p>ProjListEstimateHourRate</p></td>
<td><p>ProjListEstimateHourRate</p></td>
</tr>
<tr class="odd">
<td><p>ProjListEstimateProdBacklogConsumption</p></td>
<td><p>ProjListEstimate</p></td>
</tr>
<tr class="even">
<td><p>ProjListEstimateProdBacklogOnAcc</p></td>
<td><p>ProjListEstimate</p></td>
</tr>
<tr class="odd">
<td><p>ProjListEstimateProdBacklogPL</p></td>
<td><p>ProjListEstimate</p></td>
</tr>
<tr class="even">
<td><p>ProjListEstimateReadyForElimination</p></td>
<td><p>ProjListEstimate</p></td>
</tr>
<tr class="odd">
<td><p>ProjListEstimateWonFixedPriceProjPL</p></td>
<td><p>ProjListEstimate</p></td>
</tr>
<tr class="even">
<td><p>ProjListInvoiceTable</p></td>
<td><p>ProjListInvoiceTable</p></td>
</tr>
<tr class="odd">
<td><p>ProjListLedgerReconPayRoll</p></td>
<td><p>ProjListLedgerRecon</p></td>
</tr>
<tr class="even">
<td><p>ProjListLedgerReconProfitLoss</p></td>
<td><p>ProjListLedgerRecon</p></td>
</tr>
<tr class="odd">
<td><p>ProjListLedgerReconWIP</p></td>
<td><p>ProjListLedgerRecon</p></td>
</tr>
<tr class="even">
<td><p>ProjListLedgerReconWIPAccount</p></td>
<td><p>ProjListLedgerReconWIPAccount</p></td>
</tr>
<tr class="odd">
<td><p>ProjListLedgerUpdatesConsumption</p></td>
<td><p>ProjListLedgerUpdates</p></td>
</tr>
<tr class="even">
<td><p>ProjListLedgerUpdatesOnAccount</p></td>
<td><p>ProjListLedgerUpdates</p></td>
</tr>
<tr class="odd">
<td><p>ProjListLedgerUpdatesPayroll</p></td>
<td><p>ProjListLedgerUpdates</p></td>
</tr>
<tr class="even">
<td><p>ProjListLedgerUpdatesProfitLoss</p></td>
<td><p>ProjListLedgerUpdatesProfitLoss</p></td>
</tr>
<tr class="odd">
<td><p>ProjListLedgerUpdatesWIP</p></td>
<td><p>ProjListLedgerUpdates</p></td>
</tr>
<tr class="even">
<td><p>ProjListLineProperty</p></td>
<td><p>ProjListLineProperty</p></td>
</tr>
<tr class="odd">
<td><p>ProjListPostingReady</p></td>
<td><p>ProjListPostingReady</p></td>
</tr>
<tr class="even">
<td><p>ProjListProjConsumptionCategory</p></td>
<td><p>ProjConsumCateg</p></td>
</tr>
<tr class="odd">
<td><p>ProjListProjConsumptionCategory2Column</p></td>
<td><p>ProjConsumCateg2Column</p></td>
</tr>
<tr class="even">
<td><p>ProjListProjConsumptionCategory2CoPeriod</p></td>
<td><p>ProjConsumCateg2Prd</p></td>
</tr>
<tr class="odd">
<td><p>ProjListProjConsumptionEmplItem</p></td>
<td><p>ProjConsumEmpl</p></td>
</tr>
<tr class="even">
<td><p>ProjListProjConsumptionEmplItem2Column</p></td>
<td><p>ProjConsumEmpl2Column</p></td>
</tr>
<tr class="odd">
<td><p>ProjListProjConsumptionEmplItem2CoPeriod</p></td>
<td><p>ProjConsumeEmpl2Prd</p></td>
</tr>
<tr class="even">
<td><p>ProjListProjConsumptionProj</p></td>
<td><p>ProjConsumProj</p></td>
</tr>
<tr class="odd">
<td><p>ProjListProjConsumptionProj2Column</p></td>
<td><p>ProjConsumProj2Column</p></td>
</tr>
<tr class="even">
<td><p>ProjListProjConsumptionProj2ColumnPeriod</p></td>
<td><p>ProjConsumProj2Prd</p></td>
</tr>
<tr class="odd">
<td><p>ProjListProjHourRateCategory</p></td>
<td><p>ProjHourRateCateg</p></td>
</tr>
<tr class="even">
<td><p>ProjListProjHourRateEmplItem</p></td>
<td><p>ProjHourRateEmpl</p></td>
</tr>
<tr class="odd">
<td><p>ProjListProjHourRateProj</p></td>
<td><p>ProjHourRateProj</p></td>
</tr>
<tr class="even">
<td><p>ProjListProjOnAccountProj</p></td>
<td><p>ProjOnAccProj</p></td>
</tr>
<tr class="odd">
<td><p>ProjListProjOnAccountProj2Column</p></td>
<td><p>ProjOnAccProj2Column</p></td>
</tr>
<tr class="even">
<td><p>ProjListProjOnAccountProj2ColumnPeriod</p></td>
<td><p>ProjOnAccProj2Prd</p></td>
</tr>
<tr class="odd">
<td><p>ProjListProjPayRollCategory</p></td>
<td><p>ProjPayrollCateg</p></td>
</tr>
<tr class="even">
<td><p>ProjListProjPayRollCategory2Column</p></td>
<td><p>ProjPayrollCateg2Column</p></td>
</tr>
<tr class="odd">
<td><p>ProjListProjPayRollCategory2ColumnPeriod</p></td>
<td><p>ProjPayrollCateg2Prd</p></td>
</tr>
<tr class="even">
<td><p>ProjListProjPayRollEmplItem</p></td>
<td><p>ProjPayrollEmpl</p></td>
</tr>
<tr class="odd">
<td><p>ProjListProjPayRollEmplItem2Column</p></td>
<td><p>ProjPayrollEmpl2Column</p></td>
</tr>
<tr class="even">
<td><p>ProjListProjPayRollEmplItem2ColumnPeriod</p></td>
<td><p>ProjPayrollEmpl2Prd</p></td>
</tr>
<tr class="odd">
<td><p>ProjListProjPayRollProj</p></td>
<td><p>ProjPayrollProj</p></td>
</tr>
<tr class="even">
<td><p>ProjListProjPayRollProj2Column</p></td>
<td><p>ProjPayrollProj2Column</p></td>
</tr>
<tr class="odd">
<td><p>ProjListProjPayRollProj2ColumnPeriod</p></td>
<td><p>ProjPayrollProj2Prd</p></td>
</tr>
<tr class="even">
<td><p>ProjListProjPosting</p></td>
<td><p>ProjListProjPosting</p></td>
</tr>
<tr class="odd">
<td><p>ProjListProjProfitLossCategory</p></td>
<td><p>ProjProfitLossCateg</p></td>
</tr>
<tr class="even">
<td><p>ProjListProjProfitLossCategory2ColPeriod</p></td>
<td><p>ProjProfitLossCateg2Prd</p></td>
</tr>
<tr class="odd">
<td><p>ProjListProjProfitLossCategory2Column</p></td>
<td><p>ProjProfitLossCateg2Column</p></td>
</tr>
<tr class="even">
<td><p>ProjListProjProfitLossEmplItem</p></td>
<td><p>ProjProfitLossEmpl</p></td>
</tr>
<tr class="odd">
<td><p>ProjListProjProfitLossEmplItem2ColPeriod</p></td>
<td><p>ProjProfitLossEmpl2Prd</p></td>
</tr>
<tr class="even">
<td><p>ProjListProjProfitLossEmplItem2Column</p></td>
<td><p>ProjProfitLossEmpl2Column</p></td>
</tr>
<tr class="odd">
<td><p>ProjListProjProfitLossProj</p></td>
<td><p>ProjProfitLossProj</p></td>
</tr>
<tr class="even">
<td><p>ProjListProjProfitLossProj2Column</p></td>
<td><p>ProjProfitLossProj2Column</p></td>
</tr>
<tr class="odd">
<td><p>ProjListProjProfitLossProj2ColumnPeriod</p></td>
<td><p>ProfitLossProj2Prd</p></td>
</tr>
<tr class="even">
<td><p>ProjListProjTable</p></td>
<td><p>ProjListProjTable</p></td>
</tr>
<tr class="odd">
<td><p>ProjListProjWIPCategory</p></td>
<td><p>ProjWIPCateg</p></td>
</tr>
<tr class="even">
<td><p>ProjListProjWIPCategory2Column</p></td>
<td><p>ProjWIPCateg2Column</p></td>
</tr>
<tr class="odd">
<td><p>ProjListProjWIPCategory2ColumnPeriod</p></td>
<td><p>ProjWIPCateg2Prd</p></td>
</tr>
<tr class="even">
<td><p>ProjListProjWIPCustTable</p></td>
<td><p>ProjListProjWIPCustTable</p></td>
</tr>
<tr class="odd">
<td><p>ProjListProjWIPEmplItem</p></td>
<td><p>ProjWIPEmpl</p></td>
</tr>
<tr class="even">
<td><p>ProjListProjWIPEmplItem2Column</p></td>
<td><p>ProjWIPEmpl2Column</p></td>
</tr>
<tr class="odd">
<td><p>ProjListProjWIPEmplItem2ColumnPeriod</p></td>
<td><p>ProjWIPEmpl2Prd</p></td>
</tr>
<tr class="even">
<td><p>ProjListProjWIPProj</p></td>
<td><p>ProjWIPProj</p></td>
</tr>
<tr class="odd">
<td><p>ProjListProjWIPProj2Column</p></td>
<td><p>ProjWIPProj2Column</p></td>
</tr>
<tr class="even">
<td><p>ProjListProjWIPProj2ColumnPeriod</p></td>
<td><p>ProjWIPProj2Prd</p></td>
</tr>
<tr class="odd">
<td><p>ProjListTrans</p></td>
<td><p>ProjListTrans</p></td>
</tr>
<tr class="even">
<td><p>ProjListTransCommittedCost</p></td>
<td><p>ProjListTransCommittedCost</p></td>
</tr>
<tr class="odd">
<td><p>ProjListTransProj</p></td>
<td><p>ProjListTransProj</p></td>
</tr>
<tr class="even">
<td><p>ProjMissingHourReg</p></td>
<td><p>ProjMissingHourReg</p></td>
</tr>
<tr class="odd">
<td><p>ProjOnAccountInvoicePlan</p></td>
<td><p>ProjOnAccountInvoicePlan</p></td>
</tr>
<tr class="even">
<td><p>ProjPeriodPosting</p></td>
<td><p>ProjPeriodPosting</p></td>
</tr>
<tr class="odd">
<td><p>ProjPriceGroupList</p></td>
<td><p>ProjPriceGroupList</p></td>
</tr>
<tr class="even">
<td><p>ProjUtilCategory</p></td>
<td><p>ProjUtilCategory</p></td>
</tr>
<tr class="odd">
<td><p>ProjUtilEmpl</p></td>
<td><p>ProjUtilEmpl</p></td>
</tr>
<tr class="even">
<td><p>ProjUtilProject</p></td>
<td><p>ProjUtilProject</p></td>
</tr>
<tr class="odd">
<td><p>ProjValCategory</p></td>
<td><p>ProjValCategory</p></td>
</tr>
<tr class="even">
<td><p>ProjValEmplCategory</p></td>
<td><p>ProjValEmplCategory</p></td>
</tr>
<tr class="odd">
<td><p>ProjValEmployee</p></td>
<td><p>ProjValEmployee</p></td>
</tr>
<tr class="even">
<td><p>ProjValEmployeeProj</p></td>
<td><p>ProjValEmployeeProj</p></td>
</tr>
<tr class="odd">
<td><p>ProjValProjCategory</p></td>
<td><p>ProjValProjCategory</p></td>
</tr>
<tr class="even">
<td><p>ProjValProject</p></td>
<td><p>ProjValProject</p></td>
</tr>
<tr class="odd">
<td><p>PurchPackingSlip</p></td>
<td><p>PurchPackingSlip</p></td>
</tr>
<tr class="even">
<td><p>PurchPurchaseOrder</p></td>
<td><p>PurchPurchaseOrder</p></td>
</tr>
<tr class="odd">
<td><p>PurchRanking</p></td>
<td><p>PurchRanking</p></td>
</tr>
<tr class="even">
<td><p>PurchReceiptsList</p></td>
<td><p>PurchReceiptsList</p></td>
</tr>
<tr class="odd">
<td><p>PurchVariencesCostPrice</p></td>
<td><p>PurchVariencesCostPrice</p></td>
</tr>
<tr class="even">
<td><p>ReqItemJournalSafetyStock</p></td>
<td><p>ReqItemJournalSafetyStock</p></td>
</tr>
<tr class="odd">
<td><p>ReqTransAction</p></td>
<td><p>ReqTransAction</p></td>
</tr>
<tr class="even">
<td><p>ReqTransFutures</p></td>
<td><p>ReqTransFutures</p></td>
</tr>
<tr class="odd">
<td><p>CommissionTrans</p></td>
<td><p>CommissionTrans</p></td>
</tr>
<tr class="even">
<td><p>ReturnAcknowledgment</p></td>
<td><p>ReturnAcknowledgmentAndDocument</p></td>
</tr>
<tr class="odd">
<td><p>ReturnDocument</p></td>
<td><p>ReturnAcknowledgmentAndDocument</p></td>
</tr>
<tr class="even">
<td><p>SalesCODLabel</p></td>
<td><p>SalesCODLabel</p></td>
</tr>
<tr class="odd">
<td><p>SalesConfirm</p></td>
<td><p>SalesConfirm</p></td>
</tr>
<tr class="even">
<td><p>SalesHeading</p></td>
<td><p>SalesHeading</p></td>
</tr>
<tr class="odd">
<td><p>SalesLinesExtended</p></td>
<td><p>SalesLinesExtended</p></td>
</tr>
<tr class="even">
<td><p>SalesNotInvoiced</p></td>
<td><p>SalesNotInvoiced</p></td>
</tr>
<tr class="odd">
<td><p>SalesPackingSlip</p></td>
<td><p>SalesPackingSlip</p></td>
</tr>
<tr class="even">
<td><p>SalesQuotation</p></td>
<td><p>SalesQuotation</p></td>
</tr>
<tr class="odd">
<td><p>SalesQuotationConfirmation</p></td>
<td><p>SalesQuotationConfirmation</p></td>
</tr>
<tr class="even">
<td><p>SalesShippingLabel</p></td>
<td><p>SalesShippingLabel</p></td>
</tr>
<tr class="odd">
<td><p>InventCheckSettlement</p></td>
<td><p>InventCheckSettlement</p></td>
</tr>
<tr class="even">
<td><p>InventSiteDimensionLinkValidation</p></td>
<td><p>InventSiteDimensionLinkValidation</p></td>
</tr>
<tr class="odd">
<td><p>WrkCtrCapRes</p></td>
<td><p>WrkCtrCapRes</p></td>
</tr>
<tr class="even">
<td><p>WrkCtrJobs</p></td>
<td><p>WrkCtrJobs</p></td>
</tr>
<tr class="odd">
<td><p>COSCostRatesPrint</p></td>
<td><p>COSCostRatesPrint</p></td>
</tr>
<tr class="even">
<td><p>COSDiffAccount</p></td>
<td><p>COSDiffAccount</p></td>
</tr>
<tr class="odd">
<td><p>COSDiffLedger</p></td>
<td><p>COSDiffLedger</p></td>
</tr>
<tr class="even">
<td><p>COSDiffProd</p></td>
<td><p>COSDiffProd</p></td>
</tr>
<tr class="odd">
<td><p>COSJournalReport</p></td>
<td><p>COSJournalReport</p></td>
</tr>
<tr class="even">
<td><p>COSPeriodCalculationUniversal</p></td>
<td><p>COSPeriodCalculationUniversal</p></td>
</tr>
<tr class="odd">
<td><p>COSReportPrint</p></td>
<td><p>COSReportPrint</p></td>
</tr>
<tr class="even">
<td><p>COSTrans</p></td>
<td><p>COSTrans</p></td>
</tr>
<tr class="odd">
<td><p>COSTransPreview</p></td>
<td><p>COSTransPreview</p></td>
</tr>
<tr class="even">
<td><p>EPSalesByCustomer</p></td>
<td><p>EPSalesByCustomer</p></td>
</tr>
<tr class="odd">
<td><p>EPSalesByRegion</p></td>
<td><p>EPSalesByRegion</p></td>
</tr>
<tr class="even">
<td><p>InventBalanceAccount</p></td>
<td><p>InventBalanceAccount</p></td>
</tr>
<tr class="odd">
<td><p>InventLedgerConciliation</p></td>
<td><p>InventLedgerConciliation</p></td>
</tr>
<tr class="even">
<td><p>BOMCalcTrans</p></td>
<td><p>BOMCalcTrans</p></td>
</tr>
<tr class="odd">
<td><p>BOMConsistOf</p></td>
<td><p>BOMConsistOf</p></td>
</tr>
<tr class="even">
<td><p>BOMPartOf</p></td>
<td><p>BOMPartOf</p></td>
</tr>
<tr class="odd">
<td><p>ConvInventPriceIsZero</p></td>
<td><p>ConvInventPriceIsZero</p></td>
</tr>
<tr class="even">
<td><p>ForecastSalesItem</p></td>
<td><p>ForecastSalesItem</p></td>
</tr>
<tr class="odd">
<td><p>InventABC</p></td>
<td><p>InventABC</p></td>
</tr>
<tr class="even">
<td><p>InventAdjOnHand</p></td>
<td><p>InventAdjOnHand</p></td>
</tr>
<tr class="odd">
<td><p>InventAdjTransaction</p></td>
<td><p>InventAdjTransaction</p></td>
</tr>
<tr class="even">
<td><p>InventAgeDim</p></td>
<td><p>InventAgeDim</p></td>
</tr>
<tr class="odd">
<td><p>InventAgeGroup</p></td>
<td><p>InventAgeGroup</p></td>
</tr>
<tr class="even">
<td><p>InventBalanceAccountService</p></td>
<td><p>InventBalanceAccountService</p></td>
</tr>
<tr class="odd">
<td><p>InventCheckReceiptCostPricePcs</p></td>
<td><p>InventCheckReceiptCostPricePcs</p></td>
</tr>
<tr class="even">
<td><p>InventCostValue</p></td>
<td><p>InventCostValue</p></td>
</tr>
<tr class="odd">
<td><p>InventCostVariances</p></td>
<td><p>InventCostVariances</p></td>
</tr>
<tr class="even">
<td><p>InventCountingList</p></td>
<td><p>InventCountingList</p></td>
</tr>
<tr class="odd">
<td><p>InventCountStatistics</p></td>
<td><p>InventCountStatistics</p></td>
</tr>
<tr class="even">
<td><p>InventDimPhys</p></td>
<td><p>InventDimPhys</p></td>
</tr>
<tr class="odd">
<td><p>InventJournalTrans</p></td>
<td><p>InventJournalTrans</p></td>
</tr>
<tr class="even">
<td><p>InventJournalTrans_Tag</p></td>
<td><p>InventJournalTrans_Tag</p></td>
</tr>
<tr class="odd">
<td><p>InventJournalTransTransfer</p></td>
<td><p>InventJournalTransTransfer</p></td>
</tr>
<tr class="even">
<td><p>InventNonConformanceTable</p></td>
<td><p>InventNonConformanceTable</p></td>
</tr>
<tr class="odd">
<td><p>InventNonConformanceTag</p></td>
<td><p>InventNonConformanceTag</p></td>
</tr>
<tr class="even">
<td><p>InventOnhand</p></td>
<td><p>InventOnhand</p></td>
</tr>
<tr class="odd">
<td><p>InventOpenQtyCritical</p></td>
<td><p>InventOpenQtyCritical</p></td>
</tr>
<tr class="even">
<td><p>InventPriceOverview</p></td>
<td><p>InventPriceOverview</p></td>
</tr>
<tr class="odd">
<td><p>InventQuarantineOrder</p></td>
<td><p>InventQuarantineOrder</p></td>
</tr>
<tr class="even">
<td><p>InventSettlementAdjustment</p></td>
<td><p>InventSettlementAdjustment</p></td>
</tr>
<tr class="odd">
<td><p>InventStdCostConvCheck</p></td>
<td><p>InventStdCostConvCheck</p></td>
</tr>
<tr class="even">
<td><p>InventStdCostVariance</p></td>
<td><p>InventStdCostVariance</p></td>
</tr>
<tr class="odd">
<td><p>InventSumCritical</p></td>
<td><p>InventSumCritical</p></td>
</tr>
<tr class="even">
<td><p>InventTableOverview</p></td>
<td><p>InventTableOverview</p></td>
</tr>
<tr class="odd">
<td><p>InventTablePriceDiscount</p></td>
<td><p>InventTablePriceDiscount</p></td>
</tr>
<tr class="even">
<td><p>InventTableQuantity</p></td>
<td><p>InventTableQuantity</p></td>
</tr>
<tr class="odd">
<td><p>InventTestCertOfAnalysis</p></td>
<td><p>InventTestCertOfAnalysis</p></td>
</tr>
<tr class="even">
<td><p>InventTestCorrection</p></td>
<td><p>InventTestCorrection</p></td>
</tr>
<tr class="odd">
<td><p>InventTransferOrderOverview</p></td>
<td><p>InventTransferOrderOverview</p></td>
</tr>
<tr class="even">
<td><p>InventTransferReceive</p></td>
<td><p>InventTransferReceive</p></td>
</tr>
<tr class="odd">
<td><p>InventTransferShip</p></td>
<td><p>InventTransferShip</p></td>
</tr>
<tr class="even">
<td><p>WMSBillOfLading</p></td>
<td><p>WMSBillOfLading</p></td>
</tr>
<tr class="odd">
<td><p>WMSCheckABCZones</p></td>
<td><p>WMSCheckABCZones</p></td>
</tr>
<tr class="even">
<td><p>WMSJournalTrans</p></td>
<td><p>WMSJournalTrans</p></td>
</tr>
<tr class="odd">
<td><p>WMSLocationLabel</p></td>
<td><p>WMSLocationLabel</p></td>
</tr>
<tr class="even">
<td><p>WMSPalletList</p></td>
<td><p>WMSPalletList</p></td>
</tr>
<tr class="odd">
<td><p>WMSPalletNumber</p></td>
<td><p>WMSPalletNumber</p></td>
</tr>
<tr class="even">
<td><p>WMSPickingList</p></td>
<td><p>WMSPickingList</p></td>
</tr>
<tr class="odd">
<td><p>WMSPickingList_OrderPick</p></td>
<td><p>WMSPickingList_OrderPick</p></td>
</tr>
<tr class="even">
<td><p>WMSPickingLocations</p></td>
<td><p>WMSPickingLocations</p></td>
</tr>
<tr class="odd">
<td><p>WMSShipmentList</p></td>
<td><p>WMSShipmentList</p></td>
</tr>
<tr class="even">
<td><p>IndirectCostOverview</p></td>
<td><p>IndirectCostOverview</p></td>
</tr>
<tr class="odd">
<td><p>PBAConfiguratedItem</p></td>
<td><p>PBAConfiguratedItem</p></td>
</tr>
<tr class="even">
<td><p>PBAConsistOf</p></td>
<td><p>PBAConsistOf</p></td>
</tr>
<tr class="odd">
<td><p>ProdCalcTrans</p></td>
<td><p>ProdCalcTrans</p></td>
</tr>
<tr class="even">
<td><p>ProdFinishGoodsInProgress</p></td>
<td><p>ProdFinishGoodsInProgress</p></td>
</tr>
<tr class="odd">
<td><p>ProdIndirectCostInProgress</p></td>
<td><p>ProdIndirectCostInProgress</p></td>
</tr>
<tr class="even">
<td><p>ProdOverview</p></td>
<td><p>ProdOverview</p></td>
</tr>
<tr class="odd">
<td><p>ProdPicklist</p></td>
<td><p>ProdPicklist</p></td>
</tr>
<tr class="even">
<td><p>ProdRawmaterialInProgress</p></td>
<td><p>ProdRawmaterialInProgress</p></td>
</tr>
<tr class="odd">
<td><p>ProdReport</p></td>
<td><p>ProdReport</p></td>
</tr>
<tr class="even">
<td><p>ProdResourcesInProgress</p></td>
<td><p>ProdResourcesInProgress</p></td>
</tr>
<tr class="odd">
<td><p>ProdRouteCard</p></td>
<td><p>ProdRouteCard</p></td>
</tr>
<tr class="even">
<td><p>ProdRouteJob</p></td>
<td><p>ProdRouteJob</p></td>
</tr>
<tr class="odd">
<td><p>SMAServiceOrderMargin</p></td>
<td><p>SMAServiceOrderMargin</p></td>
</tr>
<tr class="even">
<td><p>SMAWorkNote</p></td>
<td><p>SMAWorkNote</p></td>
</tr>
<tr class="odd">
<td><p>JmgAbsenceCalendar</p></td>
<td><p>JmgPlannedAbsence</p></td>
</tr>
<tr class="even">
<td><p>JmgAbsenceColumn</p></td>
<td><p>JmgAbsence</p></td>
</tr>
<tr class="odd">
<td><p>JmgEmplCard</p></td>
<td><p>JmgWorkerCard</p></td>
</tr>
<tr class="even">
<td><p>JmgEmployeeReport</p></td>
<td><p>JmgEmployee</p></td>
</tr>
<tr class="odd">
<td><p>JmgEmployeeTimeSpec</p></td>
<td><p>Jmgpayspec</p></td>
</tr>
<tr class="even">
<td><p>JmgEmplSignedIn</p></td>
<td><p>JmgEmplSignedIn</p></td>
</tr>
<tr class="odd">
<td><p>JmgFlexBalance</p></td>
<td><p>JmgFlexBalance</p></td>
</tr>
<tr class="even">
<td><p>JmgFlexCheck</p></td>
<td><p>JmgFlexCheck</p></td>
</tr>
<tr class="odd">
<td><p>JmgIndirectActivity</p></td>
<td><p>JmgIndirectActivity</p></td>
</tr>
<tr class="even">
<td><p>JmgIpcBarcode</p></td>
<td><p>JmgIpcBarcode</p></td>
</tr>
<tr class="odd">
<td><p>JmgIpcStat</p></td>
<td><p>JmgAbsenceStatistics</p></td>
</tr>
<tr class="even">
<td><p>JmgPayAgreement</p></td>
<td><p>JmgPayAggreement</p></td>
</tr>
<tr class="odd">
<td><p>JmgPayStatTrans</p></td>
<td><p>JmgPayStatTrans</p></td>
</tr>
<tr class="even">
<td><p>JmgProfile</p></td>
<td><p>JmgProfileDaily and JmgProfileWeek</p></td>
</tr>
<tr class="odd">
<td><p>JmgProjBarcode</p></td>
<td><p>JmgProjBarcode</p></td>
</tr>
<tr class="even">
<td><p>JmgWorkPlanner_Employee</p></td>
<td><p>JmgWorkPlanner_Employee</p></td>
</tr>
<tr class="odd">
<td><p>JmgWorkPlanner_Profile</p></td>
<td><p>JmgWorkPlanner_Profile</p></td>
</tr>
</tbody>
</table>


### Report Mapping to a Non-Reporting Services Implementation

The following table provides a mapping of reports from Microsoft Dynamics AX 2009 to a similar representation of data in Microsoft Dynamics AX 2012 in the form of list pages or export to Excel functionality from a form.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Microsoft Dynamics AX 2009 Report Name</p></th>
<th><p>Microsoft Dynamics AX 2012 Implementation Type</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>SysUtilElementsLog</p></td>
<td><p>Export to Excel</p></td>
</tr>
<tr class="even">
<td><p>SysUpgradeEstimate</p></td>
<td><p>Export to Excel</p></td>
</tr>
<tr class="odd">
<td><p>EmplReportAdvance_RU</p></td>
<td><p>Export to Excel</p></td>
</tr>
<tr class="even">
<td><p>RLedgerSheetEngine_ActAdjustVend</p></td>
<td><p>Export to Excel</p></td>
</tr>
<tr class="odd">
<td><p>PurchInvoice4Paym_RU, PurchInvoice4PaymOriginal_RU, PurchInvoice4PaymCopy_RU</p></td>
<td><p>Export to Excel</p></td>
</tr>
<tr class="even">
<td><p>CustVendFacture_RU</p></td>
<td><p>Export to Excel</p></td>
</tr>
<tr class="odd">
<td><p>CustVendOutPaym_RU</p></td>
<td><p>Export to Excel</p></td>
</tr>
<tr class="even">
<td><p>SalesInvoice4Paym_RU, SalesInvoice4PaymOriginal_RU, SalesInvoice4PaymCopy_RU</p></td>
<td><p>Export to Excel</p></td>
</tr>
<tr class="odd">
<td><p>PurchInvoice_RU</p></td>
<td><p>Export to Excel</p></td>
</tr>
<tr class="even">
<td><p>RCashBook</p></td>
<td><p>Export to Excel</p></td>
</tr>
<tr class="odd">
<td><p>RCashDocJournal</p></td>
<td><p>Export to Excel</p></td>
</tr>
<tr class="even">
<td><p>RCashOrder_RU</p></td>
<td><p>Export to Excel</p></td>
</tr>
<tr class="odd">
<td><p>RAssetCollationStatement</p></td>
<td><p>Export to Excel</p></td>
</tr>
<tr class="even">
<td><p>RTax25Registers</p></td>
<td><p>Export to Excel</p></td>
</tr>
<tr class="odd">
<td><p>RTax25RegisterTrans</p></td>
<td><p>Export to Excel</p></td>
</tr>
<tr class="even">
<td><p>LedgerBalanceSheetDimPrint6111_IL</p></td>
<td><p>Export to Excel</p></td>
</tr>
<tr class="odd">
<td><p>RPayAlimonySheetReport</p></td>
<td><p>Export to Excel</p></td>
</tr>
<tr class="even">
<td><p>RPayDepositJournalReport</p></td>
<td><p>Export to Excel</p></td>
</tr>
<tr class="odd">
<td><p>RPaySheetListReport</p></td>
<td><p>Export to Excel</p></td>
</tr>
<tr class="even">
<td><p>RPaySheetReport</p></td>
<td><p>Export to Excel</p></td>
</tr>
<tr class="odd">
<td><p>RPaySickListReport</p></td>
<td><p>Export to Excel</p></td>
</tr>
<tr class="even">
<td><p>SalesSupplyCapacity</p></td>
<td><p>ListPage</p></td>
</tr>
</tbody>
</table>

