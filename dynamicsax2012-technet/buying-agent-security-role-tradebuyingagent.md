---
title: Buying agent security role (TradeBuyingAgent)
TOCTitle: Buying agent security role (TradeBuyingAgent)
ms:assetid: b226b369-9fad-411b-868e-afd66884d4d2
ms:mtpsurl: https://technet.microsoft.com/library/Hh527123(v=AX.60)
ms:contentKeyID: 37823174
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Buying agent security role (TradeBuyingAgent) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Buying agent security role represents a user who documents purchase events and responds to purchase inquiries.

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
<td><p>Inquire into import letter of credit</p></td>
<td><p>BankImportLetterOfCreditInquire</p></td>
<td><p>Respond to inquiries about the status of import letters of credit</p></td>
</tr>
<tr class="even">
<td><p>Inquire into products definition master</p></td>
<td><p>EcoResProductDefinitionMasterInquire</p></td>
<td><p>Respond to inquiries about products definition master data</p></td>
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
<td><p>Inquire into purchase requisition consolidation</p></td>
<td><p>PurchReqConsolidationReview</p></td>
<td><p>Respond to inquiries about the status of the purchase requisition consolidation process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into quality control progress</p></td>
<td><p>InventQualityControlProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the quality control process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into related inventory status</p></td>
<td><p>InventRelatedInventoryStatusInquire</p></td>
<td><p>Respond to inquiries about the status of the related inventory</p></td>
</tr>
<tr class="even">
<td><p>Inquire into vendor master</p></td>
<td><p>VendVendorMasterInquire</p></td>
<td><p>Respond to inquiries about vendor master data</p></td>
</tr>
<tr class="odd">
<td><p>Maintain CTP</p></td>
<td><p>ReqCtpMaintain</p></td>
<td><p>Document and record capable to promise (CTP) calculations</p></td>
</tr>
<tr class="even">
<td><p>Maintain firming of planned purchase orders</p></td>
<td><p>ReqPlannedPurchaseOrderFirmingMaintain</p></td>
<td><p>Document and record planned purchase order firming</p></td>
</tr>
<tr class="odd">
<td><p>Maintain import letter of credit</p></td>
<td><p>BankImportLetterOfCreditMaintain</p></td>
<td><p>Document and record import letter of credit business events</p></td>
</tr>
<tr class="even">
<td><p>Maintain inventory marking</p></td>
<td><p>InventMarkingMaintain</p></td>
<td><p>Document and record inventory marking</p></td>
</tr>
<tr class="odd">
<td><p>Maintain inventory picking</p></td>
<td><p>InventPickingMaintain</p></td>
<td><p>Document and record inventory picking</p></td>
</tr>
<tr class="even">
<td><p>Maintain inventory registration</p></td>
<td><p>InventRegistrationMaintain</p></td>
<td><p>Document and record inventory registration</p></td>
</tr>
<tr class="odd">
<td><p>Maintain on-hand inventory reservations</p></td>
<td><p>InventOnHandReservationMaintain</p></td>
<td><p>Document and record on-hand inventory reservations</p></td>
</tr>
<tr class="even">
<td><p>Maintain planned purchase orders</p></td>
<td><p>ReqPlannedPurchaseOrdersMaintain</p></td>
<td><p>Document and record planned purchase orders</p></td>
</tr>
<tr class="odd">
<td><p>Maintain product receipt</p></td>
<td><p>PurchPackingSlipMaintain</p></td>
<td><p>Document and record product receipt</p></td>
</tr>
<tr class="even">
<td><p>Maintain product receipt corrections</p></td>
<td><p>PurchPackingSlipCorrectionMaintain</p></td>
<td><p>Document and record product receipt corrections</p></td>
</tr>
<tr class="odd">
<td><p>Maintain purchase order release from agreements</p></td>
<td><p>PurchaseAgreementReleasePurchaseOrder</p></td>
<td><p>Maintain purchase order release from agreements</p></td>
</tr>
<tr class="even">
<td><p>Maintain purchase orders</p></td>
<td><p>PurchOrderMaintain</p></td>
<td><p>Document and record purchase order</p></td>
</tr>
<tr class="odd">
<td><p>Maintain purchase requisition consolidation</p></td>
<td><p>PurchReqConsolidationMaintain</p></td>
<td><p>Maintain the purchase requisition consolidation process</p></td>
</tr>
<tr class="even">
<td><p>Maintain rejected confirmation of product receipts</p></td>
<td><p>EPPurchCORConfOfReceiptsRejectMaintain</p></td>
<td><p>Document and record rejected confirmation of product receipts</p></td>
</tr>
<tr class="odd">
<td><p>Maintain release of output order</p></td>
<td><p>WMSOutputOrderRelease</p></td>
<td><p>Release output orders</p></td>
</tr>
<tr class="even">
<td><p>Role center URL redirection</p></td>
<td><p>EPHomePageView</p></td>
<td><p>Enable redirection from generic role center URL</p></td>
</tr>
<tr class="odd">
<td><p>View fiscal document source texts</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2.</P>


</div></td>
<td><p>FiscalDocumentSourceTextView_BR</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## Privileges

In Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack, no privileges are directly assigned to this role.

In Microsoft Dynamics AX 2012 R2, this security role is assigned the following privilege by default.

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
<td><p>Maintain assessable value form</p></td>
<td><p>CustomsImportAssessableValueMaintain_IN</p></td>
</tr>
</tbody>
</table>

  


