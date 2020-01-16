---
title: Financial controller security role (LedgerFinancialController)
TOCTitle: Financial controller security role (LedgerFinancialController)
ms:assetid: d4febd5d-c1f5-488f-8767-bf8621e25cfa
ms:mtpsurl: https://technet.microsoft.com/library/Hh527140(v=AX.60)
ms:contentKeyID: 37823191
author: Khairunj
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Financial controller security role (LedgerFinancialController) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Financial controller security role represents a user who reviews the performance of all accounting processes and enables those processes.

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
<td><p>Approve purchase requisitions</p></td>
<td><p>PurchReqPurchaseRequisitionApprove</p></td>
<td><p>Approve and authorize purchase requisitions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into audit policies</p></td>
<td><p>ComplianceMgmtAuditPoliciesInquire</p></td>
<td><p>Respond to inquiries about audit reference data</p></td>
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
<td><p>Inquire into bank letter of guarantee</p></td>
<td><p>BankLetterOfGuaranteeInquire</p></td>
<td><p>Respond to inquiries about bank letter of guarantee</p></td>
</tr>
<tr class="even">
<td><p>Inquire into bank management policies</p></td>
<td><p>BankBankManagementPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the bank management process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into bank management reference data</p></td>
<td><p>BankBankMgmtReferenceDataInquire</p></td>
<td><p>Respond to inquiries about bank management reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into bank transaction status</p></td>
<td><p>BankBankTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of bank transactions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into bill of exchange status</p></td>
<td><p>PaymBillOfExchangeStatusInquire</p></td>
<td><p>Respond to inquiries about the status of bills of exchange</p></td>
</tr>
<tr class="even">
<td><p>Inquire into budget check errors or warnings</p></td>
<td><p>BudgetBudgetCheckResultsInquire</p></td>
<td><p>Respond to inquiries about budget check results</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into budget master</p></td>
<td><p>BudgetBudgetsInquire</p></td>
<td><p>Respond to inquiries about budget master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into budget register entry status</p></td>
<td><p>BudgetBudgetTransStatusInquire</p></td>
<td><p>Respond to inquiries about the status of budget register entries</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into chart of account master</p></td>
<td><p>LedgerChartOfAccountsInquire</p></td>
<td><p>Respond to inquiries about chart of accounts</p></td>
</tr>
<tr class="even">
<td><p>Inquire into closing transaction status</p></td>
<td><p>LedgerClosingTransactionsStatusInquire</p></td>
<td><p>Respond to inquiries about the status of closing transactions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into collections status</p></td>
<td><p>CollectionLetterCollectionsStatusInquir</p></td>
<td><p>Respond to inquiries about the status of collections</p></td>
</tr>
<tr class="even">
<td><p>Inquire into compliance reference data</p></td>
<td><p>ComplianceMgmtComplianceRefDataInquire</p></td>
<td><p>Respond to inquiries about compliance reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into credit card processing</p></td>
<td><p>CreditCardCreditCardProcessingInquire</p></td>
<td><p>Respond to inquiries about credit card processing</p></td>
</tr>
<tr class="even">
<td><p>Inquire into customer invoice status</p></td>
<td><p>CustInvoiceCustomerInvoiceStatusInquire</p></td>
<td><p>Respond to inquiries about the status of customer invoices</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into customer master</p></td>
<td><p>CustCustomerMasterInquire</p></td>
<td><p>Respond to inquiries about customer master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into customer payments status</p></td>
<td><p>PaymCustomerPaymentsStatusInquire</p></td>
<td><p>Respond to inquiries about the status of customer payments</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into export letter of credit</p></td>
<td><p>BankExportLetterOfCreditInquire</p></td>
<td><p>Respond to inquiries about the status of export letters of credit</p></td>
</tr>
<tr class="even">
<td><p>Inquire into fixed asset budgets</p></td>
<td><p>AssetFixedAssetBudgetsInquire</p></td>
<td><p>Respond to inquiries about fixed asset budget master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into fixed asset transaction status</p></td>
<td><p>AssetFixedAssetTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of fixed asset transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into general ledger policies</p></td>
<td><p>LedgerGeneralLedgerPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the general ledger process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into general ledger reference data</p></td>
<td><p>LedgerGeneralLedgerReferenceDataInquire</p></td>
<td><p>Respond to inquiries about general ledger reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into import letter of credit</p></td>
<td><p>BankImportLetterOfCreditInquire</p></td>
<td><p>Respond to inquiries about the status of import letters of credit</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into inventory through the role center</p></td>
<td><p>LedgerRoleCenterInventoryInquire</p></td>
<td><p>Inquire into inventory through the role center</p></td>
</tr>
<tr class="even">
<td><p>Inquire into journals and transaction status</p></td>
<td><p>LedgerJournalsTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of journals and transactions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into promissory note status</p></td>
<td><p>PaymPromissoryNoteStatusInquire</p></td>
<td><p>Respond to inquiries about the status of promissory notes</p></td>
</tr>
<tr class="even">
<td><p>Inquire into purchase requisition</p></td>
<td><p>PurchReqPurchaseRequisitionInquire</p></td>
<td><p>Respond to inquiries about the status of purchase requisitions</p></td>
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
<td><p>Maintain derived financial hierarchy filters</p></td>
<td><p>LedgerDerivedFinancialHierarchyMaintain</p></td>
<td><p>Create, edit, or delete filters for derived financial hierarchies</p></td>
</tr>
<tr class="odd">
<td><p>Review bank management process performance</p></td>
<td><p>BankBankManagementProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the bank management process</p></td>
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
<td><p>Review collections process performance</p></td>
<td><p>CollectionLetterCollectionProcPerfRevie</p></td>
<td><p>Monitor, analyze, and improve the collections process</p></td>
</tr>
<tr class="odd">
<td><p>Review fixed assets process performance</p></td>
<td><p>AssetFixedAssetsProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the fixed assets process</p></td>
</tr>
<tr class="even">
<td><p>Review general ledger process performance</p></td>
<td><p>LedgerGeneralLedgerProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the general ledger process</p></td>
</tr>
<tr class="odd">
<td><p>Review invoice and cash process performance</p></td>
<td><p>CustInvoiceInvoiceAndCashProcPerfReview</p></td>
<td><p>Monitor, analyze, and improve the invoice and cash process</p></td>
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
<th><p>Duty AOT name</p></th>
<th><p>Duty description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Approve budget plans</p></td>
<td><p>BudgetPlanApprove</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Approve purchase requisitions</p></td>
<td><p>PurchReqPurchaseRequisitionApprove</p></td>
<td><p>Approve and authorize purchase requisitions</p></td>
</tr>
<tr class="odd">
<td><p>Enable financial reports generator</p></td>
<td><p>RRGEnable</p></td>
<td><p>Set up templates, report format, and other information to enable the financial reports generator</p></td>
</tr>
<tr class="even">
<td><p>Inquire about accounting data</p></td>
<td><p>InquireAccountingData_RU</p></td>
<td><p>Respond to inquiries about accounting data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about accounting data</p></td>
<td><p>LedgerRRGGInquire</p></td>
<td><p>Respond to inquiries about accounting data</p></td>
</tr>
<tr class="even">
<td><p>Inquire about electronic documents</p></td>
<td><p>LedgerRRGEInquire</p></td>
<td><p>Respond to inquiries about electronic documents</p></td>
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
<td><p>Inquire into audit policies</p></td>
<td><p>ComplianceMgmtAuditPoliciesInquire</p></td>
<td><p>Respond to inquiries about audit reference data</p></td>
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
<td><p>Inquire into bank letter of guarantee</p></td>
<td><p>BankLetterOfGuaranteeInquire</p></td>
<td><p>Respond to inquiries about bank letter of guarantee</p></td>
</tr>
<tr class="even">
<td><p>Inquire into bank management policies</p></td>
<td><p>BankBankManagementPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the bank management process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into bank management reference data</p></td>
<td><p>BankBankMgmtReferenceDataInquire</p></td>
<td><p>Respond to inquiries about bank management reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into bank transaction status</p></td>
<td><p>BankBankTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of bank transactions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into bill of exchange status</p></td>
<td><p>PaymBillOfExchangeStatusInquire</p></td>
<td><p>Respond to inquiries about the status of bills of exchange</p></td>
</tr>
<tr class="even">
<td><p>Inquire into budget check errors or warnings</p></td>
<td><p>BudgetBudgetCheckResultsInquire</p></td>
<td><p>Respond to inquiries about budget check results</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into budget master</p></td>
<td><p>BudgetBudgetsInquire</p></td>
<td><p>Respond to inquiries about budget master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into budget register entry status</p></td>
<td><p>BudgetBudgetTransStatusInquire</p></td>
<td><p>Respond to inquiries about the status of budget register entries</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into cash management reference data</p></td>
<td><p>CashManagementReferenceDataInquire</p></td>
<td><p>Respond to inquiries about cash management process reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into cash transaction status</p></td>
<td><p>CashTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of cash transactions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into chart of account master</p></td>
<td><p>LedgerChartOfAccountsInquire</p></td>
<td><p>Respond to inquiries about chart of accounts</p></td>
</tr>
<tr class="even">
<td><p>Inquire into closing transaction status</p></td>
<td><p>LedgerClosingTransactionsStatusInquire</p></td>
<td><p>Respond to inquiries about the status of closing transactions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into collections status</p></td>
<td><p>CollectionLetterCollectionsStatusInquir</p></td>
<td><p>Respond to inquiries about the status of collections</p></td>
</tr>
<tr class="even">
<td><p>Inquire into compliance reference data</p></td>
<td><p>ComplianceMgmtComplianceRefDataInquire</p></td>
<td><p>Respond to inquiries about compliance reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into credit card processing</p></td>
<td><p>CreditCardCreditCardProcessingInquire</p></td>
<td><p>Respond to inquiries about credit card processing</p></td>
</tr>
<tr class="even">
<td><p>Inquire into customer invoice status</p></td>
<td><p>CustInvoiceCustomerInvoiceStatusInquire</p></td>
<td><p>Respond to inquiries about the status of customer invoices</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into customer master</p></td>
<td><p>CustCustomerMasterInquire</p></td>
<td><p>Respond to inquiries about customer master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into customer payments status</p></td>
<td><p>PaymCustomerPaymentsStatusInquire</p></td>
<td><p>Respond to inquiries about the status of customer payments</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into export letter of credit</p></td>
<td><p>BankExportLetterOfCreditInquire</p></td>
<td><p>Respond to inquiries about the status of export letters of credit</p></td>
</tr>
<tr class="even">
<td><p>Inquire into fixed asset budgets</p></td>
<td><p>AssetFixedAssetBudgetsInquire</p></td>
<td><p>Respond to inquiries about fixed asset budget master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into fixed asset transaction status</p></td>
<td><p>AssetFixedAssetTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of fixed asset transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into general ledger policies</p></td>
<td><p>LedgerGeneralLedgerPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the general ledger process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into general ledger reference data</p></td>
<td><p>LedgerGeneralLedgerReferenceDataInquire</p></td>
<td><p>Respond to inquiries about general ledger reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into import letter of credit</p></td>
<td><p>BankImportLetterOfCreditInquire</p></td>
<td><p>Respond to inquiries about the status of import letters of credit</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into inventory through the role center</p></td>
<td><p>LedgerRoleCenterInventoryInquire</p></td>
<td><p>Inquire into inventory through the role center</p></td>
</tr>
<tr class="even">
<td><p>Inquire into items receipt note</p></td>
<td><p>GoodsReceiptNoteInquiry_IN</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into journals and transaction status</p></td>
<td><p>LedgerJournalsTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of journals and transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into project master</p></td>
<td><p>ProjProjectMasterInquire</p></td>
<td><p>Respond to inquiries about project master information</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into promissory note status</p></td>
<td><p>PaymPromissoryNoteStatusInquire</p></td>
<td><p>Respond to inquiries about the status of promissory notes</p></td>
</tr>
<tr class="even">
<td><p>Inquire into purchase requisition</p></td>
<td><p>PurchReqPurchaseRequisitionInquire</p></td>
<td><p>Respond to inquiries about the status of purchase requisitions</p></td>
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
<td><p>Maintain budget planning configuration and processes</p></td>
<td><p>BudgetPlanningConfigProcessMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain budget plans</p></td>
<td><p>BudgetPlanMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain derived financial hierarchy filters</p></td>
<td><p>LedgerDerivedFinancialHierarchyMaintain</p></td>
<td><p>Create, edit, or delete filters for derived financial hierarchies</p></td>
</tr>
<tr class="odd">
<td><p>Maintain electronic documents</p></td>
<td><p>RRGEMAintain</p></td>
<td><p></p></td>
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
<td><p>Review collections process performance</p></td>
<td><p>CollectionLetterCollectionProcPerfRevie</p></td>
<td><p>Monitor, analyze, and improve the collections process</p></td>
</tr>
<tr class="even">
<td><p>Review fixed assets process performance</p></td>
<td><p>AssetFixedAssetsProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the fixed assets process</p></td>
</tr>
<tr class="odd">
<td><p>Review general ledger process performance</p></td>
<td><p>LedgerGeneralLedgerProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the general ledger process</p></td>
</tr>
<tr class="even">
<td><p>Review invoice and cash process performance</p></td>
<td><p>CustInvoiceInvoiceAndCashProcPerfReview</p></td>
<td><p>Monitor, analyze, and improve the invoice and cash process</p></td>
</tr>
<tr class="odd">
<td><p>Review invoice and payment process performance</p></td>
<td><p>VendInvoiceInvoicePaymentProcPerfReview</p></td>
<td><p>Monitor, analyze, and improve the invoice and payment process</p></td>
</tr>
<tr class="even">
<td><p>Role center URL redirection</p></td>
<td><p>EPHomePageView</p></td>
<td><p>Enable redirection from generic role center URL</p></td>
</tr>
<tr class="odd">
<td><p>View fiscal document source texts</p></td>
<td><p>FiscalDocumentSourceTextView_BR</p></td>
<td><p></p></td>
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
<td><p>Inquire into fixed asset budgets</p></td>
<td><p>AssetFixedAssetBudgetsInquire</p></td>
<td><p>Respond to inquiries about fixed asset budget master data</p></td>
</tr>
<tr class="odd">
<td><p>Review fixed assets process performance</p></td>
<td><p>AssetFixedAssetsProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the fixed assets process</p></td>
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
<td><p>Inquire into bank management policies</p></td>
<td><p>BankBankManagementPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the bank management process</p></td>
</tr>
<tr class="even">
<td><p>Review bank management process performance</p></td>
<td><p>BankBankManagementProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the bank management process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into bank management reference data</p></td>
<td><p>BankBankMgmtReferenceDataInquire</p></td>
<td><p>Respond to inquiries about bank management reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into bank transaction status</p></td>
<td><p>BankBankTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of bank transactions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into export letter of credit</p></td>
<td><p>BankExportLetterOfCreditInquire</p></td>
<td><p>Respond to inquiries about the status of export letters of credit</p></td>
</tr>
<tr class="even">
<td><p>Inquire into import letter of credit</p></td>
<td><p>BankImportLetterOfCreditInquire</p></td>
<td><p>Respond to inquiries about the status of import letters of credit</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into bank letter of guarantee</p></td>
<td><p>BankLetterOfGuaranteeInquire</p></td>
<td><p>Respond to inquiries about bank letter of guarantee</p></td>
</tr>
<tr class="even">
<td><p>Inquire into budget check errors or warnings</p></td>
<td><p>BudgetBudgetCheckResultsInquire</p></td>
<td><p>Respond to inquiries about budget check results</p></td>
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
<td><p>Inquire into budget master</p></td>
<td><p>BudgetBudgetsInquire</p></td>
<td><p>Respond to inquiries about budget master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into budget register entry status</p></td>
<td><p>BudgetBudgetTransStatusInquire</p></td>
<td><p>Respond to inquiries about the status of budget register entries</p></td>
</tr>
<tr class="odd">
<td><p>Approve budget plans</p></td>
<td><p>BudgetPlanApprove</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain budget plans</p></td>
<td><p>BudgetPlanMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain budget planning configuration and processes</p></td>
<td><p>BudgetPlanningConfigProcessMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into cash management reference data</p></td>
<td><p>CashManagementReferenceDataInquire</p></td>
<td><p>Respond to inquiries about cash management process reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into cash transaction status</p></td>
<td><p>CashTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of cash transactions</p></td>
</tr>
<tr class="even">
<td><p>Review collections process performance</p></td>
<td><p>CollectionLetterCollectionProcPerfRevie</p></td>
<td><p>Monitor, analyze, and improve the collections process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into collections status</p></td>
<td><p>CollectionLetterCollectionsStatusInquir</p></td>
<td><p>Respond to inquiries about the status of collections</p></td>
</tr>
<tr class="even">
<td><p>Inquire into audit policies</p></td>
<td><p>ComplianceMgmtAuditPoliciesInquire</p></td>
<td><p>Respond to inquiries about audit reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into compliance reference data</p></td>
<td><p>ComplianceMgmtComplianceRefDataInquire</p></td>
<td><p>Respond to inquiries about compliance reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into credit card processing</p></td>
<td><p>CreditCardCreditCardProcessingInquire</p></td>
<td><p>Respond to inquiries about credit card processing</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into customer master</p></td>
<td><p>CustCustomerMasterInquire</p></td>
<td><p>Respond to inquiries about customer master data</p></td>
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
<td><p>Review invoice and cash process performance</p></td>
<td><p>CustInvoiceInvoiceAndCashProcPerfReview</p></td>
<td><p>Monitor, analyze, and improve the invoice and cash process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about customer overdue debt VAT journals</p></td>
<td><p>CustOverdueVATJournalInquire_W</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Role center URL redirection</p></td>
<td><p>EPHomePageView</p></td>
<td><p>Enable redirection from generic role center URL</p></td>
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
<td><p>Inquire about prepayment factures</p></td>
<td><p>FacturePrepaymInquire_RU</p></td>
<td><p>Respond to inquiries about prepayment factures</p></td>
</tr>
<tr class="even">
<td><p>View fiscal document source texts</p></td>
<td><p>FiscalDocumentSourceTextView_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into items receipt note</p></td>
<td><p>GoodsReceiptNoteInquiry_IN</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire about accounting data</p></td>
<td><p>InquireAccountingData_RU</p></td>
<td><p>Respond to inquiries about accounting data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into chart of account master</p></td>
<td><p>LedgerChartOfAccountsInquire</p></td>
<td><p>Respond to inquiries about chart of accounts</p></td>
</tr>
<tr class="even">
<td><p>Inquire into closing transaction status</p></td>
<td><p>LedgerClosingTransactionsStatusInquire</p></td>
<td><p>Respond to inquiries about the status of closing transactions</p></td>
</tr>
<tr class="odd">
<td><p>Maintain derived financial hierarchy filters</p></td>
<td><p>LedgerDerivedFinancialHierarchyMaintain</p></td>
<td><p>Create, edit, or delete filters for derived financial hierarchies</p></td>
</tr>
<tr class="even">
<td><p>Inquire into general ledger policies</p></td>
<td><p>LedgerGeneralLedgerPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the general ledger process</p></td>
</tr>
<tr class="odd">
<td><p>Review general ledger process performance</p></td>
<td><p>LedgerGeneralLedgerProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the general ledger process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into general ledger reference data</p></td>
<td><p>LedgerGeneralLedgerReferenceDataInquire</p></td>
<td><p>Respond to inquiries about general ledger reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into journals and transaction status</p></td>
<td><p>LedgerJournalsTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of journals and transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into inventory through the role center</p></td>
<td><p>LedgerRoleCenterInventoryInquire</p></td>
<td><p>Inquire into inventory through the role center</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about electronic documents</p></td>
<td><p>LedgerRRGEInquire</p></td>
<td><p>Respond to inquires about electronic documents</p></td>
</tr>
<tr class="even">
<td><p>Inquire about accounting data</p></td>
<td><p>LedgerRRGGInquire</p></td>
<td><p>Respond to inquiries about accounting data</p></td>
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
<td><p>Approve purchase requisitions</p></td>
<td><p>PurchReqPurchaseRequisitionApprove</p></td>
<td><p>Approve and authorize purchase requisitions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into purchase requisition</p></td>
<td><p>PurchReqPurchaseRequisitionInquire</p></td>
<td><p>Respond to inquiries about the status of purchase requisitions</p></td>
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
<td><p>Inquire about payment status for vendor invoices</p></td>
<td><p>VendInvoice4paymentStatusInquire_RU</p></td>
<td><p>Respond to inquiries about payment status for vendor invoices</p></td>
</tr>
<tr class="even">
<td><p>Review invoice and payment process performance</p></td>
<td><p>VendInvoiceInvoicePaymentProcPerfReview</p></td>
<td><p>Monitor, analyze, and improve the invoice and payment process</p></td>
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
<td><p>View bank accounts</p></td>
<td><p>BankAccountTableView</p></td>
</tr>
<tr class="even">
<td><p>View projects</p></td>
<td><p>ProjTableView</p></td>
</tr>
</tbody>
</table>


By default, this security role is assigned the following privileges in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.

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
<td><p>Generate financial stock card report of Thailand</p></td>
<td><p>InventStockCardFinancialGenerate</p></td>
</tr>
<tr class="even">
<td><p>Generate physical stock card of Thailand</p></td>
<td><p>InventStockCardPhysicalGenerate</p></td>
</tr>
</tbody>
</table>

  


