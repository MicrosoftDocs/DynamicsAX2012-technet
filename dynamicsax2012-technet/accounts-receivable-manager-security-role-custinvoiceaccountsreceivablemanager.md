---
title: Accounts receivable manager security role (CustInvoiceAccountsReceivableManager)
TOCTitle: Accounts receivable manager security role (CustInvoiceAccountsReceivableManager)
ms:assetid: 76627691-99ac-4403-ae1b-65a38c38cc48
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh527103(v=AX.60)
ms:contentKeyID: 37823155
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Accounts receivable manager security role (CustInvoiceAccountsReceivableManager) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Accounts receivable manager security role represents a user who reviews customer invoice process performance and enables the customer invoice process.

## Duties

By default, this security role is assigned the following duties in Microsoft Dynamics AX.

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
<td><p>Inquire into export letter of credit</p></td>
<td><p>BankExportLetterOfCreditInquire</p></td>
<td><p>Respond to inquiries about the status of export letters of credit</p></td>
</tr>
<tr class="even">
<td><p>Maintain export letter of credit</p></td>
<td><p>BankExportLetterOfCreditMaintain</p></td>
<td><p>Document and record export letter of credit business events</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into bank letter of guarantee</p></td>
<td><p>BankLetterOfGuaranteeInquire</p></td>
<td><p>Respond to inquiries about bank letter of guarantee</p></td>
</tr>
<tr class="even">
<td><p>Maintain bank letter of guarantee</p></td>
<td><p>BankLetterOfGuaranteeMaintain</p></td>
<td><p>Maintain bank letter of guarantee</p></td>
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
<td><p>Maintain Configurator definitions and processes</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ConfiguratorMaintain_BR</p></td>
<td><p>Access to the Definition group, Layout group, Export/import of groups, and Configurator export utility tool</p></td>
</tr>
<tr class="even">
<td><p>Enable credit cards</p></td>
<td><p>CreditCardCreditCardEnable</p></td>
<td><p>Set up credit card parameters and payment services</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into credit card processing</p></td>
<td><p>CreditCardCreditCardProcessingInquire</p></td>
<td><p>Respond to inquiries about credit card processing</p></td>
</tr>
<tr class="even">
<td><p>Inquire into credit card reference data</p></td>
<td><p>CreditCardCreditCardReferenceDataInquir</p></td>
<td><p>Respond to inquiries about credit card reference data</p></td>
</tr>
<tr class="odd">
<td><p>Enable credit cards process</p></td>
<td><p>CreditCardCreditCardsProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the credit cards process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into customer master</p></td>
<td><p>CustCustomerMasterInquire</p></td>
<td><p>Respond to inquiries about customer master data</p></td>
</tr>
<tr class="odd">
<td><p>Enable customer process</p></td>
<td><p>CustCustomerProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the customer process</p></td>
</tr>
<tr class="even">
<td><p>Maintain customer master</p></td>
<td><p>CustCustomersMaintain</p></td>
<td><p>Document and record customer master information</p></td>
</tr>
<tr class="odd">
<td><p>Maintain the Accountant acceptance status</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>CustDirectiveAccountantMaintain_PSN</p></td>
<td><p>Maintain the Accountant acceptance status</p></td>
</tr>
<tr class="even">
<td><p>View titre</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>CustDirectiveInquire_PSN</p></td>
<td><p>View titre tabs, titre reports, and the titre maintenance form</p></td>
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
<td><p>Inquire about customer overdue debt VAT journals</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>CustOverdueVATJournalInquire_W</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain sites solution in accounts receivable module</p></td>
<td><p>CustSitesSolutionMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into address book reference data</p></td>
<td><p>DirAddressBookReferenceDataInquire</p></td>
<td><p>Respond to inquiries about address book reference data</p></td>
</tr>
<tr class="odd">
<td><p>Maintain correction letters</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>EFDocCorrectionLetterMaintain_BR</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>View electronic fiscal document information</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>EFDocumentMaintain_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Configure electronic fiscal document</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>EFDocumentSetup_BR</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>NF-e issued in contingency mode</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>EFiscalDocContingencyMode_BR</p></td>
<td><p>NF-e issued in contingency mode</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into EInvoice progress</p></td>
<td><p>EInvoiceInquire_MX</p></td>
<td><p>Inquire into EInvoice progress</p></td>
</tr>
<tr class="even">
<td><p>Role center URL redirection</p></td>
<td><p>EPHomePageView</p></td>
<td><p>Enable redirection from generic role center URL</p></td>
</tr>
<tr class="odd">
<td><p>View fiscal document</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>FiscalDocumentInquire_BR</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>View fiscal document source texts</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>FiscalDocumentSourceTextView_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into imported content and FCI</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ImportedContentPerItemInquire_BR</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into chart of account master</p></td>
<td><p>LedgerChartOfAccountsInquire</p></td>
<td><p>Respond to inquiries about chart of accounts</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into journals and transaction status</p></td>
<td><p>LedgerJournalsTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of journals and transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into bill of exchange status</p></td>
<td><p>PaymBillOfExchangeStatusInquire</p></td>
<td><p>Respond to inquiries about the status of bills of exchange</p></td>
</tr>
<tr class="odd">
<td><p>Approve bill of exchange transactions</p></td>
<td><p>PaymBillOfExchangeTransactionsApprove</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into customer payments status</p></td>
<td><p>PaymCustomerPaymentsStatusInquire</p></td>
<td><p>Respond to inquiries about the status of customer payments</p></td>
</tr>
<tr class="odd">
<td><p>Approve customer payment transactions</p></td>
<td><p>PaymCustPaymentTransactionsApprove</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into customer positive payments</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>PaymCustPositivePayInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain positive payments</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>PaymPositivePayMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Approves generated customer rebates</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>PdsRebateApprove</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain rebate payments</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>PdsRebatePaymentMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Processes customer rebates</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>PdsRebateProcess</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain customer print management settings</p></td>
<td><p>PrintMgmtCustTableSetupMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain free text invoice print management settings</p></td>
<td><p>PrintMgmtFreeTextSettingsMaintain</p></td>
<td><p>Maintain free text invoice print management settings</p></td>
</tr>
<tr class="odd">
<td><p>Maintain receivables setup print management settings</p></td>
<td><p>PrintMgmtReceivablesSettingsMaintain</p></td>
<td><p>Maintain receivables setup print management settings</p></td>
</tr>
<tr class="even">
<td><p>RPS file export and import for Electronic fiscal document city</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>RPSMaintain_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain sales fiscal document</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>SalesFiscalDocumentMaintain_BR</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into sales order progress</p></td>
<td><p>SalesOrderProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the sales order process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into quotation to sales order policies</p></td>
<td><p>SalesQuotationToSalesOrderPolInquire</p></td>
<td><p>Respond to inquiries about the policies governing the quotation to sales order process</p></td>
</tr>
<tr class="even">
<td><p>Enable quotation to sales order process</p></td>
<td><p>SalesQuotationToSalesOrderProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the quotation to sales order process</p></td>
</tr>
<tr class="odd">
<td><p>Review average VAT</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>TaxAverageVATReview</p></td>
<td><p>Review average VAT details via the average VAT report</p></td>
</tr>
<tr class="even">
<td><p>View tax branches</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>TaxBranchView</p></td>
<td><p>Set up tax branch details</p></td>
</tr>
<tr class="odd">
<td><p>View tax fiscal documents</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>TaxFiscalDocumentInquire_BR</p></td>
<td><p>View tax fiscal documents</p></td>
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
<td><p>Inquire into withholding tax transactions</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>TaxWithholdTransactionInquire</p></td>
<td><p>Inquire the withholding tax transactions details.</p></td>
</tr>
<tr class="even">
<td><p>Maintain withholding tax transactions</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>TaxWithholdTransactionMaintain</p></td>
<td><p>Maintain the withholding tax transactions details.</p></td>
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
<td><p>Generate the details of the Receivables by billing classification</p></td>
<td><p>CustReceivablePeriodDetailReportGenerate</p></td>
</tr>
<tr class="even">
<td><p>Generate the Receivables by billing classification report</p></td>
<td><p>CustReceivableClassificationGenerate</p></td>
</tr>
</tbody>
</table>


By default, no privileges are directly assigned to this security role in Microsoft Dynamics AX 2012 R2 or Microsoft Dynamics AX 2012 R3.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

