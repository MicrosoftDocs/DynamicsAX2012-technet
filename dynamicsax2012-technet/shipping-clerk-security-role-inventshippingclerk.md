---
title: Shipping clerk security role (InventShippingClerk)
TOCTitle: Shipping clerk security role (InventShippingClerk)
ms:assetid: 9d6e722d-1da1-48b5-80c4-3857738a71ed
ms:mtpsurl: https://technet.microsoft.com/library/Hh527114(v=AX.60)
ms:contentKeyID: 37823165
author: Khairunj
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Shipping clerk security role (InventShippingClerk) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Shipping clerk security role represents a user who documents shipping operation events and responds to warehouse shipping operation inquiries.

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
<td><p>Role center URL redirection</p></td>
<td><p>EPHomePageView</p></td>
<td><p>Enable redirection from generic role center URL</p></td>
</tr>
<tr class="even">
<td><p>View fiscal document</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>FiscalDocumentInquire_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain fiscal document texts</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>FiscalDocumentTextMaintain_BR</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>View fiscal document texts</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>FiscalDocumentTextView_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain batch movements</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>InventBatchHandlingMaintain</p></td>
<td><p>Document inventory batch merge operations</p></td>
</tr>
<tr class="even">
<td><p>Inquire into quality control progress</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>InventQualityControlProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the quality control process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into related inventory status</p></td>
<td><p>InventRelatedInventoryStatusInquire</p></td>
<td><p>Respond to inquiries about the status of the related inventory</p></td>
</tr>
<tr class="even">
<td><p>Maintain RFID tracking</p></td>
<td><p>InventRFIDTrackingMaintain</p></td>
<td><p>Document and record RFID tracking</p></td>
</tr>
<tr class="odd">
<td><p>Approve shipping operations</p></td>
<td><p>InventShippingOperationApprove</p></td>
<td><p>Approve shipping and delivery operations</p></td>
</tr>
<tr class="even">
<td><p>Maintain shipping operations</p></td>
<td><p>InventShippingOperationMaintain</p></td>
<td><p>Document and record shipping operations</p></td>
</tr>
<tr class="odd">
<td><p>Maintain tracking dimensions master</p></td>
<td><p>InventTrackingDimensionsMasterMaintain</p></td>
<td><p>Maintain serial and batch numbers</p></td>
</tr>
<tr class="even">
<td><p>Maintain correction of serial numbers</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>InventTrackingRegisterCorrectionMaintain</p></td>
<td><p>Make corrections to serial numbers that were registered during the sales process</p></td>
</tr>
<tr class="odd">
<td><p>Maintain registration of unreadable serial numbers</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>InventTrackingRegisterUnknownMaintain</p></td>
<td><p>Register serial numbers as not readable as part of the sales process</p></td>
</tr>
<tr class="even">
<td><p>Maintain materials kanban execution</p></td>
<td><p>KanbanExecutionMaterialsMaintain</p></td>
<td><p>Document and record material replenishment execution for lean manufacturing</p></td>
</tr>
<tr class="odd">
<td><p>Maintain packing slip corrections</p></td>
<td><p>SalesPackingSlipCorrectionMaintain</p></td>
<td><p>Document and record sales packing slip corrections</p></td>
</tr>
<tr class="even">
<td><p>Inquire into shipping carrier master</p></td>
<td><p>ShipCarrierMasterInquire</p></td>
<td><p>Respond to inquiries about shipping carrier master data</p></td>
</tr>
<tr class="odd">
<td><p>Maintain sales pickup invoices</p></td>
<td><p>ShipCarrierSalesPickupInvoiceMaintain</p></td>
<td><p>Document and record sales pickup invoices</p></td>
</tr>
<tr class="even">
<td><p>Maintain license plate master</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>WHSLicensePlateMaintain</p></td>
<td><p>Maintain license plate master</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into warehouse planning status</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>WHSWarehousePlanningStatusInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain pallets master</p></td>
<td><p>WMSPalletsMasterMaintain</p></td>
<td><p>Maintain pallet numbers</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into warehouse operation progress</p></td>
<td><p>WMSWarehouseOperationProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the warehouse operation process</p></td>
</tr>
</tbody>
</table>

  


