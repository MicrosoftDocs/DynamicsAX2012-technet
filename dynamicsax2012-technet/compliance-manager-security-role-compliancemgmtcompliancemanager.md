---
title: Compliance manager security role (ComplianceMgmtComplianceManager)
TOCTitle: Compliance manager security role (ComplianceMgmtComplianceManager)
ms:assetid: 269f7620-9ddc-4f8c-a166-19445de146e1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh527076(v=AX.60)
ms:contentKeyID: 37823128
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Compliance manager security role (ComplianceMgmtComplianceManager) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Compliance manager security role represents a user who reviews compliance process performance and enables the compliance process.

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
<td><p>Enable compliance process</p></td>
<td><p>ComplianceMgmtComplianceProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the compliance process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into audit policies</p></td>
<td><p>ComplianceMgmtAuditPoliciesInquire</p></td>
<td><p>Respond to inquiries about audit reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into bank management policies</p></td>
<td><p>BankBankManagementPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the bank management process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into budget master</p></td>
<td><p>BudgetBudgetsInquire</p></td>
<td><p>Respond to inquiries about budget master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into compliance policies</p></td>
<td><p>ComplianceMgmtCompliancePoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the compliance process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into compliance reference data</p></td>
<td><p>ComplianceMgmtComplianceRefDataInquire</p></td>
<td><p>Respond to inquiries about compliance reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into customer master</p></td>
<td><p>CustCustomerMasterInquire</p></td>
<td><p>Respond to inquiries about customer master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into customer reference data</p></td>
<td><p>CustCustomerReferenceDataInquire</p></td>
<td><p>Respond to inquiries about customer master reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into general ledger policies</p></td>
<td><p>LedgerGeneralLedgerPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the general ledger process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into invoice and cash policies</p></td>
<td><p>CustInvoiceInvoiceAndCashPoliciesInquir</p></td>
<td><p>Respond to inquiries about policies governing the invoice and cash process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into invoice and payment policies</p></td>
<td><p>VendInvoiceInvoicePaymentPoliciesInquir</p></td>
<td><p>Respond to inquiries about policies governing the invoice and payment process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into journals and transaction status</p></td>
<td><p>LedgerJournalsTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of journals and transactions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into purchase order to invoice policies</p></td>
<td><p>PurchOrderToInvoicePoliciesInquire</p></td>
<td><p>Respond to inquiries about the policies governing the purchase order to invoice process</p></td>
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
<td><p>Inquire into sales tax policies</p></td>
<td><p>TaxSalesTaxPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the sales tax process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into travel and expense policies</p></td>
<td><p>TrvTravelAndExpensePoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the travel and expense process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into vendor master</p></td>
<td><p>VendVendorMasterInquire</p></td>
<td><p>Respond to inquiries about vendor master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into vendor process</p></td>
<td><p>VendVendorProcessInquire</p></td>
<td><p>Respond to inquiries about vendor process</p></td>
</tr>
<tr class="even">
<td><p>Maintain audit policies</p></td>
<td><p>ComplianceMgmtAuditPoliciesMaintain</p></td>
<td><p>Set up policy and reference data to enable audit policy rules and cases</p></td>
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
<td><p>Review credit cards process performance</p></td>
<td><p>CreditCardCreditCardsProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the credit cards process</p></td>
</tr>
<tr class="odd">
<td><p>Review EU sales list process performance</p></td>
<td><p>TaxEUSalesListProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the EU sales list process</p></td>
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
<td><p>Review sales taxes process performance</p></td>
<td><p>TaxSalesTaxesProcessPerfReview</p></td>
<td><p>Monitor sales taxes</p></td>
</tr>
<tr class="odd">
<td><p>View budget plans</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>BudgetPlanView</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

