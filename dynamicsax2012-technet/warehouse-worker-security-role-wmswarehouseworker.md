---
title: Warehouse worker security role (WMSWarehouseWorker)
TOCTitle: Warehouse worker security role (WMSWarehouseWorker)
ms:assetid: 23fdff2b-e57e-45d2-96da-5736c484d467
ms:mtpsurl: https://technet.microsoft.com/library/Hh527075(v=AX.60)
ms:contentKeyID: 37823127
author: Khairunj
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Warehouse worker security role (WMSWarehouseWorker) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Warehouse worker security role represents a user who documents warehouse operation events and responds to warehouse operation inquiries.

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
<td><p>Maintain inventory corrections</p></td>
<td><p>InventCorrectionsMaintain</p></td>
<td><p>Document and record inventory corrections</p></td>
</tr>
<tr class="odd">
<td><p>Maintain production journal</p></td>
<td><p>InventJournalProductionMaintain</p></td>
<td><p>Document and record production entries in inventory journal</p></td>
</tr>
<tr class="even">
<td><p>Maintain movement journal</p></td>
<td><p>InventMovementUpdatesMaintain</p></td>
<td><p>Document and record movement entries in inventory journal</p></td>
</tr>
<tr class="odd">
<td><p>Maintain on-hand inventory reservations</p></td>
<td><p>InventOnHandReservationMaintain</p></td>
<td><p>Document and record on-hand inventory reservations</p></td>
</tr>
<tr class="even">
<td><p>Maintain packing materials</p></td>
<td><p>InventPackMaterialsMaintain</p></td>
<td><p>Document and record packing materials</p></td>
</tr>
<tr class="odd">
<td><p>Maintain physical inventory blocking</p></td>
<td><p>InventPhysicalInventoryBlockingMaintain</p></td>
<td><p>Document and record physical inventory blocking</p></td>
</tr>
<tr class="even">
<td><p>Maintain physical inventory counting</p></td>
<td><p>InventPhysicalInventoryCountingMaintain</p></td>
<td><p>Document and record physical inventory counting</p></td>
</tr>
<tr class="odd">
<td><p>Maintain inventory picking</p></td>
<td><p>InventPickingMaintain</p></td>
<td><p>Document and record inventory picking</p></td>
</tr>
<tr class="even">
<td><p>Maintain inventory adjustment journal entries</p></td>
<td><p>InventProfitLossUpdatesMaintain</p></td>
<td><p>Document and record adjustment entries in inventory adjustment journal</p></td>
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
<td><p>Maintain tracking dimensions master</p></td>
<td><p>InventTrackingDimensionsMasterMaintain</p></td>
<td><p>Maintain serial and batch numbers</p></td>
</tr>
<tr class="even">
<td><p>Approve inventory transfers</p></td>
<td><p>InventTransfersApprove</p></td>
<td><p>Approve inventory transfer entries</p></td>
</tr>
<tr class="odd">
<td><p>Maintain inventory transfers</p></td>
<td><p>InventTransfersMaintain</p></td>
<td><p>Document and record inventory transfers</p></td>
</tr>
<tr class="even">
<td><p>Maintain materials kanban execution</p></td>
<td><p>KanbanExecutionMaterialsMaintain</p></td>
<td><p>Document and record material replenishment execution for lean manufacturing</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into picking processes</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRInventPickInquire</p></td>
<td><p>Respond to inquiries about picking processes</p></td>
</tr>
<tr class="even">
<td><p>Inquire into packing operations master</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRWMSPackingOperationMasterInquire</p></td>
<td><p>Inquire into master data for packing operations</p></td>
</tr>
<tr class="odd">
<td><p>Maintain sales pickup shipments</p></td>
<td><p>ShipCarrierSalesPickupShipmentsMaintain</p></td>
<td><p>Document and record sales pickup shipments</p></td>
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
<td><p>Maintain license plate master</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>WHSLicensePlateMaintain</p></td>
<td><p>Maintain license plate master</p></td>
</tr>
<tr class="even">
<td><p>Inquire into warehouse planning status</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>WHSWarehousePlanningStatusInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain pallets master</p></td>
<td><p>WMSPalletsMasterMaintain</p></td>
<td><p>Maintain pallet numbers</p></td>
</tr>
<tr class="even">
<td><p>Maintain pallet warehouse operations</p></td>
<td><p>WMSPalletWarehouseOperationsMaintain</p></td>
<td><p>Document and record pallet warehouse operations</p></td>
</tr>
<tr class="odd">
<td><p>Maintain physical quantity adjustment</p></td>
<td><p>WMSPhysicalQuantityAdjustmentMaintain</p></td>
<td><p>Document and record physical quantity adjustment</p></td>
</tr>
<tr class="even">
<td><p>Inquire into warehouse operation progress</p></td>
<td><p>WMSWarehouseOperationProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the warehouse operation process</p></td>
</tr>
<tr class="odd">
<td><p>Maintain warehouse picking operations</p></td>
<td><p>WMSWarehousePickingOperationMaintain</p></td>
<td><p>Document and record warehouse picking operations</p></td>
</tr>
</tbody>
</table>

  


