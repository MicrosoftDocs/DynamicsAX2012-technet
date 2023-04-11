---
title: Treasurer security role (PaymTreasurer)
TOCTitle: Treasurer security role (PaymTreasurer)
ms:assetid: a9175325-9308-494c-b34b-3d6cccf345bb
ms:mtpsurl: https://technet.microsoft.com/library/Hh527118(v=AX.60)
ms:contentKeyID: 37823169
author: tonyafehr
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Treasurer security role (PaymTreasurer) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Treasurer security role represents a user who documents treasury events and responds to treasury inquiries.

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
<td><p>Enable bank management process</p></td>
<td><p>BankBankManagementProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the bank management process</p></td>
</tr>
<tr class="even">
<td><p>Enable client bank management process</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>BankClientBankManagementProcessEnable_RU</p></td>
<td><p>Set up import format, export format, and other information to enable the client bank management process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about accounting data</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>InquireAccountingData_RU</p></td>
<td><p>Respond to inquiries about accounting data</p></td>
</tr>
<tr class="even">
<td><p>Inquire about payment status for customer invoices</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>CustInvoice4PaymInquire_RU</p></td>
<td><p>Respond to inquiries about payment status for customer invoices</p></td>
</tr>
<tr class="odd">
<td><p>Inquire about payment status for vendor invoices</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>VendInvoice4paymentStatusInquire_RU</p></td>
<td><p>Respond to inquiries about payment status for vendor invoices</p></td>
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
<td><p>Inquire into cash accounts</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>CashAccountsInquire</p></td>
<td><p>Respond to inquiries about cash accounts data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into cash transaction status</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>CashTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of cash transactions</p></td>
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
<td><p>Inquire into Treasurer reports</p></td>
<td><p>LedgerTreasurerInquire</p></td>
<td><p>View all treasurer reports</p></td>
</tr>
<tr class="odd">
<td><p>Maintain bank account reconciliation transactions</p></td>
<td><p>BankBankAccountReconTransactionsMaintai</p></td>
<td><p>Document and record bank account reconciliation business events</p></td>
</tr>
<tr class="even">
<td><p>Maintain bank accounts master</p></td>
<td><p>BankBankAccountsMaintain</p></td>
<td><p>Maintain bank accounts master</p></td>
</tr>
<tr class="odd">
<td><p>Maintain bank letter of guarantee</p></td>
<td><p>BankLetterOfGuaranteeMaintain</p></td>
<td><p>Maintain bank letter of guarantee</p></td>
</tr>
<tr class="even">
<td><p>Maintain bank transactions</p></td>
<td><p>BankBankTransactionsMaintain</p></td>
<td><p>Document and record bank business events</p></td>
</tr>
<tr class="odd">
<td><p>Maintain cash and bank print management settings</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>BankPrintMgmtMaintain_BR</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain export letter of credit</p></td>
<td><p>BankExportLetterOfCreditMaintain</p></td>
<td><p>Document and record export letter of credit business events</p></td>
</tr>
<tr class="odd">
<td><p>Maintain import letter of credit</p></td>
<td><p>BankImportLetterOfCreditMaintain</p></td>
<td><p>Document and record import letter of credit business events</p></td>
</tr>
<tr class="even">
<td><p>Review bank management process performance</p></td>
<td><p>BankBankManagementProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the bank management process</p></td>
</tr>
<tr class="odd">
<td><p>Review bank management process performance through the role center</p></td>
<td><p>BankRoleCenterBankMgmtProcessPerfReview</p></td>
<td><p>Review bank management process performance through the role center.</p></td>
</tr>
<tr class="even">
<td><p>Role center URL redirection</p></td>
<td><p>EPHomePageView</p></td>
<td><p>Enable redirection from generic role center URL</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into customer positive payments</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>PaymCustPositivePayInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain positive payments</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>PaymPositivePayMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into vendor positive payments</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>PaymVendPositivePayInquire</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

  


