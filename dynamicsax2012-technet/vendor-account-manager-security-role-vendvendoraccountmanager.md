---
title: Vendor account manager security role (VendVendorAccountManager)
TOCTitle: Vendor account manager security role (VendVendorAccountManager)
ms:assetid: d00d7e89-f1de-4700-9ccb-ff6e8d0c259e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh527136(v=AX.60)
ms:contentKeyID: 37823187
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Vendor account manager security role (VendVendorAccountManager) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Vendor account manager security role represents a user who documents vendor events and responds to vendor inquiries.

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
<td><p>Configure AIF synchronization</p></td>
<td><p>AifSyncConfigure</p></td>
<td><p>Allows specifying filters on ports</p></td>
</tr>
<tr class="even">
<td><p>Enable vendor process</p></td>
<td><p>VendVendorProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the vendor process</p></td>
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
<td><p>Inquire into employee-initiated vendor request status</p></td>
<td><p>VendRequestEmployeeVendorRequestInquire</p></td>
<td><p>Respond to inquiries about status on employee-initiated vendor requests</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into prospective vendor master</p></td>
<td><p>VendProspectiveVendorMasterInquire</p></td>
<td><p>Respond to inquiries about prospective vendor master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into request for quotation status</p></td>
<td><p>PurchRFQRequestForQuoteInquire</p></td>
<td><p>Respond to inquiries about the status of request for quotations</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into unsolicited vendor master</p></td>
<td><p>VendUnsolicitedVendorMasterInquire</p></td>
<td><p>Respond to inquiries about unsolicited vendor master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into vendor master</p></td>
<td><p>VendVendorMasterInquire</p></td>
<td><p>Respond to inquiries about vendor master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into vendor questionnaire progress</p></td>
<td><p>VendVendorQuestionnaireInquire</p></td>
<td><p>Respond to inquiries about vendor questionnaires</p></td>
</tr>
<tr class="even">
<td><p>Inquire into vendor-initiated request status</p></td>
<td><p>VendRequestVendorInitiateRequestInquire</p></td>
<td><p>Respond to inquiries about status on vendor-initiated requests</p></td>
</tr>
<tr class="odd">
<td><p>Maintain cases</p></td>
<td><p>CaseCasesMaintain</p></td>
<td><p>Maintain cases</p></td>
</tr>
<tr class="even">
<td><p>Maintain contacts</p></td>
<td><p>smmContactsMaintain</p></td>
<td><p>Configure and maintain contacts</p></td>
</tr>
<tr class="odd">
<td><p>Maintain document services operation which lets you send</p></td>
<td><p>PurchRFQFormLetterSendProcessMaintain</p></td>
<td><p>Receive RFQ</p></td>
</tr>
<tr class="even">
<td><p>Maintain purchasing cases</p></td>
<td><p>CasePurchasingCasesMaintain</p></td>
<td><p>Maintain purchasing cases</p></td>
</tr>
<tr class="odd">
<td><p>Maintain sites service solution and online pages available in procurement and sourcing area</p></td>
<td><p>PurchRFQSolutionMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain vendor hold status</p></td>
<td><p>VendOnHoldUpdate</p></td>
<td><p>Maintain vendor hold status</p></td>
</tr>
<tr class="odd">
<td><p>Review case process</p></td>
<td><p>CaseCaseProcessReview</p></td>
<td><p>Monitor, analyze, and improve the case process</p></td>
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
</tbody>
</table>

  


