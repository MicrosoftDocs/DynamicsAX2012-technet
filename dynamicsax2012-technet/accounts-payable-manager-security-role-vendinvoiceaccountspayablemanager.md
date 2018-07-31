---
title: Accounts payable manager security role (VendInvoiceAccountsPayableManager)
TOCTitle: Accounts payable manager security role (VendInvoiceAccountsPayableManager)
ms:assetid: 18703c11-7732-4535-9cd2-de63924aca18
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh527072(v=AX.60)
ms:contentKeyID: 37823124
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Accounts payable manager security role (VendInvoiceAccountsPayableManager) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Accounts payable manager security role represents a user who reviews vendor invoice process performance and enables the vendor invoice process.

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
<td><p>Approve promissory note transactions</p></td>
<td><p>PaymPromissoryNoteTransactionsApprove</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Approve purchase requisitions</p></td>
<td><p>PurchReqPurchaseRequisitionApprove</p></td>
<td><p>Approve and authorize purchase requisitions</p></td>
</tr>
<tr class="odd">
<td><p>Approve vendor invoices</p></td>
<td><p>VendInvoiceVendorInvoiceApprove</p></td>
<td><p>Approve vendor invoices</p></td>
</tr>
<tr class="even">
<td><p>Approve vendor payment transactions</p></td>
<td><p>PaymVendorPaymentTransactionsApprove</p></td>
<td><p>Delegate approval for journal</p></td>
</tr>
<tr class="odd">
<td><p>Enable invoice and payment process</p></td>
<td><p>VendInvoiceInvoicePaymentProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the invoice and payment process</p></td>
</tr>
<tr class="even">
<td><p>Enable purchase order to invoice process</p></td>
<td><p>PurchOrderToInvoiceProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the purchase order to invoice process</p></td>
</tr>
<tr class="odd">
<td><p>Enable purchase order to invoice process for public sector</p></td>
<td><p>PurchOrderToInvoiceProcessEnable_PSN</p></td>
<td><p>Set up policies and reference data to enable the purchase order to invoice process</p></td>
</tr>
<tr class="even">
<td><p>Enable purchasing process</p></td>
<td><p>ProcPurchasingProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the purchasing process</p></td>
</tr>
<tr class="odd">
<td><p>Enable purchasing process for public sector</p></td>
<td><p>ProcPurchasingProcessEnable_PSN</p></td>
<td><p>Set up policies and reference data to enable the purchasing process</p></td>
</tr>
<tr class="even">
<td><p>Enable signing limit process</p></td>
<td><p>ProcSigningLimitProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the signing limits process</p></td>
</tr>
<tr class="odd">
<td><p>Enable travel and expense process</p></td>
<td><p>TrvTravelAndExpenseProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the travel and expense process</p></td>
</tr>
<tr class="even">
<td><p>Enable vendor process</p></td>
<td><p>VendVendorProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the vendor process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into address book reference data</p></td>
<td><p>DirAddressBookReferenceDataInquire</p></td>
<td><p>Respond to inquiries about address book reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into bank accounts master</p></td>
<td><p>BankBankAccountsInquire</p></td>
<td><p>Respond to inquiries about bank master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into chart of account master</p></td>
<td><p>LedgerChartOfAccountsInquire</p></td>
<td><p>Respond to inquiries about chart of accounts</p></td>
</tr>
<tr class="even">
<td><p>Inquire into contact master</p></td>
<td><p>smmContactMasterInquire</p></td>
<td><p>Respond to inquiries about contact master data</p></td>
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
<td><p>Inquire into import letter of credit</p></td>
<td><p>BankImportLetterOfCreditInquire</p></td>
<td><p>Respond to inquiries about the status of import letters of credit</p></td>
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
<td><p>Inquire into promissory note status</p></td>
<td><p>PaymPromissoryNoteStatusInquire</p></td>
<td><p>Respond to inquiries about the status of promissory notes</p></td>
</tr>
<tr class="even">
<td><p>Inquire into purchase order to invoice policies</p></td>
<td><p>PurchOrderToInvoicePoliciesInquire</p></td>
<td><p>Respond to inquiries about the policies governing the purchase order to invoice process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into purchase order to invoice progress</p></td>
<td><p>PurchOrderToInvoiceProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the purchase order to invoice process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into purchase order to invoice progress for public sector</p></td>
<td><p>PurchOrderToInvoiceProgressInquire_PSN</p></td>
<td><p>Respond to inquiries about the status of the purchase order to invoice process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into purchase requisition</p></td>
<td><p>PurchReqPurchaseRequisitionInquire</p></td>
<td><p>Respond to inquiries about the status of purchase requisitions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into purchasing policies</p></td>
<td><p>ProcPurchasingProcessInquire</p></td>
<td><p>Respond to inquiries about policies governing the purchasing process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into purchasing policies for public sector</p></td>
<td><p>ProcPurchasingProcessInquire_PSN</p></td>
<td><p>Respond to inquiries about policies governing the purchasing process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into sales commissions master</p></td>
<td><p>CustInvoiceSalesCommissionsInquire</p></td>
<td><p>Respond to inquiries about commission master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into sales tax process reference data</p></td>
<td><p>TaxSalesTaxProcessReferenceDataInquire</p></td>
<td><p>Respond to inquiries about sales tax process reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into signing limit policies</p></td>
<td><p>ProcSigningLimitProcessInquire</p></td>
<td><p>Respond to inquiries about policies related to signing limits</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into vendor invoice register status</p></td>
<td><p>VendInvoiceVendorInvRegisterView</p></td>
<td><p>Respond to inquiries about the status of vendor invoice register</p></td>
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
<td><p>Maintain import letter of credit</p></td>
<td><p>BankImportLetterOfCreditMaintain</p></td>
<td><p>Document and record import letter of credit business events</p></td>
</tr>
<tr class="even">
<td><p>Maintain payables setup print management settings</p></td>
<td><p>PrintMgmtPayablesSettingsMaintain</p></td>
<td><p>Maintain payables setup print management settings</p></td>
</tr>
<tr class="odd">
<td><p>Maintain sites service solution in account payable module</p></td>
<td><p>VendSitesSolutionMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain travel and expense queues</p></td>
<td><p>TrvTravelAndExpenseQueuesMaintain</p></td>
<td><p>Maintain travel and expense queues</p></td>
</tr>
<tr class="odd">
<td><p>Maintain vendor master</p></td>
<td><p>VendVendorMasterMaintain</p></td>
<td><p>Maintain vendor master</p></td>
</tr>
<tr class="even">
<td><p>Maintain vendor print management settings</p></td>
<td><p>PrintMgmtVendTableSetupMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Review bank management process performance</p></td>
<td><p>BankBankManagementProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the bank management process</p></td>
</tr>
<tr class="even">
<td><p>Review travel and expense process</p></td>
<td><p>TrvTravelAndExpenseProcessReview</p></td>
<td><p>Monitor, analyze, and improve the travel and expense process</p></td>
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
<td><p>Approve promissory note transactions</p></td>
<td><p>PaymPromissoryNoteTransactionsApprove</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Approve purchase requisitions</p></td>
<td><p>PurchReqPurchaseRequisitionApprove</p></td>
<td><p>Approve and authorize purchase requisitions</p></td>
</tr>
<tr class="odd">
<td><p>Approve vendor invoices</p></td>
<td><p>VendInvoiceVendorInvoiceApprove</p></td>
<td><p>Approve vendor invoices</p></td>
</tr>
<tr class="even">
<td><p>Approve vendor payment transactions</p></td>
<td><p>PaymVendorPaymentTransactionsApprove</p></td>
<td><p>Delegate approval for journal</p></td>
</tr>
<tr class="odd">
<td><p>Enable invoice and payment process</p></td>
<td><p>VendInvoiceInvoicePaymentProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the invoice and payment process</p></td>
</tr>
<tr class="even">
<td><p>Enable purchase order to invoice process</p></td>
<td><p>PurchOrderToInvoiceProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the purchase order to invoice process</p></td>
</tr>
<tr class="odd">
<td><p>Enable purchase order to invoice process for public sector</p></td>
<td><p>PurchOrderToInvoiceProcessEnable_PSN</p></td>
<td><p>Set up policies and reference data to enable the purchase order to invoice process</p></td>
</tr>
<tr class="even">
<td><p>Enable purchasing process</p></td>
<td><p>ProcPurchasingProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the purchasing process</p></td>
</tr>
<tr class="odd">
<td><p>Enable purchasing process for public sector</p></td>
<td><p>ProcPurchasingProcessEnable_PSN</p></td>
<td><p>Set up policies and reference data to enable the purchasing process</p></td>
</tr>
<tr class="even">
<td><p>Enable signing limit process</p></td>
<td><p>ProcSigningLimitProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the signing limits process</p></td>
</tr>
<tr class="odd">
<td><p>Enable travel and expense process</p></td>
<td><p>TrvTravelAndExpenseProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the travel and expense process</p></td>
</tr>
<tr class="even">
<td><p>Enable vendor process</p></td>
<td><p>VendVendorProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the vendor process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into address book reference data</p></td>
<td><p>DirAddressBookReferenceDataInquire</p></td>
<td><p>Respond to inquiries about address book reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into bank accounts master</p></td>
<td><p>BankBankAccountsInquire</p></td>
<td><p>Respond to inquiries about bank master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into chart of account master</p></td>
<td><p>LedgerChartOfAccountsInquire</p></td>
<td><p>Respond to inquiries about chart of accounts</p></td>
</tr>
<tr class="even">
<td><p>Inquire into contact master</p></td>
<td><p>smmContactMasterInquire</p></td>
<td><p>Respond to inquiries about contact master data</p></td>
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
<td><p>Inquire into import letter of credit</p></td>
<td><p>BankImportLetterOfCreditInquire</p></td>
<td><p>Respond to inquiries about the status of import letters of credit</p></td>
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
<td><p>Inquire into mandats</p></td>
<td><p>VendDirectiveInquire_PSN</p></td>
<td><p>View mandat tabs, mandat reports, and the mandat maintenance form</p></td>
</tr>
<tr class="even">
<td><p>Inquire into promissory note status</p></td>
<td><p>PaymPromissoryNoteStatusInquire</p></td>
<td><p>Respond to inquiries about the status of promissory notes</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into purchase order to invoice policies</p></td>
<td><p>PurchOrderToInvoicePoliciesInquire</p></td>
<td><p>Respond to inquiries about the policies governing the purchase order to invoice process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into purchase order to invoice progress</p></td>
<td><p>PurchOrderToInvoiceProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the purchase order to invoice process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into purchase order to invoice progress for public sector</p></td>
<td><p>PurchOrderToInvoiceProgressInquire_PSN</p></td>
<td><p>Respond to inquiries about the status of the purchase order to invoice process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into purchase requisition</p></td>
<td><p>PurchReqPurchaseRequisitionInquire</p></td>
<td><p>Respond to inquiries about the status of purchase requisitions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into purchasing policies</p></td>
<td><p>ProcPurchasingProcessInquire</p></td>
<td><p>Respond to inquiries about policies governing the purchasing process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into purchasing policies for public sector</p></td>
<td><p>ProcPurchasingProcessInquire_PSN</p></td>
<td><p>Respond to inquiries about policies governing the purchasing process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into sales commissions master</p></td>
<td><p>CustInvoiceSalesCommissionsInquire</p></td>
<td><p>Respond to inquiries about commission master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into sales tax process reference data</p></td>
<td><p>TaxSalesTaxProcessReferenceDataInquire</p></td>
<td><p>Respond to inquiries about sales tax process reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into signing limit policies</p></td>
<td><p>ProcSigningLimitProcessInquire</p></td>
<td><p>Respond to inquiries about policies related to signing limits</p></td>
</tr>
<tr class="even">
<td><p>Inquire into vendor invoice register status</p></td>
<td><p>VendInvoiceVendorInvRegisterView</p></td>
<td><p>Respond to inquiries about the status of vendor invoice register</p></td>
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
<td><p>Inquire into withholding tax transactions</p></td>
<td><p>TaxWithholdTransactionInquire</p></td>
<td><p>Inquire the withholding tax transactions details</p></td>
</tr>
<tr class="odd">
<td><p>Maintain Configurator definitions and processes</p></td>
<td><p>ConfiguratorMaintain_BR</p></td>
<td><p>Access to the Definition group, Layout group, Export/import of groups, and Configurator export utility tool</p></td>
</tr>
<tr class="even">
<td><p>Maintain correction letters</p></td>
<td><p>EFDocCorrectionLetterMaintain_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain import letter of credit</p></td>
<td><p>BankImportLetterOfCreditMaintain</p></td>
<td><p>Document and record import letter of credit business events</p></td>
</tr>
<tr class="even">
<td><p>Maintain payables setup print management settings</p></td>
<td><p>PrintMgmtPayablesSettingsMaintain</p></td>
<td><p>Maintain payables setup print management settings</p></td>
</tr>
<tr class="odd">
<td><p>Maintain sites service solution in account payable module</p></td>
<td><p>VendSitesSolutionMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain tax transactions</p></td>
<td><p>TaxTransMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain the Accountant acceptance status</p></td>
<td><p>VendDirectiveAccountantMaintain_PSN</p></td>
<td><p>Maintain the Accountant acceptance status</p></td>
</tr>
<tr class="even">
<td><p>Maintain travel and expense queues</p></td>
<td><p>TrvTravelAndExpenseQueuesMaintain</p></td>
<td><p>Maintain travel and expense queues</p></td>
</tr>
<tr class="odd">
<td><p>Maintain vendor hold status</p></td>
<td><p>VendOnHoldUpdate</p></td>
<td><p>Maintain vendor hold status</p></td>
</tr>
<tr class="even">
<td><p>Maintain vendor master</p></td>
<td><p>VendVendorMasterMaintain</p></td>
<td><p>Maintain vendor master</p></td>
</tr>
<tr class="odd">
<td><p>Maintain vendor print management settings</p></td>
<td><p>PrintMgmtVendTableSetupMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain withholding tax transactions</p></td>
<td><p>TaxWithholdTransactionMaintain</p></td>
<td><p>Maintain the withholding tax transactions details.</p></td>
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
<td><p>Review travel and expense process</p></td>
<td><p>TrvTravelAndExpenseProcessReview</p></td>
<td><p>Monitor, analyze, and improve the travel and expense process</p></td>
</tr>
<tr class="even">
<td><p>Role center URL redirection</p></td>
<td><p>EPHomePageView</p></td>
<td><p>Enable redirection from generic role center URL</p></td>
</tr>
<tr class="odd">
<td><p>View fiscal document</p></td>
<td><p>FiscalDocumentInquire_BR</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>View fiscal document source texts</p></td>
<td><p>FiscalDocumentSourceTextView_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>View tax branches</p></td>
<td><p>TaxBranchView</p></td>
<td><p>Set up tax branch details</p></td>
</tr>
<tr class="even">
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
<td><p>Inquire into fixed assets</p></td>
<td><p>AssetFixedAssetsInquire</p></td>
<td><p>Respond to inquiries about fixed assets master data</p></td>
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
<td><p>Review bank management process performance</p></td>
<td><p>BankBankManagementProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the bank management process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into import letter of credit</p></td>
<td><p>BankImportLetterOfCreditInquire</p></td>
<td><p>Respond to inquiries about the status of import letters of credit</p></td>
</tr>
<tr class="even">
<td><p>Maintain import letter of credit</p></td>
<td><p>BankImportLetterOfCreditMaintain</p></td>
<td><p>Document and record import letter of credit business events</p></td>
</tr>
<tr class="odd">
<td><p>Maintain Configurator definitions and processes</p></td>
<td><p>ConfiguratorMaintain_BR</p></td>
<td><p>Access to the Definition group, Layout group, Export/import of groups, and Configurator export utility tool</p></td>
</tr>
<tr class="even">
<td><p>Inquire into sales commissions master</p></td>
<td><p>CustInvoiceSalesCommissionsInquire</p></td>
<td><p>Respond to inquiries about commission master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into address book reference data</p></td>
<td><p>DirAddressBookReferenceDataInquire</p></td>
<td><p>Respond to inquiries about address book reference data</p></td>
</tr>
<tr class="even">
<td><p>Maintain correction letters</p></td>
<td><p>EFDocCorrectionLetterMaintain_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into receipt electronic fiscal document</p></td>
<td><p>EFDocumentReceivedXMLInquire_BR</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>View the discrepancies between vendor invoice values and the received XML values</p></td>
<td><p>EFDocumentReceivedXmlMatchingInquire_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Role center URL redirection</p></td>
<td><p>EPHomePageView</p></td>
<td><p>Enable redirection from generic role center URL</p></td>
</tr>
<tr class="even">
<td><p>View fiscal document</p></td>
<td><p>FiscalDocumentInquire_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>View fiscal document source texts</p></td>
<td><p>FiscalDocumentSourceTextView_BR</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into imported content and FCI</p></td>
<td><p>ImportedContentPerItemInquire_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into chart of account master</p></td>
<td><p>LedgerChartOfAccountsInquire</p></td>
<td><p>Respond to inquiries about chart of accounts</p></td>
</tr>
<tr class="even">
<td><p>Inquire into journals and transaction status</p></td>
<td><p>LedgerJournalsTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of journals and transactions</p></td>
</tr>
<tr class="odd">
<td><p>Maintain general ledger parameters</p></td>
<td><p>LedgerParametersMaintain</p></td>
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
<td><p>Approve promissory note transactions</p></td>
<td><p>PaymPromissoryNoteTransactionsApprove</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into vendor payment status</p></td>
<td><p>PaymVendorPaymentStatusInquire</p></td>
<td><p>Respond to inquiries about the status of vendor payments</p></td>
</tr>
<tr class="even">
<td><p>Approve vendor payment transactions</p></td>
<td><p>PaymVendorPaymentTransactionsApprove</p></td>
<td><p>Delegate approval for journal</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into vendor positive payments</p></td>
<td><p>PaymVendPositivePayInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain payables setup print management settings</p></td>
<td><p>PrintMgmtPayablesSettingsMaintain</p></td>
<td><p>Maintain payables setup print management settings</p></td>
</tr>
<tr class="odd">
<td><p>Maintain vendor print management settings</p></td>
<td><p>PrintMgmtVendTableSetupMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Enable purchasing process</p></td>
<td><p>ProcPurchasingProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the purchasing process</p></td>
</tr>
<tr class="odd">
<td><p>Enable purchasing process for public sector</p></td>
<td><p>ProcPurchasingProcessEnable_PSN</p></td>
<td><p>Set up policies and reference data to enable the purchasing process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into purchasing policies</p></td>
<td><p>ProcPurchasingProcessInquire</p></td>
<td><p>Respond to inquiries about policies governing the purchasing process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into purchasing policies for public sector</p></td>
<td><p>ProcPurchasingProcessInquire_PSN</p></td>
<td><p>Respond to inquiries about policies governing the purchasing process</p></td>
</tr>
<tr class="even">
<td><p>Enable signing limit process</p></td>
<td><p>ProcSigningLimitProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the signing limits process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into signing limit policies</p></td>
<td><p>ProcSigningLimitProcessInquire</p></td>
<td><p>Respond to inquiries about policies related to signing limits</p></td>
</tr>
<tr class="even">
<td><p>Inquire into purchase order to invoice policies</p></td>
<td><p>PurchOrderToInvoicePoliciesInquire</p></td>
<td><p>Respond to inquiries about the policies governing the purchase order to invoice process</p></td>
</tr>
<tr class="odd">
<td><p>Enable purchase order to invoice process</p></td>
<td><p>PurchOrderToInvoiceProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the purchase order to invoice process</p></td>
</tr>
<tr class="even">
<td><p>Enable purchase order to invoice process for public sector</p></td>
<td><p>PurchOrderToInvoiceProcessEnable_PSN</p></td>
<td><p>Set up policies and reference data to enable the purchase order to invoice process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into purchase order to invoice progress</p></td>
<td><p>PurchOrderToInvoiceProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the purchase order to invoice process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into purchase order to invoice progress for public sector</p></td>
<td><p>PurchOrderToInvoiceProgressInquire_PSN</p></td>
<td><p>Respond to inquiries about the status of the purchase order to invoice process</p></td>
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
<td><p>Inquire into contact master</p></td>
<td><p>smmContactMasterInquire</p></td>
<td><p>Respond to inquiries about contact master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into vendor rebate agreements</p></td>
<td><p>TAMVendRebateAgreementInquire</p></td>
<td><p>View vendor rebate agreements</p></td>
</tr>
<tr class="odd">
<td><p>Maintain purchase rebates</p></td>
<td><p>TAMVendRebateMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Review average VAT</p></td>
<td><p>TaxAverageVATReview</p></td>
<td><p>Review average VAT details via the average VAT report</p></td>
</tr>
<tr class="odd">
<td><p>View tax branches</p></td>
<td><p>TaxBranchView</p></td>
<td><p>Set up tax branch details</p></td>
</tr>
<tr class="even">
<td><p>View tax fiscal documents</p></td>
<td><p>TaxFiscalDocumentInquire_BR</p></td>
<td><p>View tax fiscal documents</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into sales tax process reference data</p></td>
<td><p>TaxSalesTaxProcessReferenceDataInquire</p></td>
<td><p>Respond to inquiries about sales tax process reference data</p></td>
</tr>
<tr class="even">
<td><p>Maintain tax transactions</p></td>
<td><p>TaxTransMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into withholding tax transactions</p></td>
<td><p>TaxWithholdTransactionInquire</p></td>
<td><p>Inquire the withholding tax transactions details.</p></td>
</tr>
<tr class="even">
<td><p>Maintain withholding tax transactions</p></td>
<td><p>TaxWithholdTransactionMaintain</p></td>
<td><p>Maintain the withholding tax transactions details.</p></td>
</tr>
<tr class="odd">
<td><p>Enable travel and expense process</p></td>
<td><p>TrvTravelAndExpenseProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the travel and expense process</p></td>
</tr>
<tr class="even">
<td><p>Review travel and expense process</p></td>
<td><p>TrvTravelAndExpenseProcessReview</p></td>
<td><p>Monitor, analyze, and improve the travel and expense process</p></td>
</tr>
<tr class="odd">
<td><p>Maintain travel and expense queues</p></td>
<td><p>TrvTravelAndExpenseQueuesMaintain</p></td>
<td><p>Maintain travel and expense queues</p></td>
</tr>
<tr class="even">
<td><p>Maintain the Accountant acceptance status</p></td>
<td><p>VendDirectiveAccountantMaintain_PSN</p></td>
<td><p>Maintain the Accountant acceptance status</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into mandats</p></td>
<td><p>VendDirectiveInquire_PSN</p></td>
<td><p>View mandat tabs, mandat reports, and the mandat maintenance form</p></td>
</tr>
<tr class="even">
<td><p>Inquire into invoice and payment policies</p></td>
<td><p>VendInvoiceInvoicePaymentPoliciesInquir</p></td>
<td><p>Respond to inquiries about policies governing the invoice and payment process</p></td>
</tr>
<tr class="odd">
<td><p>Enable invoice and payment process</p></td>
<td><p>VendInvoiceInvoicePaymentProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the invoice and payment process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into invoice and payment process reference data</p></td>
<td><p>VendInvoiceInvoicePaymntProcessRefDataI</p></td>
<td><p>Respond to inquiries about invoice and payment process reference data</p></td>
</tr>
<tr class="odd">
<td><p>Approve vendor invoices</p></td>
<td><p>VendInvoiceVendorInvoiceApprove</p></td>
<td><p>Approve vendor invoices</p></td>
</tr>
<tr class="even">
<td><p>Inquire into vendor invoice status</p></td>
<td><p>VendInvoiceVendorInvoiceStatusInquire</p></td>
<td><p>Respond to inquiries about the status of vendor invoices</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into vendor invoice register status</p></td>
<td><p>VendInvoiceVendorInvRegisterView</p></td>
<td><p>Respond to inquiries about the status of vendor invoice register</p></td>
</tr>
<tr class="even">
<td><p>Maintain vendor hold status</p></td>
<td><p>VendOnHoldUpdate</p></td>
<td><p>Maintain vendor hold status</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about overdue vendor debt CIT and PIT journals</p></td>
<td><p>VendOverdueCITPITJournalInquire_W</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire about vendor overdue debt VAT journals</p></td>
<td><p>VendOverdueVATJournalInquire_W</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain sites service solution in account payable module</p></td>
<td><p>VendSitesSolutionMaintain</p></td>
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
<td><p>Enable vendor process</p></td>
<td><p>VendVendorProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the vendor process</p></td>
</tr>
</tbody>
</table>

  


