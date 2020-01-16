---
title: Accounting supervisor security role (LedgerAccountingSupervisor)
TOCTitle: Accounting supervisor security role (LedgerAccountingSupervisor)
ms:assetid: 60d033b2-1010-46b7-8316-4b40a28a6821
ms:mtpsurl: https://technet.microsoft.com/library/Hh527097(v=AX.60)
ms:contentKeyID: 37823149
author: Khairunj
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Accounting supervisor security role (LedgerAccountingSupervisor) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Accounting supervisor security role represents a user who reviews accounting process performance and enables the accounting process.

## Duties in Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack

By default, this security role is assigned the following duties in Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Duty name</p></th>
<th><p>Duty AOT name</p></th>
<th><p>Duty description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Approve closing transactions</p></td>
<td><p>LedgerClosingTransactionsApprove</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Approve fixed assets transactions</p></td>
<td><p>AssetFixedAssetsApprove</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Approve ledger transactions</p></td>
<td><p>LedgerLedgerTransactionsApprove</p></td>
<td><p>Approve ledger transactions</p></td>
</tr>
<tr class="even">
<td><p>Enable collections process</p></td>
<td><p>CollectionLetterCollectionsProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the collections process</p></td>
</tr>
<tr class="odd">
<td><p>Enable credit cards process</p></td>
<td><p>CreditCardCreditCardsProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the credit cards process</p></td>
</tr>
<tr class="even">
<td><p>Enable EU sales list process</p></td>
<td><p>TaxEUSalesListProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the EU sales list process</p></td>
</tr>
<tr class="odd">
<td><p>Enable fixed assets process</p></td>
<td><p>AssetFixedAssetsProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the fixed assets process</p></td>
</tr>
<tr class="even">
<td><p>Enable general ledger process</p></td>
<td><p>LedgerGeneralLedgerProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the general ledger process</p></td>
</tr>
<tr class="odd">
<td><p>Enable Intrastat process</p></td>
<td><p>TaxIntrastatProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the Intrastat process</p></td>
</tr>
<tr class="even">
<td><p>Enable invoice and cash process</p></td>
<td><p>CustInvoiceInvoiceAndCashProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the invoice and cash process</p></td>
</tr>
<tr class="odd">
<td><p>Enable invoice and payment process</p></td>
<td><p>VendInvoiceInvoicePaymentProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the invoice and payment process</p></td>
</tr>
<tr class="even">
<td><p>Enable sales taxes process</p></td>
<td><p>TaxSalesTaxesProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the sales taxes process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into bank account reconciliation status</p></td>
<td><p>BankBankAcctReconStatusInquire</p></td>
<td><p>Respond to inquiries about the status of bank account reconciliations</p></td>
</tr>
<tr class="even">
<td><p>Inquire into bank accounts master</p></td>
<td><p>BankBankAccountsInquire</p></td>
<td><p>Respond to inquiries about bank master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into bank transaction status</p></td>
<td><p>BankBankTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of bank transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into bill of exchange status</p></td>
<td><p>PaymBillOfExchangeStatusInquire</p></td>
<td><p>Respond to inquiries about the status of bills of exchange</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into budget check errors or warnings</p></td>
<td><p>BudgetBudgetCheckResultsInquire</p></td>
<td><p>Respond to inquiries about budget check results</p></td>
</tr>
<tr class="even">
<td><p>Inquire into budget master</p></td>
<td><p>BudgetBudgetsInquire</p></td>
<td><p>Respond to inquiries about budget master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into budget register entry status</p></td>
<td><p>BudgetBudgetTransStatusInquire</p></td>
<td><p>Respond to inquiries about the status of budget register entries</p></td>
</tr>
<tr class="even">
<td><p>Inquire into chart of account master</p></td>
<td><p>LedgerChartOfAccountsInquire</p></td>
<td><p>Respond to inquiries about chart of accounts</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into closing transaction status</p></td>
<td><p>LedgerClosingTransactionsStatusInquire</p></td>
<td><p>Respond to inquiries about the status of closing transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into customer invoice status</p></td>
<td><p>CustInvoiceCustomerInvoiceStatusInquire</p></td>
<td><p>Respond to inquiries about the status of customer invoices</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into customer payments status</p></td>
<td><p>PaymCustomerPaymentsStatusInquire</p></td>
<td><p>Respond to inquiries about the status of customer payments</p></td>
</tr>
<tr class="even">
<td><p>Inquire into EInvoice progress</p></td>
<td><p>EInvoiceInquire_MX</p></td>
<td><p>Inquire into EInvoice progress</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into EU sales list transaction status</p></td>
<td><p>TaxEUSalesListTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of EU sales list transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into fixed asset budgets</p></td>
<td><p>AssetFixedAssetBudgetsInquire</p></td>
<td><p>Respond to inquiries about fixed asset budget master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into fixed asset policies</p></td>
<td><p>AssetFixedAssetPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the fixed asset process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into fixed asset reference data</p></td>
<td><p>AssetFixedAssetReferenceDataInquire</p></td>
<td><p>Respond to inquiries about fixed asset reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into fixed asset transaction status</p></td>
<td><p>AssetFixedAssetTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of fixed asset transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into fixed assets</p></td>
<td><p>AssetFixedAssetsInquire</p></td>
<td><p>Respond to inquiries about fixed assets master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into general ledger policies</p></td>
<td><p>LedgerGeneralLedgerPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the general ledger process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into general ledger reference data</p></td>
<td><p>LedgerGeneralLedgerReferenceDataInquire</p></td>
<td><p>Respond to inquiries about general ledger reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into Intrastat policies</p></td>
<td><p>TaxIntrastatPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the Intrastat process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into Intrastat reference data</p></td>
<td><p>TaxIntrastatReferenceDataInquire</p></td>
<td><p>Respond to inquiries about Intrastat reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into Intrastat transaction status</p></td>
<td><p>TaxIntrastatTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of Intrastat transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into invoice and cash reference data</p></td>
<td><p>CustInvoiceInvoiceAndCashRefDataInquire</p></td>
<td><p>Respond to inquiries about invoice and cash reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into invoice and payment policies</p></td>
<td><p>VendInvoiceInvoicePaymentPoliciesInquir</p></td>
<td><p>Respond to inquiries about policies governing the invoice and payment process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into invoice and payment process reference data</p></td>
<td><p>VendInvoiceInvoicePaymntProcessRefDataI</p></td>
<td><p>Respond to inquiries about invoice and payment process reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into journals and transaction status</p></td>
<td><p>LedgerJournalsTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of journals and transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into promissory note status</p></td>
<td><p>PaymPromissoryNoteStatusInquire</p></td>
<td><p>Respond to inquiries about the status of promissory notes</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into sales commissions master</p></td>
<td><p>CustInvoiceSalesCommissionsInquire</p></td>
<td><p>Respond to inquiries about commission master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into sales tax policies</p></td>
<td><p>TaxSalesTaxPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the sales tax process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into sales tax process reference data</p></td>
<td><p>TaxSalesTaxProcessReferenceDataInquire</p></td>
<td><p>Respond to inquiries about sales tax process reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into sales tax transaction status</p></td>
<td><p>TaxSalesTaxTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of sales tax transactions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into vendor invoice status</p></td>
<td><p>VendInvoiceVendorInvoiceStatusInquire</p></td>
<td><p>Respond to inquiries about the status of vendor invoices</p></td>
</tr>
<tr class="even">
<td><p>Inquire into vendor master</p></td>
<td><p>VendVendorMasterInquire</p></td>
<td><p>Respond to inquiries about vendor master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into vendor payment status</p></td>
<td><p>PaymVendorPaymentStatusInquire</p></td>
<td><p>Respond to inquiries about the status of vendor payments</p></td>
</tr>
<tr class="even">
<td><p>Maintain chart of accounts master</p></td>
<td><p>LedgerChartOfAccountsMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain closing transactions</p></td>
<td><p>LedgerClosingTransactionsMaintain</p></td>
<td><p>Document and record financial closing business events</p></td>
</tr>
<tr class="even">
<td><p>Maintain cost master</p></td>
<td><p>CostingVersionCostMasterMaintain</p></td>
<td><p>Maintain prices and costing versions</p></td>
</tr>
<tr class="odd">
<td><p>Maintain fixed asset transactions</p></td>
<td><p>AssetFixedAssetTransactionsMaintain</p></td>
<td><p>Document and record fixed asset business events</p></td>
</tr>
<tr class="even">
<td><p>Maintain fixed assets</p></td>
<td><p>AssetFixedAssetsMaintain</p></td>
<td><p>Maintain fixed assets</p></td>
</tr>
<tr class="odd">
<td><p>Maintain journals and transactions</p></td>
<td><p>LedgerJournalsAndTransactionsMaintain</p></td>
<td><p>Document and record journal transactions</p></td>
</tr>
<tr class="even">
<td><p>Maintain packing materials</p></td>
<td><p>InventPackMaterialsMaintain</p></td>
<td><p>Document and record packing materials</p></td>
</tr>
<tr class="odd">
<td><p>Maintain sales commissions master</p></td>
<td><p>CustInvoiceSalesCommissionsMaintain</p></td>
<td><p>Document and record sales commissions master information</p></td>
</tr>
<tr class="even">
<td><p>Review bank management process performance</p></td>
<td><p>BankBankManagementProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the bank management process</p></td>
</tr>
<tr class="odd">
<td><p>Review budget control process performance</p></td>
<td><p>BudgetBudgetControlProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the budget control process</p></td>
</tr>
<tr class="even">
<td><p>Review budget process performance</p></td>
<td><p>BudgetBudgetProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the budget process</p></td>
</tr>
<tr class="odd">
<td><p>Review compliance process performance</p></td>
<td><p>ComplianceMgmtComplianceProcPerfReview</p></td>
<td><p>Monitor, analyze, and improve the compliance process</p></td>
</tr>
<tr class="even">
<td><p>Review general ledger process performance</p></td>
<td><p>LedgerGeneralLedgerProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the general ledger process</p></td>
</tr>
<tr class="odd">
<td><p>Review general ledger process performance through the role center</p></td>
<td><p>LedgerRoleCenterGLProcessPerfReview</p></td>
<td><p>Review general ledger process performance through the role center.</p></td>
</tr>
<tr class="even">
<td><p>Review invoice and payment process performance</p></td>
<td><p>VendInvoiceInvoicePaymentProcPerfReview</p></td>
<td><p>Monitor, analyze, and improve the invoice and payment process</p></td>
</tr>
<tr class="odd">
<td><p>Role center URL redirection</p></td>
<td><p>EPHomePageView</p></td>
<td><p>Enable redirection from generic role center URL</p></td>
</tr>
</tbody>
</table>


## Duties in Microsoft Dynamics AX 2012 R2

By default, this security role is assigned the following duties in Microsoft Dynamics AX 2012 R2.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Duty name</p></th>
<th><p>Duty AOT Name</p></th>
<th><p>Duty description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Approve closing transactions</p></td>
<td><p>LedgerClosingTransactionsApprove</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Approve fixed assets transactions</p></td>
<td><p>AssetFixedAssetsApprove</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Approve ledger transactions</p></td>
<td><p>LedgerLedgerTransactionsApprove</p></td>
<td><p>Approve ledger transactions</p></td>
</tr>
<tr class="even">
<td><p>Enable cash management process</p></td>
<td><p>CashManagementProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the cash management process</p></td>
</tr>
<tr class="odd">
<td><p>Enable collections process</p></td>
<td><p>CollectionLetterCollectionsProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the collections process</p></td>
</tr>
<tr class="even">
<td><p>Enable credit cards process</p></td>
<td><p>CreditCardCreditCardsProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the credit cards process</p></td>
</tr>
<tr class="odd">
<td><p>Enable deferral management process</p></td>
<td><p>RDeferralsProcessEnable</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Enable EU sales list process</p></td>
<td><p>TaxEUSalesListProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the EU sales list process</p></td>
</tr>
<tr class="odd">
<td><p>Enable financial reports generator</p></td>
<td><p>RRGEnable</p></td>
<td><p>Set up templates, report format, and other information to enable the financial reports generator</p></td>
</tr>
<tr class="even">
<td><p>Enable fixed assets process</p></td>
<td><p>AssetFixedAssetsProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the fixed assets process</p></td>
</tr>
<tr class="odd">
<td><p>Enable general ledger process</p></td>
<td><p>LedgerGeneralLedgerProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the general ledger process</p></td>
</tr>
<tr class="even">
<td><p>Enable Intrastat process</p></td>
<td><p>TaxIntrastatProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the Intrastat process</p></td>
</tr>
<tr class="odd">
<td><p>Enable invoice and cash process</p></td>
<td><p>CustInvoiceInvoiceAndCashProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the invoice and cash process</p></td>
</tr>
<tr class="even">
<td><p>Enable invoice and payment process</p></td>
<td><p>VendInvoiceInvoicePaymentProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the invoice and payment process</p></td>
</tr>
<tr class="odd">
<td><p>Enable reversal of unrealized VAT</p></td>
<td><p>TaxReversalOfUnrealizdVATEnable</p></td>
<td><p>Post reversal of unrealized VAT to realized VAT when tax invoice has been received</p></td>
</tr>
<tr class="even">
<td><p>Enable sales taxes process</p></td>
<td><p>TaxSalesTaxesProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the sales taxes process</p></td>
</tr>
<tr class="odd">
<td><p>Enable the fixed asset process for Russian fixed assets</p></td>
<td><p>RassetProcessManagementEnable</p></td>
<td><p>Set up fixed asset information to enable the fixed asset process for Russian fixed assets</p></td>
</tr>
<tr class="even">
<td><p>Enable VAT process</p></td>
<td><p>TaxVATProcessEnable_RU</p></td>
<td><p>Set up VAT information to enable the VAT process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about accounting data</p></td>
<td><p>LedgerRRGGInquire</p></td>
<td><p>Respond to inquiries about accounting data</p></td>
</tr>
<tr class="even">
<td><p>Inquire about cash accounts</p></td>
<td><p>CashAccountsReview_RU</p></td>
<td><p>Respond to inquiries about cash accounts</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about customs duty data</p></td>
<td><p>CustomsDutyInquire_RU</p></td>
<td><p>Respond to inquiries about customs duty data</p></td>
</tr>
<tr class="even">
<td><p>Inquire about deferrals</p></td>
<td><p>RDeferralsInquire</p></td>
<td><p>Respond to inquiries about deferrals</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about electronic documents</p></td>
<td><p>LedgerRRGEInquire</p></td>
<td><p>Respond to inquires about electronic documents</p></td>
</tr>
<tr class="even">
<td><p>Inquire about fixed asset journals for Russia</p></td>
<td><p>InquireJournalsFA_RU</p></td>
<td><p>Respond to inquiries about fixed asset journals in Russia</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about fixed asset taxes for Russia</p></td>
<td><p>InquireTaxesFA_RU</p></td>
<td><p>Respond to inquiries about fixed asset taxes in Russia</p></td>
</tr>
<tr class="even">
<td><p>Inquire about fixed assets in Russia</p></td>
<td><p>InquireFA_RU</p></td>
<td><p>Respond to inquiries about fixed assets in Russia</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about incoming factures</p></td>
<td><p>FactureIncomingInquire_RU</p></td>
<td><p>Respond to inquiries about incoming factures</p></td>
</tr>
<tr class="even">
<td><p>Inquire about outgoing factures</p></td>
<td><p>FactureOutgoingInquire_RU</p></td>
<td><p>Respond to inquiries about outgoing factures</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about payment status for customer invoices</p></td>
<td><p>CustInvoice4PaymInquire_RU</p></td>
<td><p>Respond to inquiries about payment status for customer invoices</p></td>
</tr>
<tr class="even">
<td><p>Inquire about payment status for vendor invoices</p></td>
<td><p>VendInvoice4paymentStatusInquire_RU</p></td>
<td><p>Respond to inquiries about payment status for vendor invoices</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about prepayment factures</p></td>
<td><p>FacturePrepaymInquire_RU</p></td>
<td><p>Respond to inquiries about prepayment factures</p></td>
</tr>
<tr class="even">
<td><p>Inquire about tax accounting reference data</p></td>
<td><p>RTax25ReferenceDataInquire</p></td>
<td><p>Respond to inquiries about tax accounting reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about translation setup and sessions</p></td>
<td><p>RTSLTranslationInquire</p></td>
<td><p>Respond to inquiries about translation setup and sessions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into additional information related to cash accounts</p></td>
<td><p>CashAccountsAdditionalDataInquire</p></td>
<td><p>Respond to inquiries about the status of additional data related to cash accounts</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into bank account reconciliation status</p></td>
<td><p>BankBankAcctReconStatusInquire</p></td>
<td><p>Respond to inquiries about the status of bank account reconciliations</p></td>
</tr>
<tr class="even">
<td><p>Inquire into bank accounts master</p></td>
<td><p>BankBankAccountsInquire</p></td>
<td><p>Respond to inquiries about bank master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into bank transaction status</p></td>
<td><p>BankBankTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of bank transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into bill of exchange status</p></td>
<td><p>PaymBillOfExchangeStatusInquire</p></td>
<td><p>Respond to inquiries about the status of bills of exchange</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into budget check errors or warnings</p></td>
<td><p>BudgetBudgetCheckResultsInquire</p></td>
<td><p>Respond to inquiries about budget check results</p></td>
</tr>
<tr class="even">
<td><p>Inquire into budget master</p></td>
<td><p>BudgetBudgetsInquire</p></td>
<td><p>Respond to inquiries about budget master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into budget register entry status</p></td>
<td><p>BudgetBudgetTransStatusInquire</p></td>
<td><p>Respond to inquiries about the status of budget register entries</p></td>
</tr>
<tr class="even">
<td><p>Inquire into cash accounts</p></td>
<td><p>CashAccountsInquire</p></td>
<td><p>Respond to inquiries about cash accounts data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into cash transaction status</p></td>
<td><p>CashTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of cash transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into chart of account master</p></td>
<td><p>LedgerChartOfAccountsInquire</p></td>
<td><p>Respond to inquiries about chart of accounts</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into closing transaction status</p></td>
<td><p>LedgerClosingTransactionsStatusInquire</p></td>
<td><p>Respond to inquiries about the status of closing transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into customer consolidated invoice</p></td>
<td><p>CustConsolidatedInvoiceInquire_JP</p></td>
<td><p>Inquire into customer consolidated invoice</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into customer invoice status</p></td>
<td><p>CustInvoiceCustomerInvoiceStatusInquire</p></td>
<td><p>Respond to inquiries about the status of customer invoices</p></td>
</tr>
<tr class="even">
<td><p>Inquire into customer payments status</p></td>
<td><p>PaymCustomerPaymentsStatusInquire</p></td>
<td><p>Respond to inquiries about the status of customer payments</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into deferral transactions</p></td>
<td><p>RDeferralsTransInquire</p></td>
<td><p>Respond to inquiries about deferral transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into EInvoice progress</p></td>
<td><p>EInvoiceInquire_MX</p></td>
<td><p>Inquire into EInvoice progress</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into EU sales list transaction status</p></td>
<td><p>TaxEUSalesListTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of EU sales list transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into fixed asset budgets</p></td>
<td><p>AssetFixedAssetBudgetsInquire</p></td>
<td><p>Respond to inquiries about fixed asset budget master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into fixed asset policies</p></td>
<td><p>AssetFixedAssetPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the fixed asset process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into fixed asset reference data</p></td>
<td><p>AssetFixedAssetReferenceDataInquire</p></td>
<td><p>Respond to inquiries about fixed asset reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into fixed asset transaction status</p></td>
<td><p>AssetFixedAssetTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of fixed asset transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into fixed assets</p></td>
<td><p>AssetFixedAssetsInquire</p></td>
<td><p>Respond to inquiries about fixed assets master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into general ledger policies</p></td>
<td><p>LedgerGeneralLedgerPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the general ledger process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into general ledger reference data</p></td>
<td><p>LedgerGeneralLedgerReferenceDataInquire</p></td>
<td><p>Respond to inquiries about general ledger reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into Intrastat policies</p></td>
<td><p>TaxIntrastatPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the Intrastat process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into Intrastat reference data</p></td>
<td><p>TaxIntrastatReferenceDataInquire</p></td>
<td><p>Respond to inquiries about Intrastat reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into Intrastat transaction status</p></td>
<td><p>TaxIntrastatTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of Intrastat transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into invoice and cash reference data</p></td>
<td><p>CustInvoiceInvoiceAndCashRefDataInquire</p></td>
<td><p>Respond to inquiries about invoice and cash reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into invoice and payment policies</p></td>
<td><p>VendInvoiceInvoicePaymentPoliciesInquir</p></td>
<td><p>Respond to inquiries about policies governing the invoice and payment process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into invoice and payment process reference data</p></td>
<td><p>VendInvoiceInvoicePaymntProcessRefDataI</p></td>
<td><p>Respond to inquiries about invoice and payment process reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into journals and transaction status</p></td>
<td><p>LedgerJournalsTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of journals and transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into JP sales tax report</p></td>
<td><p>SalesTaxReportInquire_JP</p></td>
<td><p>Inquire into JP sales tax report</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into project master</p></td>
<td><p>ProjProjectMasterInquire</p></td>
<td><p>Respond to inquiries about project master information</p></td>
</tr>
<tr class="even">
<td><p>Inquire into promissory note status</p></td>
<td><p>PaymPromissoryNoteStatusInquire</p></td>
<td><p>Respond to inquiries about the status of promissory notes</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into sales commissions master</p></td>
<td><p>CustInvoiceSalesCommissionsInquire</p></td>
<td><p>Respond to inquiries about commission master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into sales tax policies</p></td>
<td><p>TaxSalesTaxPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the sales tax process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into sales tax process reference data</p></td>
<td><p>TaxSalesTaxProcessReferenceDataInquire</p></td>
<td><p>Respond to inquiries about sales tax process reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into sales tax transaction status</p></td>
<td><p>TaxSalesTaxTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of sales tax transactions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into vendor internal invoices</p></td>
<td><p>TaxVendInternalInvoiceInquiry</p></td>
<td><p>Respond to inquiries about vendor internal invoices created for EU purchases</p></td>
</tr>
<tr class="even">
<td><p>Inquire into vendor invoice status</p></td>
<td><p>VendInvoiceVendorInvoiceStatusInquire</p></td>
<td><p>Respond to inquiries about the status of vendor invoices</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into vendor master</p></td>
<td><p>VendVendorMasterInquire</p></td>
<td><p>Respond to inquiries about vendor master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into vendor payment status</p></td>
<td><p>PaymVendorPaymentStatusInquire</p></td>
<td><p>Respond to inquiries about the status of vendor payments</p></td>
</tr>
<tr class="odd">
<td><p>Maintain cash accounts</p></td>
<td><p>CashAccountsMaintain</p></td>
<td><p>Maintain cash accounts</p></td>
</tr>
<tr class="even">
<td><p>Maintain chart of accounts master</p></td>
<td><p>LedgerChartOfAccountsMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain closing transactions</p></td>
<td><p>LedgerClosingTransactionsMaintain</p></td>
<td><p>Document and record financial closing business events</p></td>
</tr>
<tr class="even">
<td><p>Maintain cost master</p></td>
<td><p>CostingVersionCostMasterMaintain</p></td>
<td><p>Maintain prices and costing versions</p></td>
</tr>
<tr class="odd">
<td><p>Maintain electronic documents</p></td>
<td><p>RRGEMAintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain fixed asset transactions</p></td>
<td><p>AssetFixedAssetTransactionsMaintain</p></td>
<td><p>Document and record fixed asset business events</p></td>
</tr>
<tr class="odd">
<td><p>Maintain fixed assets</p></td>
<td><p>AssetFixedAssetsMaintain</p></td>
<td><p>Maintain fixed assets</p></td>
</tr>
<tr class="even">
<td><p>Maintain journals and transactions</p></td>
<td><p>LedgerJournalsAndTransactionsMaintain</p></td>
<td><p>Document and record journal transactions</p></td>
</tr>
<tr class="odd">
<td><p>Maintain packing materials</p></td>
<td><p>InventPackMaterialsMaintain</p></td>
<td><p>Document and record packing materials</p></td>
</tr>
<tr class="even">
<td><p>Maintain periodic settlement and unsettlement</p></td>
<td><p>MaintainAutoSettleReverse_RU</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain purchase complementary invoices</p></td>
<td><p>PurchComplementaryInvoiceMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain sales commissions master</p></td>
<td><p>CustInvoiceSalesCommissionsMaintain</p></td>
<td><p>Document and record sales commissions master information</p></td>
</tr>
<tr class="odd">
<td><p>Maintain sales complementary invoices</p></td>
<td><p>SalesComplementaryInvoiceMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain tax branches</p></td>
<td><p>TaxBranchMaintain</p></td>
<td><p>View Tax Branch dimension details when creating dimensions</p></td>
</tr>
<tr class="odd">
<td><p>Maintain tax fiscal documents</p></td>
<td><p>TaxFiscalDocumentMaintain_BR</p></td>
<td><p>Create and update tax fiscal documents</p></td>
</tr>
<tr class="even">
<td><p>Maintain vendor consolidated invoice</p></td>
<td><p>VendConsolidatedInvoiceMaintain_JP</p></td>
<td><p>Maintain vendor consolidated invoice</p></td>
</tr>
<tr class="odd">
<td><p>Review average VAT</p></td>
<td><p>TaxAverageVATReview</p></td>
<td><p>Review average VAT details via the average VAT report</p></td>
</tr>
<tr class="even">
<td><p>Review bank management process performance</p></td>
<td><p>BankBankManagementProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the bank management process</p></td>
</tr>
<tr class="odd">
<td><p>Review budget control process performance</p></td>
<td><p>BudgetBudgetControlProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the budget control process</p></td>
</tr>
<tr class="even">
<td><p>Review budget process performance</p></td>
<td><p>BudgetBudgetProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the budget process</p></td>
</tr>
<tr class="odd">
<td><p>Review compliance process performance</p></td>
<td><p>ComplianceMgmtComplianceProcPerfReview</p></td>
<td><p>Monitor, analyze, and improve the compliance process</p></td>
</tr>
<tr class="even">
<td><p>Review general ledger process performance</p></td>
<td><p>LedgerGeneralLedgerProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the general ledger process</p></td>
</tr>
<tr class="odd">
<td><p>Review general ledger process performance through the role center</p></td>
<td><p>LedgerRoleCenterGLProcessPerfReview</p></td>
<td><p>Review general ledger process performance through the role center.</p></td>
</tr>
<tr class="even">
<td><p>Review invoice and payment process performance</p></td>
<td><p>VendInvoiceInvoicePaymentProcPerfReview</p></td>
<td><p>Monitor, analyze, and improve the invoice and payment process</p></td>
</tr>
<tr class="odd">
<td><p>Review unrealized VAT</p></td>
<td><p>TaxUnrealizdVATRemainingReview</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Role center URL redirection</p></td>
<td><p>EPHomePageView</p></td>
<td><p>Enable redirection from generic role center URL</p></td>
</tr>
<tr class="odd">
<td><p>View budget plans</p></td>
<td><p>BudgetPlanView</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>View fiscal document source texts</p></td>
<td><p>FiscalDocumentSourceTextView_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>View purchase complementary invoices</p></td>
<td><p>PurchComplementaryInvoiceInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>View sales complementary invoices</p></td>
<td><p>SalesComplementaryInvoiceInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>View tax fiscal documents</p></td>
<td><p>TaxFiscalDocumentInquire_BR</p></td>
<td><p>View tax fiscal documents</p></td>
</tr>
</tbody>
</table>


## Duties in Microsoft Dynamics AX 2012 R3

By default, this security role is assigned the following duties in Microsoft Dynamics AX 2012 R3.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Duty name</p></th>
<th><p>Duty AOT name</p></th>
<th><p>Duty description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Inquire into alcohol declaration data</p></td>
<td><p>AlcoholDeclarationDataInquire_RU</p></td>
<td><p>Respond to inquires about alcohol declaration data</p></td>
</tr>
<tr class="even">
<td><p>Enable alcohol declaration process</p></td>
<td><p>AlcoholDeclarationProcessEnable_RU</p></td>
<td><p>Set up reference data and journals to enable the alcohol declaration process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into fixed asset budgets</p></td>
<td><p>AssetFixedAssetBudgetsInquire</p></td>
<td><p>Respond to inquiries about fixed asset budget master data</p></td>
</tr>
<tr class="even">
<td><p>Manage fixed asset impairment</p></td>
<td><p>AssetFixedAssetImpairmentManage_JP</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into fixed asset policies</p></td>
<td><p>AssetFixedAssetPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the fixed asset process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into fixed asset reference data</p></td>
<td><p>AssetFixedAssetReferenceDataInquire</p></td>
<td><p>Respond to inquiries about fixed asset reference data</p></td>
</tr>
<tr class="odd">
<td><p>Approve fixed assets transactions</p></td>
<td><p>AssetFixedAssetsApprove</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into fixed assets</p></td>
<td><p>AssetFixedAssetsInquire</p></td>
<td><p>Respond to inquiries about fixed assets master data</p></td>
</tr>
<tr class="odd">
<td><p>Maintain fixed assets</p></td>
<td><p>AssetFixedAssetsMaintain</p></td>
<td><p>Maintain fixed assets</p></td>
</tr>
<tr class="even">
<td><p>Enable fixed assets process</p></td>
<td><p>AssetFixedAssetsProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the fixed assets process</p></td>
</tr>
<tr class="odd">
<td><p>Maintain fixed asset transactions</p></td>
<td><p>AssetFixedAssetTransactionsMaintain</p></td>
<td><p>Document and record fixed asset business events</p></td>
</tr>
<tr class="even">
<td><p>Inquire into fixed asset transaction status</p></td>
<td><p>AssetFixedAssetTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of fixed asset transactions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into bank accounts master</p></td>
<td><p>BankBankAccountsInquire</p></td>
<td><p>Respond to inquiries about bank master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into bank account reconciliation status</p></td>
<td><p>BankBankAcctReconStatusInquire</p></td>
<td><p>Respond to inquiries about the status of bank account reconciliations</p></td>
</tr>
<tr class="odd">
<td><p>Review bank management process performance</p></td>
<td><p>BankBankManagementProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the bank management process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into bank transaction status</p></td>
<td><p>BankBankTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of bank transactions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into budget check errors or warnings</p></td>
<td><p>BudgetBudgetCheckResultsInquire</p></td>
<td><p>Respond to inquiries about budget check results</p></td>
</tr>
<tr class="even">
<td><p>Review budget control process performance</p></td>
<td><p>BudgetBudgetControlProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the budget control process</p></td>
</tr>
<tr class="odd">
<td><p>Review budget process performance</p></td>
<td><p>BudgetBudgetProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the budget process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into budget master</p></td>
<td><p>BudgetBudgetsInquire</p></td>
<td><p>Respond to inquiries about budget master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into budget register entry status</p></td>
<td><p>BudgetBudgetTransStatusInquire</p></td>
<td><p>Respond to inquiries about the status of budget register entries</p></td>
</tr>
<tr class="even">
<td><p>View budget plans</p></td>
<td><p>BudgetPlanView</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into additional information related to cash accounts</p></td>
<td><p>CashAccountsAdditionalDataInquire</p></td>
<td><p>Respond to inquiries about the status of additional data related to cash accounts</p></td>
</tr>
<tr class="even">
<td><p>Inquire into cash accounts</p></td>
<td><p>CashAccountsInquire</p></td>
<td><p>Respond to inquiries about cash accounts data</p></td>
</tr>
<tr class="odd">
<td><p>Maintain cash accounts</p></td>
<td><p>CashAccountsMaintain</p></td>
<td><p>Maintain cash accounts</p></td>
</tr>
<tr class="even">
<td><p>Inquire about cash accounts</p></td>
<td><p>CashAccountsReview_RU</p></td>
<td><p>Respond to inquiries about cash accounts</p></td>
</tr>
<tr class="odd">
<td><p>Enable cash management process</p></td>
<td><p>CashManagementProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the cash management process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into cash transaction status</p></td>
<td><p>CashTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of cash transactions</p></td>
</tr>
<tr class="odd">
<td><p>Enable collections process</p></td>
<td><p>CollectionLetterCollectionsProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the collections process</p></td>
</tr>
<tr class="even">
<td><p>Review compliance process performance</p></td>
<td><p>ComplianceMgmtComplianceProcPerfReview</p></td>
<td><p>Monitor, analyze, and improve the compliance process</p></td>
</tr>
<tr class="odd">
<td><p>Maintain cost master</p></td>
<td><p>CostingVersionCostMasterMaintain</p></td>
<td><p>Maintain prices and costing versions</p></td>
</tr>
<tr class="even">
<td><p>Enable credit cards process</p></td>
<td><p>CreditCardCreditCardsProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the credit cards process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into customer consolidated invoice</p></td>
<td><p>CustConsolidatedInvoiceInquire_JP</p></td>
<td><p>Inquire into customer consolidated invoice</p></td>
</tr>
<tr class="even">
<td><p>Inquire about payment status for customer invoices</p></td>
<td><p>CustInvoice4PaymInquire_RU</p></td>
<td><p>Respond to inquiries about payment status for customer invoices</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into customer invoice status</p></td>
<td><p>CustInvoiceCustomerInvoiceStatusInquire</p></td>
<td><p>Respond to inquiries about the status of customer invoices</p></td>
</tr>
<tr class="even">
<td><p>Enable invoice and cash process</p></td>
<td><p>CustInvoiceInvoiceAndCashProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the invoice and cash process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into invoice and cash reference data</p></td>
<td><p>CustInvoiceInvoiceAndCashRefDataInquire</p></td>
<td><p>Respond to inquiries about invoice and cash reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into sales commissions master</p></td>
<td><p>CustInvoiceSalesCommissionsInquire</p></td>
<td><p>Respond to inquiries about commission master data</p></td>
</tr>
<tr class="odd">
<td><p>Maintain sales commissions master</p></td>
<td><p>CustInvoiceSalesCommissionsMaintain</p></td>
<td><p>Document and record sales commissions master information</p></td>
</tr>
<tr class="even">
<td><p>Inquire about customs duty data</p></td>
<td><p>CustomsDutyInquire_RU</p></td>
<td><p>Respond to inquiries about customs duty data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about customer overdue debt VAT journals</p></td>
<td><p>CustOverdueVATJournalInquire_W</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into EInvoice progress</p></td>
<td><p>EInvoiceInquire_MX</p></td>
<td><p>Inquire into EInvoice progress</p></td>
</tr>
<tr class="odd">
<td><p>Role center URL redirection</p></td>
<td><p>EPHomePageView</p></td>
<td><p>Enable redirection from generic role center URL</p></td>
</tr>
<tr class="even">
<td><p>Inquire about incoming factures</p></td>
<td><p>FactureIncomingInquire_RU</p></td>
<td><p>Respond to inquiries about incoming factures</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about outgoing factures</p></td>
<td><p>FactureOutgoingInquire_RU</p></td>
<td><p>Respond to inquiries about outgoing factures</p></td>
</tr>
<tr class="even">
<td><p>Inquire about prepayment factures</p></td>
<td><p>FacturePrepaymInquire_RU</p></td>
<td><p>Respond to inquiries about prepayment factures</p></td>
</tr>
<tr class="odd">
<td><p>View fiscal document source texts</p></td>
<td><p>FiscalDocumentSourceTextView_BR</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain imported content and FCI</p></td>
<td><p>ImportedContentPerItemMaintain_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire about fixed assets in Russia</p></td>
<td><p>InquireFA_RU</p></td>
<td><p>Respond to inquiries about fixed assets in Russia</p></td>
</tr>
<tr class="even">
<td><p>Inquire about fixed asset journals for Russia</p></td>
<td><p>InquireJournalsFA_RU</p></td>
<td><p>Respond to inquiries about fixed asset journals in Russia</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about fixed asset taxes for Russia</p></td>
<td><p>InquireTaxesFA_RU</p></td>
<td><p>Respond to inquiries about fixed asset taxes in Russia</p></td>
</tr>
<tr class="even">
<td><p>Maintain packing materials</p></td>
<td><p>InventPackMaterialsMaintain</p></td>
<td><p>Document and record packing materials</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into chart of account master</p></td>
<td><p>LedgerChartOfAccountsInquire</p></td>
<td><p>Respond to inquiries about chart of accounts</p></td>
</tr>
<tr class="even">
<td><p>Maintain chart of accounts master</p></td>
<td><p>LedgerChartOfAccountsMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Approve closing transactions</p></td>
<td><p>LedgerClosingTransactionsApprove</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain closing transactions</p></td>
<td><p>LedgerClosingTransactionsMaintain</p></td>
<td><p>Document and record financial closing business events</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into closing transaction status</p></td>
<td><p>LedgerClosingTransactionsStatusInquire</p></td>
<td><p>Respond to inquiries about the status of closing transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into general ledger policies</p></td>
<td><p>LedgerGeneralLedgerPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the general ledger process</p></td>
</tr>
<tr class="odd">
<td><p>Enable general ledger process</p></td>
<td><p>LedgerGeneralLedgerProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the general ledger process</p></td>
</tr>
<tr class="even">
<td><p>Review general ledger process performance</p></td>
<td><p>LedgerGeneralLedgerProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the general ledger process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into general ledger reference data</p></td>
<td><p>LedgerGeneralLedgerReferenceDataInquire</p></td>
<td><p>Respond to inquiries about general ledger reference data</p></td>
</tr>
<tr class="even">
<td><p>Maintain journals and transactions</p></td>
<td><p>LedgerJournalsAndTransactionsMaintain</p></td>
<td><p>Document and record journal transactions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into journals and transaction status</p></td>
<td><p>LedgerJournalsTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of journals and transactions</p></td>
</tr>
<tr class="even">
<td><p>Approve ledger transactions</p></td>
<td><p>LedgerLedgerTransactionsApprove</p></td>
<td><p>Approve ledger transactions</p></td>
</tr>
<tr class="odd">
<td><p>Review general ledger process performance through the role center</p></td>
<td><p>LedgerRoleCenterGLProcessPerfReview</p></td>
<td><p>Review general ledger process performance through the role center.</p></td>
</tr>
<tr class="even">
<td><p>Inquire about electronic documents</p></td>
<td><p>LedgerRRGEInquire</p></td>
<td><p>Respond to inquires about electronic documents</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about accounting data</p></td>
<td><p>LedgerRRGGInquire</p></td>
<td><p>Respond to inquiries about accounting data</p></td>
</tr>
<tr class="even">
<td><p>Maintain periodic settlement and unsettlement</p></td>
<td><p>MaintainAutoSettleReverse_RU</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into bill of exchange status</p></td>
<td><p>PaymBillOfExchangeStatusInquire</p></td>
<td><p>Respond to inquiries about the status of bills of exchange</p></td>
</tr>
<tr class="even">
<td><p>Inquire into customer payments status</p></td>
<td><p>PaymCustomerPaymentsStatusInquire</p></td>
<td><p>Respond to inquiries about the status of customer payments</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into customer positive payments</p></td>
<td><p>PaymCustPositivePayInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain positive payments</p></td>
<td><p>PaymPositivePayMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into promissory note status</p></td>
<td><p>PaymPromissoryNoteStatusInquire</p></td>
<td><p>Respond to inquiries about the status of promissory notes</p></td>
</tr>
<tr class="even">
<td><p>Inquire into vendor payment status</p></td>
<td><p>PaymVendorPaymentStatusInquire</p></td>
<td><p>Respond to inquiries about the status of vendor payments</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into vendor positive payments</p></td>
<td><p>PaymVendPositivePayInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into project master</p></td>
<td><p>ProjProjectMasterInquire</p></td>
<td><p>Respond to inquiries about project master information</p></td>
</tr>
<tr class="odd">
<td><p>View purchase complementary invoices</p></td>
<td><p>PurchComplementaryInvoiceInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain purchase complementary invoices</p></td>
<td><p>PurchComplementaryInvoiceMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Enable the fixed asset process for Russian fixed assets</p></td>
<td><p>RassetProcessManagementEnable</p></td>
<td><p>Set up fixed asset information to enable the fixed asset process for Russian fixed assets</p></td>
</tr>
<tr class="even">
<td><p>Inquire about deferrals</p></td>
<td><p>RDeferralsInquire</p></td>
<td><p>Respond to inquiries about deferrals</p></td>
</tr>
<tr class="odd">
<td><p>Enable deferral management process</p></td>
<td><p>RDeferralsProcessEnable</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into deferral transactions</p></td>
<td><p>RDeferralsTransInquire</p></td>
<td><p>Respond to inquiries about deferral transactions</p></td>
</tr>
<tr class="odd">
<td><p>Maintain electronic documents</p></td>
<td><p>RRGEMAintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Enable financial reports generator</p></td>
<td><p>RRGEnable</p></td>
<td><p>Set up templates, report format, and other information to enable the financial reports generator</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about translation setup and sessions</p></td>
<td><p>RTSLTranslationInquire</p></td>
<td><p>Respond to inquiries about translation setup and sessions</p></td>
</tr>
<tr class="even">
<td><p>View sales complementary invoices</p></td>
<td><p>SalesComplementaryInvoiceInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain sales complementary invoices</p></td>
<td><p>SalesComplementaryInvoiceMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into JP sales tax report</p></td>
<td><p>SalesTaxReportInquire_JP</p></td>
<td><p>Inquire into JP sales tax report</p></td>
</tr>
<tr class="odd">
<td><p>Review average VAT</p></td>
<td><p>TaxAverageVATReview</p></td>
<td><p>Review average VAT details via the average VAT report</p></td>
</tr>
<tr class="even">
<td><p>Maintain tax branches</p></td>
<td><p>TaxBranchMaintain</p></td>
<td><p>View Tax Branch dimension details when creating dimensions</p></td>
</tr>
<tr class="odd">
<td><p>Enable EU sales list process</p></td>
<td><p>TaxEUSalesListProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the EU sales list process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into EU sales list transaction status</p></td>
<td><p>TaxEUSalesListTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of EU sales list transactions</p></td>
</tr>
<tr class="odd">
<td><p>View tax fiscal documents</p></td>
<td><p>TaxFiscalDocumentInquire_BR</p></td>
<td><p>View tax fiscal documents</p></td>
</tr>
<tr class="even">
<td><p>Maintain tax fiscal documents</p></td>
<td><p>TaxFiscalDocumentMaintain_BR</p></td>
<td><p>Create and update tax fiscal documents</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into Intrastat policies</p></td>
<td><p>TaxIntrastatPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the Intrastat process</p></td>
</tr>
<tr class="even">
<td><p>Enable Intrastat process</p></td>
<td><p>TaxIntrastatProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the Intrastat process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into Intrastat reference data</p></td>
<td><p>TaxIntrastatReferenceDataInquire</p></td>
<td><p>Respond to inquiries about Intrastat reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into Intrastat transaction status</p></td>
<td><p>TaxIntrastatTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of Intrastat transactions</p></td>
</tr>
<tr class="odd">
<td><p>Enable reversal of unrealized VAT</p></td>
<td><p>TaxReversalOfUnrealizdVATEnable</p></td>
<td><p>Post reversal of unrealized VAT to realized VAT when tax invoice has been received</p></td>
</tr>
<tr class="even">
<td><p>Enable sales taxes process</p></td>
<td><p>TaxSalesTaxesProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the sales taxes process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into sales tax policies</p></td>
<td><p>TaxSalesTaxPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the sales tax process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into sales tax process reference data</p></td>
<td><p>TaxSalesTaxProcessReferenceDataInquire</p></td>
<td><p>Respond to inquiries about sales tax process reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into sales tax transaction status</p></td>
<td><p>TaxSalesTaxTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of sales tax transactions</p></td>
</tr>
<tr class="even">
<td><p>Review unrealized VAT</p></td>
<td><p>TaxUnrealizdVATRemainingReview</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Enable VAT process</p></td>
<td><p>TaxVATProcessEnable_RU</p></td>
<td><p>Set up VAT information to enable the VAT process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into vendor internal invoices</p></td>
<td><p>TaxVendInternalInvoiceInquiry</p></td>
<td><p>Respond to inquiries about vendor internal invoices created for EU purchases</p></td>
</tr>
<tr class="odd">
<td><p>Maintain vendor consolidated invoice</p></td>
<td><p>VendConsolidatedInvoiceMaintain_JP</p></td>
<td><p>Maintain vendor consolidated invoice</p></td>
</tr>
<tr class="even">
<td><p>Inquire about payment status for vendor invoices</p></td>
<td><p>VendInvoice4paymentStatusInquire_RU</p></td>
<td><p>Respond to inquiries about payment status for vendor invoices</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into invoice and payment policies</p></td>
<td><p>VendInvoiceInvoicePaymentPoliciesInquir</p></td>
<td><p>Respond to inquiries about policies governing the invoice and payment process</p></td>
</tr>
<tr class="even">
<td><p>Enable invoice and payment process</p></td>
<td><p>VendInvoiceInvoicePaymentProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the invoice and payment process</p></td>
</tr>
<tr class="odd">
<td><p>Review invoice and payment process performance</p></td>
<td><p>VendInvoiceInvoicePaymentProcPerfReview</p></td>
<td><p>Monitor, analyze, and improve the invoice and payment process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into invoice and payment process reference data</p></td>
<td><p>VendInvoiceInvoicePaymntProcessRefDataI</p></td>
<td><p>Respond to inquiries about invoice and payment process reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into vendor invoice status</p></td>
<td><p>VendInvoiceVendorInvoiceStatusInquire</p></td>
<td><p>Respond to inquiries about the status of vendor invoices</p></td>
</tr>
<tr class="even">
<td><p>Inquire about overdue vendor debt CIT and PIT journals</p></td>
<td><p>VendOverdueCITPITJournalInquire_W</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire about vendor overdue debt VAT journals</p></td>
<td><p>VendOverdueVATJournalInquire_W</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into vendor master</p></td>
<td><p>VendVendorMasterInquire</p></td>
<td><p>Respond to inquiries about vendor master data</p></td>
</tr>
</tbody>
</table>


## Privileges

By default, this security role is assigned the following privileges in Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Privilege name</p></th>
<th><p>Privilege AOT name</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Generate cash inflow versus cash outflow chart report</p></td>
<td><p>CustCashInflowvsCashOutflowGenerate</p></td>
</tr>
<tr class="even">
<td><p>Generate ledger transaction list report</p></td>
<td><p>LedgerTransListAccountGenerate</p></td>
</tr>
<tr class="odd">
<td><p>Generate trial balance report</p></td>
<td><p>LedgerTrialBalanceGenerate</p></td>
</tr>
<tr class="even">
<td><p>View projects</p></td>
<td><p>ProjTableView</p></td>
</tr>
<tr class="odd">
<td><p>View vendors</p></td>
<td><p>VendTableView</p></td>
</tr>
</tbody>
</table>


By default, this security role is assigned the following privilege in Microsoft Dynamics AX 2012 R2.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Privilege name</p></th>
<th><p>Privilege AOT name</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Maintain vendor tax invoice details</p></td>
<td><p>VendorTaxInvoiceDetailsMaintain</p></td>
</tr>
</tbody>
</table>


By default, this security role is assigned the following privilege in Microsoft Dynamics AX 2012 R3.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Privilege name</p></th>
<th><p>Privilege AOT name</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>View approved divergences</p></td>
<td><p>EFDocReceivedXmlMatchingApprovedView_BR</p></td>
</tr>
<tr class="even">
<td><p>Maintain vendor tax invoice details</p></td>
<td><p>VendorTaxInvoiceDetailsMaintain</p></td>
</tr>
</tbody>
</table>

  


