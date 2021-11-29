---
title: Accounting manager security role (LedgerAccountingManager)
TOCTitle: Accounting manager security role (LedgerAccountingManager)
ms:assetid: ec66e2e4-e849-4090-b7fb-9df840bf20b4
ms:mtpsurl: https://technet.microsoft.com/library/Hh527149(v=AX.60)
ms:contentKeyID: 37823200
author: Khairunj
ms.author: daxcpft
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Accounting manager security role (LedgerAccountingManager) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Accounting manager security role represents a user who reviews accounting, customer invoice, vendor invoice, and payment process performance and enables those processes.

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
<td><p>Approve advanced ledger entry transactions</p></td>
<td><p>AdvancedLedgerEntryApprove</p></td>
<td><p>Approve advanced ledger entry business events</p></td>
</tr>
<tr class="even">
<td><p>Approve closing transactions</p></td>
<td><p>LedgerClosingTransactionsApprove</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Approve customer invoices</p></td>
<td><p>CustInvoiceCustomerInvoiceApprove</p></td>
<td><p>Approve customer invoices</p></td>
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
<td><p>Approve vendor invoices</p></td>
<td><p>VendInvoiceVendorInvoiceApprove</p></td>
<td><p>Approve vendor invoices</p></td>
</tr>
<tr class="odd">
<td><p>Enable cost accounting process</p></td>
<td><p>COSCostAccountingProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the cost accounting process</p></td>
</tr>
<tr class="even">
<td><p>Enable cost process</p></td>
<td><p>InventCostCostProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the cost process</p></td>
</tr>
<tr class="odd">
<td><p>Enable general ledger process</p></td>
<td><p>LedgerGeneralLedgerProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the general ledger process</p></td>
</tr>
<tr class="even">
<td><p>Enable inventory valuation process</p></td>
<td><p>InventStdCostInvValuationProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the inventory valuation process</p></td>
</tr>
<tr class="odd">
<td><p>Enable the global address book process</p></td>
<td><p>DirAddressBookProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the global address book process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into bank account reconciliation status</p></td>
<td><p>BankBankAcctReconStatusInquire</p></td>
<td><p>Respond to inquiries about the status of bank account reconciliations</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into bank accounts master</p></td>
<td><p>BankBankAccountsInquire</p></td>
<td><p>Respond to inquiries about bank master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into bank letter of guarantee</p></td>
<td><p>BankLetterOfGuaranteeInquire</p></td>
<td><p>Respond to inquiries about bank letter of guarantee</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into bank management policies</p></td>
<td><p>BankBankManagementPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the bank management process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into bank management reference data</p></td>
<td><p>BankBankMgmtReferenceDataInquire</p></td>
<td><p>Respond to inquiries about bank management reference data</p></td>
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
<td><p>Inquire into collections policies</p></td>
<td><p>CollectionLetterCollectPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the collections process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into collections reference data</p></td>
<td><p>CollectionLetterCollectRefDataInquire</p></td>
<td><p>Respond to inquiries about collections reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into collections status</p></td>
<td><p>CollectionLetterCollectionsStatusInquir</p></td>
<td><p>Respond to inquiries about the status of collections</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into contact master</p></td>
<td><p>smmContactMasterInquire</p></td>
<td><p>Respond to inquiries about contact master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into cost accounting calculation status</p></td>
<td><p>COSCostAccountingCalcStatusInquire</p></td>
<td><p>Inquire into status information within the process of cost accounting</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into cost accounting master</p></td>
<td><p>COSCostAccountingMasterInquire</p></td>
<td><p>Respond to inquiries about cost accounting master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into cost accounting status</p></td>
<td><p>COSCostAccountingStatusInquire</p></td>
<td><p>Respond to inquiries about the performance of the cost accounting process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into cost master</p></td>
<td><p>InventItemPriceCostMasterInquire</p></td>
<td><p>Respond to inquiries about cost master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into cost status</p></td>
<td><p>InventCostCostStatusInquire</p></td>
<td><p>Respond to inquiries about the performance of the cost process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into customer invoice status</p></td>
<td><p>CustInvoiceCustomerInvoiceStatusInquire</p></td>
<td><p>Respond to inquiries about the status of customer invoices</p></td>
</tr>
<tr class="even">
<td><p>Inquire into customer reference data</p></td>
<td><p>CustCustomerReferenceDataInquire</p></td>
<td><p>Respond to inquiries about customer master reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into EInvoice progress</p></td>
<td><p>EInvoiceInquire_MX</p></td>
<td><p>Inquire into EInvoice progress</p></td>
</tr>
<tr class="even">
<td><p>Inquire into EU sales list transaction status</p></td>
<td><p>TaxEUSalesListTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of EU sales list transactions</p></td>
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
<td><p>Inquire into import letter of credit</p></td>
<td><p>BankImportLetterOfCreditInquire</p></td>
<td><p>Respond to inquiries about the status of import letters of credit</p></td>
</tr>
<tr class="even">
<td><p>Inquire into Intrastat policies</p></td>
<td><p>TaxIntrastatPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the Intrastat process</p></td>
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
<td><p>Inquire into invoice and cash reference data</p></td>
<td><p>CustInvoiceInvoiceAndCashRefDataInquire</p></td>
<td><p>Respond to inquiries about invoice and cash reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into invoice and payment policies</p></td>
<td><p>VendInvoiceInvoicePaymentPoliciesInquir</p></td>
<td><p>Respond to inquiries about policies governing the invoice and payment process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into invoice and payment process reference data</p></td>
<td><p>VendInvoiceInvoicePaymntProcessRefDataI</p></td>
<td><p>Respond to inquiries about invoice and payment process reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into journals and transaction status</p></td>
<td><p>LedgerJournalsTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of journals and transactions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into packing materials progress</p></td>
<td><p>InventPackMaterialsProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the packing materials process</p></td>
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
<td><p>Inquire into vendor process</p></td>
<td><p>VendVendorProcessInquire</p></td>
<td><p>Respond to inquiries about vendor process</p></td>
</tr>
<tr class="odd">
<td><p>Maintain and configure organizational model</p></td>
<td><p>OMOrganizationsMaintain</p></td>
<td><p>Create or update organizations and organization hierarchies</p></td>
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
<td><p>Maintain cost accounting master</p></td>
<td><p>COSCostAccountingMasterMaintain</p></td>
<td><p>Maintain the monetary value of expenditures for services</p></td>
</tr>
<tr class="odd">
<td><p>Maintain cost master</p></td>
<td><p>CostingVersionCostMasterMaintain</p></td>
<td><p>Maintain prices and costing versions</p></td>
</tr>
<tr class="even">
<td><p>Maintain customer master</p></td>
<td><p>CustCustomersMaintain</p></td>
<td><p>Document and record customer master information</p></td>
</tr>
<tr class="odd">
<td><p>Maintain derived financial hierarchy filters</p></td>
<td><p>LedgerDerivedFinancialHierarchyMaintain</p></td>
<td></td>
</tr>
<tr class="even">
<td><p>Maintain fixed asset budget master from role center</p></td>
<td><p>AssetFixedAssetsTransRoleCenterMaintain</p></td>
<td><p></p></td>
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
<td><p>Review compliance process performance</p></td>
<td><p>ComplianceMgmtComplianceProcPerfReview</p></td>
<td><p>Monitor, analyze, and improve the compliance process</p></td>
</tr>
<tr class="even">
<td><p>Review cost accounting process</p></td>
<td><p>COSCostAccountingProcessReview</p></td>
<td><p>Monitor cost accounting ledger</p></td>
</tr>
<tr class="odd">
<td><p>Review cost accounting process performance</p></td>
<td><p>COSCostAccountingProcessPerfReview</p></td>
<td><p>Monitor cost accounting</p></td>
</tr>
<tr class="even">
<td><p>Review cost process performance</p></td>
<td><p>InventItemPriceCostProcessPerfReview</p></td>
<td><p>Monitor cost</p></td>
</tr>
<tr class="odd">
<td><p>Review credit cards process performance</p></td>
<td><p>CreditCardCreditCardsProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the credit cards process</p></td>
</tr>
<tr class="even">
<td><p>Review EU sales list process performance</p></td>
<td><p>TaxEUSalesListProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the EU sales list process</p></td>
</tr>
<tr class="odd">
<td><p>Review general ledger process performance</p></td>
<td><p>LedgerGeneralLedgerProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the general ledger process</p></td>
</tr>
<tr class="even">
<td><p>Review general ledger process performance through the role center</p></td>
<td><p>LedgerRoleCenterGLProcessPerfReview</p></td>
<td><p>Review general ledger process performance through the role center</p></td>
</tr>
<tr class="odd">
<td><p>Review inventory valuation process performance</p></td>
<td><p>InventValueInvValuationProcessPerfRevie</p></td>
<td><p>Monitor inventory valuation</p></td>
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
<td><p>Review purchase order process performance</p></td>
<td><p>PurchOrderProcessPerformanceReview</p></td>
<td><p>Monitor purchase orders</p></td>
</tr>
<tr class="odd">
<td><p>Review purchasing reports through the role center</p></td>
<td><p>ProcRoleCenterPurchProcessReview</p></td>
<td><p>Review purchasing reports through the role center</p></td>
</tr>
<tr class="even">
<td><p>Review sales taxes process performance</p></td>
<td><p>TaxSalesTaxesProcessPerfReview</p></td>
<td><p>Monitor sales taxes</p></td>
</tr>
<tr class="odd">
<td><p>Role center URL redirection</p></td>
<td><p>EPHomePageView</p></td>
<td><p>Enable redirection from generic role center URL</p></td>
</tr>
<tr class="even">
<td><p>Setup advanced ledger entry service</p></td>
<td><p>AdvancedLedgerEntryServiceMaintain</p></td>
<td><p>Setup advanced ledger entry service to enable the service operations</p></td>
</tr>
<tr class="odd">
<td><p>View advanced ledger entry process</p></td>
<td><p>AdvancedLedgerEntryView</p></td>
<td><p>View advanced ledger entry process in ledger</p></td>
</tr>
<tr class="even">
<td><p>View and maintain advanced ledger entry process</p></td>
<td><p>AdvancedLedgerEntryMaintain</p></td>
<td><p>View and maintain advanced ledger entry process in ledger</p></td>
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
<td><p>Activate tax depreciation process</p></td>
<td><p>AssetTaxDepreciationEnable</p></td>
<td><p>Manage the tax depreciation period to calculate depreciation</p></td>
</tr>
<tr class="even">
<td><p>Approve advanced ledger entry transactions</p></td>
<td><p>AdvancedLedgerEntryApprove</p></td>
<td><p>Approve advanced ledger entry business events</p></td>
</tr>
<tr class="odd">
<td><p>Approve closing transactions</p></td>
<td><p>LedgerClosingTransactionsApprove</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Approve customer invoices</p></td>
<td><p>CustInvoiceCustomerInvoiceApprove</p></td>
<td><p>Approve customer invoices</p></td>
</tr>
<tr class="odd">
<td><p>Approve fixed assets transactions</p></td>
<td><p>AssetFixedAssetsApprove</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Approve ledger transactions</p></td>
<td><p>LedgerLedgerTransactionsApprove</p></td>
<td><p>Approve ledger transactions</p></td>
</tr>
<tr class="odd">
<td><p>Approve vendor invoices</p></td>
<td><p>VendInvoiceVendorInvoiceApprove</p></td>
<td><p>Approve vendor invoices</p></td>
</tr>
<tr class="even">
<td><p>Enable cash management process</p></td>
<td><p>CashManagementProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the cash management process</p></td>
</tr>
<tr class="odd">
<td><p>Enable cost accounting process</p></td>
<td><p>COSCostAccountingProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the cost accounting process</p></td>
</tr>
<tr class="even">
<td><p>Enable cost process</p></td>
<td><p>InventCostCostProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the cost process</p></td>
</tr>
<tr class="odd">
<td><p>Enable deferral management process</p></td>
<td><p>RDeferralsProcessEnable</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Enable financial reports generator</p></td>
<td><p>RRGEnable</p></td>
<td><p>Set up templates, report format, and other information to enable the financial reports generator</p></td>
</tr>
<tr class="odd">
<td><p>Enable general ledger process</p></td>
<td><p>LedgerGeneralLedgerProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the general ledger process</p></td>
</tr>
<tr class="even">
<td><p>Enable inventory valuation process</p></td>
<td><p>InventStdCostInvValuationProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the inventory valuation process</p></td>
</tr>
<tr class="odd">
<td><p>Enable invoice and cash process</p></td>
<td><p>CustInvoiceInvoiceAndCashProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the invoice and cash process</p></td>
</tr>
<tr class="even">
<td><p>Enable reversal of unrealized VAT</p></td>
<td><p>TaxReversalOfUnrealizdVATEnable</p></td>
<td><p>Post reversal of unrealized VAT to realized VAT when tax invoice has been received</p></td>
</tr>
<tr class="odd">
<td><p>Enable the fixed asset process for Russian fixed assets</p></td>
<td><p>RassetProcessManagementEnable</p></td>
<td><p>Set up fixed asset information to enable the fixed asset process for Russian fixed assets</p></td>
</tr>
<tr class="even">
<td><p>Enable the global address book process</p></td>
<td><p>DirAddressBookProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the global address book process</p></td>
</tr>
<tr class="odd">
<td><p>Enable VAT process</p></td>
<td><p>TaxVATProcessEnable_RU</p></td>
<td><p>Set up VAT information to enable the VAT process</p></td>
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
<td><p>Inquire about advance holder accounts</p></td>
<td><p>AdvHoldersInquire_RU</p></td>
<td><p>Respond to inquiries about advance holder accounts</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about advance holder transactions</p></td>
<td><p>AdvHoldersTransactionsStatusInquire_RU</p></td>
<td><p>Respond to inquiries about advance holder transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire about cash accounts</p></td>
<td><p>CashAccountsReview_RU</p></td>
<td><p>Respond to inquiries about cash accounts</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about cash journals</p></td>
<td><p>CashJourInquire_RU</p></td>
<td><p>Respond to inquiries about cash journals</p></td>
</tr>
<tr class="even">
<td><p>Inquire about customs duty data</p></td>
<td><p>CustomsDutyInquire_RU</p></td>
<td><p>Respond to inquiries about customs duty data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about deferrals</p></td>
<td><p>RDeferralsInquire</p></td>
<td><p>Respond to inquiries about deferrals</p></td>
</tr>
<tr class="even">
<td><p>Inquire about electronic documents</p></td>
<td><p>LedgerRRGEInquire</p></td>
<td><p>Respond to inquires about electronic documents</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about export VAT processing</p></td>
<td><p>ExportVATInquire_RU</p></td>
<td><p>Respond to inquiries about export VAT processing</p></td>
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
<td><p>Inquire about fixed asset transactions in Russia</p></td>
<td><p>InquireFixedAssetTrans_RU</p></td>
<td><p>Respond to inquiries about fixed asset transactions in Russia</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about fixed assets in Russia</p></td>
<td><p>InquireFA_RU</p></td>
<td><p>Respond to inquiries about fixed assets in Russia</p></td>
</tr>
<tr class="even">
<td><p>Inquire about incoming factures</p></td>
<td><p>FactureIncomingInquire_RU</p></td>
<td><p>Respond to inquiries about incoming factures</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about outgoing factures</p></td>
<td><p>FactureOutgoingInquire</p></td>
<td><p>Respond to inquiries about outgoing factures</p></td>
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
<td><p>Inquire about purchase books</p></td>
<td><p>PurchBookInquire_RU</p></td>
<td><p>Respond to inquiries about purchase books</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about sales books</p></td>
<td><p>SalesBookInquire_RU</p></td>
<td><p>Respond to inquiries about sales books</p></td>
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
<td><p>Inquire into advanced reports</p></td>
<td><p>EmplAdvInquire_RU</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into bank account reconciliation status</p></td>
<td><p>BankBankAcctReconStatusInquire</p></td>
<td><p>Respond to inquiries about the status of bank account reconciliations</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into bank accounts master</p></td>
<td><p>BankBankAccountsInquire</p></td>
<td><p>Respond to inquiries about bank master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into bank letter of guarantee</p></td>
<td><p>BankLetterOfGuaranteeInquire</p></td>
<td><p>Respond to inquiries about bank letter of guarantee</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into bank management policies</p></td>
<td><p>BankBankManagementPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the bank management process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into bank management reference data</p></td>
<td><p>BankBankMgmtReferenceDataInquire</p></td>
<td><p>Respond to inquiries about bank management reference data</p></td>
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
<td><p>Inquire into CFOP</p></td>
<td><p>CFOPInquire_BR</p></td>
<td><p>Inquire into CFOP</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into chart of account master</p></td>
<td><p>LedgerChartOfAccountsInquire</p></td>
<td><p>Respond to inquiries about chart of accounts</p></td>
</tr>
<tr class="even">
<td><p>Inquire into Client-Bank payments</p></td>
<td><p>BankClientInquire_RU</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into closing transaction status</p></td>
<td><p>LedgerClosingTransactionsStatusInquire</p></td>
<td><p>Respond to inquiries about the status of closing transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into collections policies</p></td>
<td><p>CollectionLetterCollectPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the collections process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into collections reference data</p></td>
<td><p>CollectionLetterCollectRefDataInquire</p></td>
<td><p>Respond to inquiries about collections reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into collections status</p></td>
<td><p>CollectionLetterCollectionsStatusInquir</p></td>
<td><p>Respond to inquiries about the status of collections</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into contact master</p></td>
<td><p>smmContactMasterInquire</p></td>
<td><p>Respond to inquiries about contact master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into cost accounting calculation status</p></td>
<td><p>COSCostAccountingCalcStatusInquire</p></td>
<td><p>Inquire into status information within the process of cost accounting</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into cost accounting master</p></td>
<td><p>COSCostAccountingMasterInquire</p></td>
<td><p>Respond to inquiries about cost accounting master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into cost accounting status</p></td>
<td><p>COSCostAccountingStatusInquire</p></td>
<td><p>Respond to inquiries about the performance of the cost accounting process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into cost master</p></td>
<td><p>InventItemPriceCostMasterInquire</p></td>
<td><p>Respond to inquiries about cost master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into cost status</p></td>
<td><p>InventCostCostStatusInquire</p></td>
<td><p>Respond to inquiries about the performance of the cost process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into cust/vend prepayments</p></td>
<td><p>CustVendPrepaymentInquire_RU</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into customer invoice status</p></td>
<td><p>CustInvoiceCustomerInvoiceStatusInquire</p></td>
<td><p>Respond to inquiries about the status of customer invoices</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into customer reference data</p></td>
<td><p>CustCustomerReferenceDataInquire</p></td>
<td><p>Respond to inquiries about customer master reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into deferral transactions</p></td>
<td><p>RDeferralsTransInquire</p></td>
<td><p>Respond to inquiries about deferral transactions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into EInvoice progress</p></td>
<td><p>EInvoiceInquire_MX</p></td>
<td><p>Inquire into EInvoice progress</p></td>
</tr>
<tr class="even">
<td><p>Inquire into estimate project master</p></td>
<td><p>ProjEstimateProjectMasterInquire</p></td>
<td><p>Respond to inquiries about estimate project master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into EU sales list transaction status</p></td>
<td><p>TaxEUSalesListTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of EU sales list transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into export letter of credit</p></td>
<td><p>BankExportLetterOfCreditInquire</p></td>
<td><p>Respond to inquiries about the status of export letters of credit</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into fixed asset budgets</p></td>
<td><p>AssetFixedAssetBudgetsInquire</p></td>
<td><p>Respond to inquiries about fixed asset budget master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into fixed asset policies</p></td>
<td><p>AssetFixedAssetPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the fixed asset process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into fixed asset reference data</p></td>
<td><p>AssetFixedAssetReferenceDataInquire</p></td>
<td><p>Respond to inquiries about fixed asset reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into fixed asset transaction status</p></td>
<td><p>AssetFixedAssetTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of fixed asset transactions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into fixed assets</p></td>
<td><p>AssetFixedAssetsInquire</p></td>
<td><p>Respond to inquiries about fixed assets master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into fixed price projects revenue recognition</p></td>
<td><p>ProjFixedPriceRevenueRecognitionInquire</p></td>
<td><p>Respond to inquiries about fixed-price revenue recognition master information</p></td>
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
<td><p>Inquire into import letter of credit</p></td>
<td><p>BankImportLetterOfCreditInquire</p></td>
<td><p>Respond to inquiries about the status of import letters of credit</p></td>
</tr>
<tr class="even">
<td><p>Inquire into Intrastat policies</p></td>
<td><p>TaxIntrastatPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the Intrastat process</p></td>
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
<td><p>Inquire into invoice and cash policies</p></td>
<td><p>CustInvoiceInvoiceAndCashPoliciesInquir</p></td>
<td><p>Respond to inquiries about policies governing the invoice and cash process</p></td>
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
<td><p>Inquire into packing materials progress</p></td>
<td><p>InventPackMaterialsProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the packing materials process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into project category master</p></td>
<td><p>ProjProjectCategoriesMasterInquire</p></td>
<td><p>Respond to inquiries about project category master information</p></td>
</tr>
<tr class="even">
<td><p>Inquire into project groups master</p></td>
<td><p>ProjProjectGroupsMasterInquire</p></td>
<td><p>Respond to inquiries about project groups master information</p></td>
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
<td><p>Inquire into vendor process</p></td>
<td><p>VendVendorProcessInquire</p></td>
<td><p>Respond to inquiries about vendor process</p></td>
</tr>
<tr class="even">
<td><p>Inquire taxes matrix</p></td>
<td><p>TaxesMatrixInquire_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain advanced reports</p></td>
<td><p>EmplAdvMaintain_RU</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain and configure organizational model</p></td>
<td><p>OMOrganizationsMaintain</p></td>
<td><p>Create or update organizations and organization hierarchies</p></td>
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
<td><p>Maintain Client-Bank payments</p></td>
<td><p>BankClientMaintain_RU</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain closing transactions</p></td>
<td><p>LedgerClosingTransactionsMaintain</p></td>
<td><p>Document and record financial closing business events</p></td>
</tr>
<tr class="odd">
<td><p>Maintain correction letters</p></td>
<td><p>EFDocCorrectionLetterMaintain_BR</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain cost accounting master</p></td>
<td><p>COSCostAccountingMasterMaintain</p></td>
<td><p>Maintain the monetary value of expenditures for services, labor and products</p></td>
</tr>
<tr class="odd">
<td><p>Maintain cost master</p></td>
<td><p>CostingVersionCostMasterMaintain</p></td>
<td><p>Maintain prices and costing versions</p></td>
</tr>
<tr class="even">
<td><p>Maintain cust/vend prepayments</p></td>
<td><p>CustVendPrepaymentMaintain_RU</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain customer master</p></td>
<td><p>CustCustomersMaintain</p></td>
<td><p>Document and record customer master information</p></td>
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
<td><p>Maintain fiscal classification</p></td>
<td><p>TaxFiscalClassificationMaintain_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain fixed asset budget master from role center</p></td>
<td><p>AssetFixedAssetsTransRoleCenterMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain incoming factures</p></td>
<td><p>FactureIncomingProcessing</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain prepayment factures</p></td>
<td><p>FacturePrepaymProcessing</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain product type</p></td>
<td><p>InventProductTypeMaintain_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain service code</p></td>
<td><p>TaxServiceCodeMaintain_BR</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain tax branches</p></td>
<td><p>TaxBranchMaintain</p></td>
<td><p>View Tax Branch dimension details when creating dimensions</p></td>
</tr>
<tr class="odd">
<td><p>Maintain vendor master</p></td>
<td><p>VendVendorMasterMaintain</p></td>
<td><p>Maintain vendor master</p></td>
</tr>
<tr class="even">
<td><p>Review average VAT</p></td>
<td><p>TaxAverageVATReview</p></td>
<td><p>Review average VAT details via the average VAT report</p></td>
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
<td><p>Review compliance process performance</p></td>
<td><p>ComplianceMgmtComplianceProcPerfReview</p></td>
<td><p>Monitor, analyze, and improve the compliance process</p></td>
</tr>
<tr class="even">
<td><p>Review cost accounting process</p></td>
<td><p>COSCostAccountingProcessReview</p></td>
<td><p>Monitor cost accounting ledger</p></td>
</tr>
<tr class="odd">
<td><p>Review cost accounting process performance</p></td>
<td><p>COSCostAccountingProcessPerfReview</p></td>
<td><p>Monitor cost accounting</p></td>
</tr>
<tr class="even">
<td><p>Review cost process performance</p></td>
<td><p>InventItemPriceCostProcessPerfReview</p></td>
<td><p>Monitor cost</p></td>
</tr>
<tr class="odd">
<td><p>Review credit cards process performance</p></td>
<td><p>CreditCardCreditCardsProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the credit cards process</p></td>
</tr>
<tr class="even">
<td><p>Review EU sales list process performance</p></td>
<td><p>TaxEUSalesListProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the EU sales list process</p></td>
</tr>
<tr class="odd">
<td><p>Review general ledger process performance</p></td>
<td><p>LedgerGeneralLedgerProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the general ledger process</p></td>
</tr>
<tr class="even">
<td><p>Review general ledger process performance through the role center</p></td>
<td><p>LedgerRoleCenterGLProcessPerfReview</p></td>
<td><p>Review general ledger process performance through the role center.</p></td>
</tr>
<tr class="odd">
<td><p>Review inventory valuation process performance</p></td>
<td><p>InventValueInvValuationProcessPerfRevie</p></td>
<td><p>Monitor inventory valuation</p></td>
</tr>
<tr class="even">
<td><p>Review inventory valuation process performance (cur.)</p></td>
<td><p>InvValueInvValuatProcPerfSecCurReview_RU</p></td>
<td><p>Monitor inventory valuation in the second currency</p></td>
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
<td><p>Review purchase order process performance</p></td>
<td><p>PurchOrderProcessPerformanceReview</p></td>
<td><p>Monitor purchase orders</p></td>
</tr>
<tr class="even">
<td><p>Review purchasing reports through the role center</p></td>
<td><p>ProcRoleCenterPurchProcessReview</p></td>
<td><p>Review purchasing reports through the role center</p></td>
</tr>
<tr class="odd">
<td><p>Review sales taxes process performance</p></td>
<td><p>TaxSalesTaxesProcessPerfReview</p></td>
<td><p>Monitor sales taxes</p></td>
</tr>
<tr class="even">
<td><p>Review unrealized VAT</p></td>
<td><p>TaxUnrealizdVATRemainingReview</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Role center URL redirection</p></td>
<td><p>EPHomePageView</p></td>
<td><p>Enable redirection from generic role center URL</p></td>
</tr>
<tr class="even">
<td><p>Setup advanced ledger entry service</p></td>
<td><p>AdvancedLedgerEntryServiceMaintain</p></td>
<td><p>Setup advanced ledger entry service to enable the service operations</p></td>
</tr>
<tr class="odd">
<td><p>View advanced ledger entry process</p></td>
<td><p>AdvancedLedgerEntryView</p></td>
<td><p>View advanced ledger entry process in ledger</p></td>
</tr>
<tr class="even">
<td><p>View and maintain advanced ledger entry process</p></td>
<td><p>AdvancedLedgerEntryMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>View Brazilian parameters</p></td>
<td><p>BrazilParametersInquire_BR</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>View budget planning configuration and processes</p></td>
<td><p>BudgetPlanningConfigProcessView</p></td>
<td><p></p></td>
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
<td><p>Approve advanced ledger entry transactions</p></td>
<td><p>AdvancedLedgerEntryApprove</p></td>
<td><p>Approve advanced ledger entry business events</p></td>
</tr>
<tr class="even">
<td><p>View and maintain advanced ledger entry process</p></td>
<td><p>AdvancedLedgerEntryMaintain</p></td>
<td><p>View and maintain advanced ledger entry process in ledger</p></td>
</tr>
<tr class="odd">
<td><p>Setup advanced ledger entry service</p></td>
<td><p>AdvancedLedgerEntryServiceMaintain</p></td>
<td><p>Setup advanced ledger entry service to enable the service operations</p></td>
</tr>
<tr class="even">
<td><p>View advanced ledger entry process</p></td>
<td><p>AdvancedLedgerEntryView</p></td>
<td><p>View advanced ledger entry process in ledger</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about advance holder accounts</p></td>
<td><p>AdvHoldersInquire_RU</p></td>
<td><p>Respond to inquiries about advance holder accounts</p></td>
</tr>
<tr class="even">
<td><p>Inquire about advance holder transactions</p></td>
<td><p>AdvHoldersTransactionsStatusInquire_RU</p></td>
<td><p>Respond to inquiries about advance holder transactions</p></td>
</tr>
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
<td><p>Maintain fixed asset budget master from role center</p></td>
<td><p>AssetFixedAssetsTransRoleCenterMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into fixed asset transaction status</p></td>
<td><p>AssetFixedAssetTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of fixed asset transactions</p></td>
</tr>
<tr class="odd">
<td><p>Activate tax depreciation process</p></td>
<td><p>AssetTaxDepreciationEnable</p></td>
<td><p>Manage the tax depreciation period to calculate depreciation</p></td>
</tr>
<tr class="even">
<td><p>Inquire into bank accounts master</p></td>
<td><p>BankBankAccountsInquire</p></td>
<td><p>Respond to inquiries about bank master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into bank account reconciliation status</p></td>
<td><p>BankBankAcctReconStatusInquire</p></td>
<td><p>Respond to inquiries about the status of bank account reconciliations</p></td>
</tr>
<tr class="even">
<td><p>Inquire into bank management policies</p></td>
<td><p>BankBankManagementPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the bank management process</p></td>
</tr>
<tr class="odd">
<td><p>Review bank management process performance</p></td>
<td><p>BankBankManagementProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the bank management process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into bank management reference data</p></td>
<td><p>BankBankMgmtReferenceDataInquire</p></td>
<td><p>Respond to inquiries about bank management reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into bank transaction status</p></td>
<td><p>BankBankTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of bank transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into Client-Bank payments</p></td>
<td><p>BankClientInquire_RU</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain Client-Bank payments</p></td>
<td><p>BankClientMaintain_RU</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into export letter of credit</p></td>
<td><p>BankExportLetterOfCreditInquire</p></td>
<td><p>Respond to inquiries about the status of export letters of credit</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into import letter of credit</p></td>
<td><p>BankImportLetterOfCreditInquire</p></td>
<td><p>Respond to inquiries about the status of import letters of credit</p></td>
</tr>
<tr class="even">
<td><p>Inquire into bank letter of guarantee</p></td>
<td><p>BankLetterOfGuaranteeInquire</p></td>
<td><p>Respond to inquiries about bank letter of guarantee</p></td>
</tr>
<tr class="odd">
<td><p>View Brazilian parameters</p></td>
<td><p>BrazilParametersInquire_BR</p></td>
<td><p></p></td>
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
<td><p>View budget planning configuration and processes</p></td>
<td><p>BudgetPlanningConfigProcessView</p></td>
<td><p></p></td>
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
<td><p>Inquire about cash journals</p></td>
<td><p>CashJourInquire_RU</p></td>
<td><p>Respond to inquiries about cash journals</p></td>
</tr>
<tr class="even">
<td><p>Enable cash management process</p></td>
<td><p>CashManagementProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the cash management process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into cash transaction status</p></td>
<td><p>CashTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of cash transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into CFOP</p></td>
<td><p>CFOPInquire_BR</p></td>
<td><p>Inquire into CFOP</p></td>
</tr>
<tr class="odd">
<td><p>Review collections process performance</p></td>
<td><p>CollectionLetterCollectionProcPerfRevie</p></td>
<td><p>Monitor, analyze, and improve the collections process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into collections status</p></td>
<td><p>CollectionLetterCollectionsStatusInquir</p></td>
<td><p>Respond to inquiries about the status of collections</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into collections policies</p></td>
<td><p>CollectionLetterCollectPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the collections process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into collections reference data</p></td>
<td><p>CollectionLetterCollectRefDataInquire</p></td>
<td><p>Respond to inquiries about collections reference data</p></td>
</tr>
<tr class="odd">
<td><p>Review compliance process performance</p></td>
<td><p>ComplianceMgmtComplianceProcPerfReview</p></td>
<td><p>Monitor, analyze, and improve the compliance process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into cost accounting calculation status</p></td>
<td><p>COSCostAccountingCalcStatusInquire</p></td>
<td><p>Inquire into status information within the process of cost accounting</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into cost accounting master</p></td>
<td><p>COSCostAccountingMasterInquire</p></td>
<td><p>Respond to inquiries about cost accounting master data</p></td>
</tr>
<tr class="even">
<td><p>Maintain cost accounting master</p></td>
<td><p>COSCostAccountingMasterMaintain</p></td>
<td><p>Maintain the monetary value of expenditures for services</p></td>
</tr>
<tr class="odd">
<td><p>Enable cost accounting process</p></td>
<td><p>COSCostAccountingProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the cost accounting process</p></td>
</tr>
<tr class="even">
<td><p>Review cost accounting process performance</p></td>
<td><p>COSCostAccountingProcessPerfReview</p></td>
<td><p>Monitor cost accounting</p></td>
</tr>
<tr class="odd">
<td><p>Review cost accounting process</p></td>
<td><p>COSCostAccountingProcessReview</p></td>
<td><p>Monitor cost accounting ledger</p></td>
</tr>
<tr class="even">
<td><p>Inquire into cost accounting status</p></td>
<td><p>COSCostAccountingStatusInquire</p></td>
<td><p>Respond to inquiries about the performance of the cost accounting process</p></td>
</tr>
<tr class="odd">
<td><p>Maintain cost master</p></td>
<td><p>CostingVersionCostMasterMaintain</p></td>
<td><p>Maintain prices and costing versions</p></td>
</tr>
<tr class="even">
<td><p>Configure costing data for a product</p></td>
<td><p>CostProductCostingDataMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Review credit cards process performance</p></td>
<td><p>CreditCardCreditCardsProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the credit cards process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into customer reference data</p></td>
<td><p>CustCustomerReferenceDataInquire</p></td>
<td><p>Respond to inquiries about customer master reference data</p></td>
</tr>
<tr class="odd">
<td><p>Maintain customer master</p></td>
<td><p>CustCustomersMaintain</p></td>
<td><p>Document and record customer master information</p></td>
</tr>
<tr class="even">
<td><p>Inquire about payment status for customer invoices</p></td>
<td><p>CustInvoice4PaymInquire_RU</p></td>
<td><p>Respond to inquiries about payment status for customer invoices</p></td>
</tr>
<tr class="odd">
<td><p>Approve customer invoices</p></td>
<td><p>CustInvoiceCustomerInvoiceApprove</p></td>
<td><p>Approve customer invoices</p></td>
</tr>
<tr class="even">
<td><p>Inquire into customer invoice status</p></td>
<td><p>CustInvoiceCustomerInvoiceStatusInquire</p></td>
<td><p>Respond to inquiries about the status of customer invoices</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into invoice and cash policies</p></td>
<td><p>CustInvoiceInvoiceAndCashPoliciesInquir</p></td>
<td><p>Respond to inquiries about policies governing the invoice and cash process</p></td>
</tr>
<tr class="even">
<td><p>Enable invoice and cash process</p></td>
<td><p>CustInvoiceInvoiceAndCashProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the invoice and cash process</p></td>
</tr>
<tr class="odd">
<td><p>Review invoice and cash process performance</p></td>
<td><p>CustInvoiceInvoiceAndCashProcPerfReview</p></td>
<td><p>Monitor, analyze, and improve the invoice and cash process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into invoice and cash reference data</p></td>
<td><p>CustInvoiceInvoiceAndCashRefDataInquire</p></td>
<td><p>Respond to inquiries about invoice and cash reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into sales commissions master</p></td>
<td><p>CustInvoiceSalesCommissionsInquire</p></td>
<td><p>Respond to inquiries about commission master data</p></td>
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
<td><p>Inquire into cust/vend prepayments</p></td>
<td><p>CustVendPrepaymentInquire_RU</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain cust/vend prepayments</p></td>
<td><p>CustVendPrepaymentMaintain_RU</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain dimension configuration for integrating applications</p></td>
<td><p>DimIntegrationConfigurationMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Enable the global address book process</p></td>
<td><p>DirAddressBookProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the global address book process</p></td>
</tr>
<tr class="even">
<td><p>Maintain correction letters</p></td>
<td><p>EFDocCorrectionLetterMaintain_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Enable receipt electronic fiscal document process</p></td>
<td><p>EFDocumentReceivedXMLEnable_BR</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into receipt electronic fiscal document</p></td>
<td><p>EFDocumentReceivedXMLInquire_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Match a vendor invoice to an NF-e XML document</p></td>
<td><p>EFDocumentReceivedXmlMatchingApprove_BR</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>View the discrepancies between vendor invoice values and the received XML values</p></td>
<td><p>EFDocumentReceivedXmlMatchingInquire_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into EInvoice progress</p></td>
<td><p>EInvoiceInquire_MX</p></td>
<td><p>Inquire into EInvoice progress</p></td>
</tr>
<tr class="even">
<td><p>Inquire into advanced reports</p></td>
<td><p>EmplAdvInquire_RU</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain advanced reports</p></td>
<td><p>EmplAdvMaintain_RU</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Role center URL redirection</p></td>
<td><p>EPHomePageView</p></td>
<td><p>Enable redirection from generic role center URL</p></td>
</tr>
<tr class="odd">
<td><p>ExchangeRate Service</p></td>
<td><p>ExchangeRateServiceOperations</p></td>
<td><p>Exchange Rate Service operations</p></td>
</tr>
<tr class="even">
<td><p>Inquire about export VAT processing</p></td>
<td><p>ExportVATInquire_RU</p></td>
<td><p>Respond to inquiries about export VAT processing</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about incoming factures</p></td>
<td><p>FactureIncomingInquire_RU</p></td>
<td><p>Respond to inquiries about incoming factures</p></td>
</tr>
<tr class="even">
<td><p>Maintain incoming factures</p></td>
<td><p>FactureIncomingProcessing</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire about outgoing factures</p></td>
<td><p>FactureOutgoingInquire</p></td>
<td><p>Respond to inquiries about outgoing factures</p></td>
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
<td><p>Maintain prepayment factures</p></td>
<td><p>FacturePrepaymProcessing</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>View fiscal document source texts</p></td>
<td><p>FiscalDocumentSourceTextView_BR</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into organizational process</p></td>
<td><p>HcmOrganizationalProcessInquire</p></td>
<td><p>Respond to inquiries about organizational reference data</p></td>
</tr>
<tr class="odd">
<td><p>Maintain imported content and FCI</p></td>
<td><p>ImportedContentPerItemMaintain_BR</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire about accounting data</p></td>
<td><p>InquireAccountingData_RU</p></td>
<td><p>Respond to inquiries about accounting data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about fixed assets in Russia</p></td>
<td><p>InquireFA_RU</p></td>
<td><p>Respond to inquiries about fixed assets in Russia</p></td>
</tr>
<tr class="even">
<td><p>Inquire about fixed asset transactions in Russia</p></td>
<td><p>InquireFixedAssetTrans_RU</p></td>
<td><p>Respond to inquiries about fixed asset transactions in Russia</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about fixed asset journals for Russia</p></td>
<td><p>InquireJournalsFA_RU</p></td>
<td><p>Respond to inquiries about fixed asset journals in Russia</p></td>
</tr>
<tr class="even">
<td><p>Inquire about fixed asset taxes for Russia</p></td>
<td><p>InquireTaxesFA_RU</p></td>
<td><p>Respond to inquiries about fixed asset taxes in Russia</p></td>
</tr>
<tr class="odd">
<td><p>Enable cost process</p></td>
<td><p>InventCostCostProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the cost process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into cost status</p></td>
<td><p>InventCostCostStatusInquire</p></td>
<td><p>Respond to inquiries about the performance of the cost process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into cost master</p></td>
<td><p>InventItemPriceCostMasterInquire</p></td>
<td><p>Respond to inquiries about cost master data</p></td>
</tr>
<tr class="even">
<td><p>Review cost process performance</p></td>
<td><p>InventItemPriceCostProcessPerfReview</p></td>
<td><p>Monitor cost</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into packing materials progress</p></td>
<td><p>InventPackMaterialsProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the packing materials process</p></td>
</tr>
<tr class="even">
<td><p>Maintain product type</p></td>
<td><p>InventProductTypeMaintain_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Enable inventory valuation process</p></td>
<td><p>InventStdCostInvValuationProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the inventory valuation process</p></td>
</tr>
<tr class="even">
<td><p>Review inventory valuation process performance</p></td>
<td><p>InventValueInvValuationProcessPerfRevie</p></td>
<td><p>Monitor inventory valuation</p></td>
</tr>
<tr class="odd">
<td><p>Review inventory valuation process performance (cur.)</p></td>
<td><p>InvValueInvValuatProcPerfSecCurReview_RU</p></td>
<td><p>Monitor inventory valuation in the second currency</p></td>
</tr>
<tr class="even">
<td><p>Inquire into chart of account master</p></td>
<td><p>LedgerChartOfAccountsInquire</p></td>
<td><p>Respond to inquiries about chart of accounts</p></td>
</tr>
<tr class="odd">
<td><p>Maintain chart of accounts master</p></td>
<td><p>LedgerChartOfAccountsMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Approve closing transactions</p></td>
<td><p>LedgerClosingTransactionsApprove</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain closing transactions</p></td>
<td><p>LedgerClosingTransactionsMaintain</p></td>
<td><p>Document and record financial closing business events</p></td>
</tr>
<tr class="even">
<td><p>Inquire into closing transaction status</p></td>
<td><p>LedgerClosingTransactionsStatusInquire</p></td>
<td><p>Respond to inquiries about the status of closing transactions</p></td>
</tr>
<tr class="odd">
<td><p>Maintain derived financial hierarchy filters</p></td>
<td><p>LedgerDerivedFinancialHierarchyMaintain</p></td>
<td><p></p></td>
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
<td><p>Inquire into journals and transaction status</p></td>
<td><p>LedgerJournalsTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of journals and transactions</p></td>
</tr>
<tr class="odd">
<td><p>Approve ledger transactions</p></td>
<td><p>LedgerLedgerTransactionsApprove</p></td>
<td><p>Approve ledger transactions</p></td>
</tr>
<tr class="even">
<td><p>Review general ledger process performance through the role center</p></td>
<td><p>LedgerRoleCenterGLProcessPerfReview</p></td>
<td><p>Review general ledger process performance through the role center</p></td>
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
<td><p>Maintain tax group default rules</p></td>
<td><p>MCRAutoTaxRulesMaintain</p></td>
<td><p>Maintain the sales tax group by rules</p></td>
</tr>
<tr class="even">
<td><p>Maintain call center parameters</p></td>
<td><p>MCRCallCenterParametersEnable</p></td>
<td><p>Enable changes to call center parameters</p></td>
</tr>
<tr class="odd">
<td><p>Maintain check payments</p></td>
<td><p>MCRPaymCheckMaintain</p></td>
<td><p>Maintain the ability to use check payments in sales orders for call centers</p></td>
</tr>
<tr class="even">
<td><p>Maintain and configure organizational model</p></td>
<td><p>OMOrganizationsMaintain</p></td>
<td><p>Create or update organizations and organization hierarchies</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into bill of exchange status</p></td>
<td><p>PaymBillOfExchangeStatusInquire</p></td>
<td><p>Respond to inquiries about the status of bills of exchange</p></td>
</tr>
<tr class="even">
<td><p>Inquire into customer positive payments</p></td>
<td><p>PaymCustPositivePayInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain positive payments</p></td>
<td><p>PaymPositivePayMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into promissory note status</p></td>
<td><p>PaymPromissoryNoteStatusInquire</p></td>
<td><p>Respond to inquiries about the status of promissory notes</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into vendor payment status</p></td>
<td><p>PaymVendorPaymentStatusInquire</p></td>
<td><p>Respond to inquiries about the status of vendor payments</p></td>
</tr>
<tr class="even">
<td><p>Inquire into vendor positive payments</p></td>
<td><p>PaymVendPositivePayInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Review purchasing reports through the role center</p></td>
<td><p>ProcRoleCenterPurchProcessReview</p></td>
<td><p>Review purchasing reports through the role center</p></td>
</tr>
<tr class="even">
<td><p>Inquire into estimate project master</p></td>
<td><p>ProjEstimateProjectMasterInquire</p></td>
<td><p>Respond to inquiries about estimate project master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into fixed price projects revenue recognition</p></td>
<td><p>ProjFixedPriceRevenueRecognitionInquire</p></td>
<td><p>Respond to inquiries about fixed-price revenue recognition master information</p></td>
</tr>
<tr class="even">
<td><p>Inquire into project category master</p></td>
<td><p>ProjProjectCategoriesMasterInquire</p></td>
<td><p>Respond to inquiries about project category master information</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into project groups master</p></td>
<td><p>ProjProjectGroupsMasterInquire</p></td>
<td><p>Respond to inquiries about project groups master information</p></td>
</tr>
<tr class="even">
<td><p>Inquire into project master</p></td>
<td><p>ProjProjectMasterInquire</p></td>
<td><p>Respond to inquiries about project master information</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about purchase books</p></td>
<td><p>PurchBookInquire_RU</p></td>
<td><p>Respond to inquiries about purchase books</p></td>
</tr>
<tr class="even">
<td><p>Review purchase order process performance</p></td>
<td><p>PurchOrderProcessPerformanceReview</p></td>
<td><p>Monitor purchase orders</p></td>
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
<td><p>Inquire about tax accounting reference data</p></td>
<td><p>RTax25ReferenceDataInquire</p></td>
<td><p>Respond to inquiries about tax accounting reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire about translation setup and sessions</p></td>
<td><p>RTSLTranslationInquire</p></td>
<td><p>Respond to inquiries about translation setup and sessions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about sales books</p></td>
<td><p>SalesBookInquire_RU</p></td>
<td><p>Respond to inquiries about sales books</p></td>
</tr>
<tr class="even">
<td><p>Inquire into contact master</p></td>
<td><p>smmContactMasterInquire</p></td>
<td><p>Respond to inquiries about contact master data</p></td>
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
<td><p>Inquire taxes matrix</p></td>
<td><p>TaxesMatrixInquire_BR</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Review EU sales list process performance</p></td>
<td><p>TaxEUSalesListProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the EU sales list process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into EU sales list transaction status</p></td>
<td><p>TaxEUSalesListTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of EU sales list transactions</p></td>
</tr>
<tr class="even">
<td><p>Maintain fiscal classification</p></td>
<td><p>TaxFiscalClassificationMaintain_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>View tax fiscal documents</p></td>
<td><p>TaxFiscalDocumentInquire_BR</p></td>
<td><p>View tax fiscal documents</p></td>
</tr>
<tr class="even">
<td><p>Inquire into Intrastat policies</p></td>
<td><p>TaxIntrastatPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the Intrastat process</p></td>
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
<td><p>Review sales taxes process performance</p></td>
<td><p>TaxSalesTaxesProcessPerfReview</p></td>
<td><p>Monitor sales taxes</p></td>
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
<td><p>Maintain service code</p></td>
<td><p>TaxServiceCodeMaintain_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Review unrealized VAT</p></td>
<td><p>TaxUnrealizdVATRemainingReview</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Enable VAT process</p></td>
<td><p>TaxVATProcessEnable_RU</p></td>
<td><p>Set up VAT information to enable the VAT process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into vendor internal invoices</p></td>
<td><p>TaxVendInternalInvoiceInquiry</p></td>
<td><p>Respond to inquiries about vendor internal invoices created for EU purchases</p></td>
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
<td><p>Review invoice and payment process performance</p></td>
<td><p>VendInvoiceInvoicePaymentProcPerfReview</p></td>
<td><p>Monitor, analyze, and improve the invoice and payment process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into invoice and payment process reference data</p></td>
<td><p>VendInvoiceInvoicePaymntProcessRefDataI</p></td>
<td><p>Respond to inquiries about invoice and payment process reference data</p></td>
</tr>
<tr class="even">
<td><p>Approve vendor invoices</p></td>
<td><p>VendInvoiceVendorInvoiceApprove</p></td>
<td><p>Approve vendor invoices</p></td>
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
<tr class="odd">
<td><p>Maintain vendor master</p></td>
<td><p>VendVendorMasterMaintain</p></td>
<td><p>Maintain vendor master</p></td>
</tr>
<tr class="even">
<td><p>Inquire into vendor process</p></td>
<td><p>VendVendorProcessInquire</p></td>
<td><p>Respond to inquiries about vendor process</p></td>
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
<td><p>View estimate projects</p></td>
<td><p>ProjWIPTableView</p></td>
</tr>
<tr class="odd">
<td><p>View project category groups</p></td>
<td><p>ProjCategoryGroupView</p></td>
</tr>
<tr class="even">
<td><p>View project cost categories</p></td>
<td><p>ProjCategoryView</p></td>
</tr>
<tr class="odd">
<td><p>View project groups</p></td>
<td><p>ProjGroupView</p></td>
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


By default, this security role is assigned the following privileges in Microsoft Dynamics AX 2012 R2.

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
<td><p>Maintain accountant information</p></td>
<td><p>AccountantInformationMaintain_BR</p></td>
</tr>
<tr class="even">
<td><p>Maintain vendor tax invoice details</p></td>
<td><p>VendorTaxInvoiceDetailsMaintain</p></td>
</tr>
</tbody>
</table>


By default, this security role is assigned the following privileges in Microsoft Dynamics AX 2012 R3.

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
<td><p>Maintain accountant information</p></td>
<td><p>AccountantInformationMaintain_BR</p></td>
</tr>
<tr class="even">
<td><p>View the mapping between vendor invoice lines and NF-e XML lines</p></td>
<td><p>EFDocReceivedXmlViewMapping_BR</p></td>
</tr>
<tr class="odd">
<td><p>Maintain vendor tax invoice details</p></td>
<td><p>VendorTaxInvoiceDetailsMaintain</p></td>
</tr>
</tbody>
</table>

  


