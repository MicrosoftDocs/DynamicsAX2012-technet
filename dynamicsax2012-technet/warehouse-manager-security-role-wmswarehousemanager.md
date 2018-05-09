---
title: Warehouse manager security role (WMSWarehouseManager)
TOCTitle: Warehouse manager security role (WMSWarehouseManager)
ms:assetid: 15050292-4252-40a2-9d11-ace82ce801d6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh527070(v=AX.60)
ms:contentKeyID: 37823122
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Warehouse manager security role (WMSWarehouseManager) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Warehouse manager security role represents a user who enables and reviews processes, authorizes recordings, maintains master data, and responds to inquiries within warehouse management.

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
<td><p>Inquire into inventory case progress</p></td>
<td><p>CaseInventoryCaseProgressInquire</p></td>
<td><p>Respond to inquiries about the status of inventory cases</p></td>
</tr>
<tr class="even">
<td><p>Inquire into products definition master</p></td>
<td><p>EcoResProductDefinitionMasterInquire</p></td>
<td><p>Respond to inquiries about products definition master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into products for operations master</p></td>
<td><p>EcoResProductForOperationsMasterInquire</p></td>
<td><p>Respond to inquiries about products for operations master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into product change cases</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>EngChgCaseInquire</p></td>
<td><p>Respond to inquiries about product change cases</p></td>
</tr>
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
<td><p>Approve inventory batch movements</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>InventBatchHandlingApprove</p></td>
<td><p>Approve inventory batch movement events</p></td>
</tr>
<tr class="even">
<td><p>Inquire into batch merges</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>InventBatchHandlingInquire</p></td>
<td><p>Respond to inquiries about merge operations on inventory batches</p></td>
</tr>
<tr class="odd">
<td><p>Approve inventory corrections</p></td>
<td><p>InventCorrectionsApprove</p></td>
<td><p>Approve inventory correction entries</p></td>
</tr>
<tr class="even">
<td><p>Approve production journal</p></td>
<td><p>InventJournalProductionPostingApprove</p></td>
<td><p>Document and record production entries in inventory journal</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into journal production progress</p></td>
<td><p>InventJournalProductionProgressInquire</p></td>
<td><p>Respond to inquiries about status of the journal production process</p></td>
</tr>
<tr class="even">
<td><p>Maintain inventory marking</p></td>
<td><p>InventMarkingMaintain</p></td>
<td><p>Document and record inventory marking</p></td>
</tr>
<tr class="odd">
<td><p>Approve movement journal</p></td>
<td><p>InventMovementUpdatesApprove</p></td>
<td><p>Approve movement entries in inventory journal</p></td>
</tr>
<tr class="even">
<td><p>Inquire into packing materials progress</p></td>
<td><p>InventPackMaterialsProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the packing materials process</p></td>
</tr>
<tr class="odd">
<td><p>Approve physical inventory counting</p></td>
<td><p>InventPhysicalInventoryCountingApprove</p></td>
<td><p>Approve counting of physical inventory in inventory journal</p></td>
</tr>
<tr class="even">
<td><p>Maintain release of picking requests</p></td>
<td><p>InventPickingRequestRelease</p></td>
<td><p>Release picking requests</p></td>
</tr>
<tr class="odd">
<td><p>Approve inventory adjustment journal</p></td>
<td><p>InventProfitLossUpdatesApprove</p></td>
<td><p>Approve profit and loss entries in inventory journal</p></td>
</tr>
<tr class="even">
<td><p>Inquire into quality control progress</p></td>
<td><p>InventQualityControlProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the quality control process</p></td>
</tr>
<tr class="odd">
<td><p>Enable receipt process</p></td>
<td><p>InventReceivingProcessEnable</p></td>
<td><p>Set up policies and reference data for the receipt process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into receipt operation progress</p></td>
<td><p>InventRecevingOperationProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the receipt operation process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into related inventory status</p></td>
<td><p>InventRelatedInventoryStatusInquire</p></td>
<td><p>Respond to inquiries about the status of the related inventory</p></td>
</tr>
<tr class="even">
<td><p>Inquire into RFID/barcode master</p></td>
<td><p>InventRFIDBarcodeMasterInquire</p></td>
<td><p>Respond to inquiries about RFID/barcode master data</p></td>
</tr>
<tr class="odd">
<td><p>Enable shipping process</p></td>
<td><p>InventShippingProcessEnable</p></td>
<td><p>Set up policies and reference data for the shipping process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into shipping progress</p></td>
<td><p>InventShippingProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the shipping process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into inventory status</p></td>
<td><p>InventStatusInquire</p></td>
<td><p>Respond to inquiries about the status of the inventory</p></td>
</tr>
<tr class="even">
<td><p>Inquire into tracking dimensions master</p></td>
<td><p>InventTrackingDimensionsMasterInquire</p></td>
<td><p>Respond to inquiries about tracking dimensions master data</p></td>
</tr>
<tr class="odd">
<td><p>Review warehouse process performance</p></td>
<td><p>InventWarehouseProcessPerformanceReview</p></td>
<td><p>Monitor, analyze, and improve the warehouse process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into materials kanban progress</p></td>
<td><p>KanbanExecutionMaterialsProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into kanban execution reference data</p></td>
<td><p>KanbanExecutionReferenceDataInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Enable the kanban rules management process</p></td>
<td><p>KanbanRulesManagementProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the kanban rule creation and maintenance</p></td>
</tr>
<tr class="odd">
<td><p>Set up picking processes</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRInventPickEnable</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into picking processes</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRInventPickInquire</p></td>
<td><p>Respond to inquiries about picking processes</p></td>
</tr>
<tr class="odd">
<td><p>Maintain packing operations master</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MCRWMSPackingOperationMasterMaintain</p></td>
<td><p>Maintain master data for packing operations</p></td>
</tr>
<tr class="even">
<td><p>Maintain inventory setup print management settings</p></td>
<td><p>PrintMgmtInventParametersSetupMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into safety stock levels</p></td>
<td><p>ReqSafetyStockProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain release of sales picking list</p></td>
<td><p>SalesPickingListRelease</p></td>
<td><p>Release sales picking list</p></td>
</tr>
<tr class="odd">
<td><p>Maintain shipping carrier master</p></td>
<td><p>ShipCarrierMasterMaintain</p></td>
<td><p>Maintain master data for shipping carriers</p></td>
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
<td><p>Inquire into units of measurement master</p></td>
<td><p>UnitOfMeasureMasterInquire</p></td>
<td><p>Respond to inquiries about units of measurement master data</p></td>
</tr>
<tr class="even">
<td><p>Maintain inventory status changes</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>WHSInventoryStatusChangesMaintain</p></td>
<td><p>Maintain inventory status changes</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into load planning progress</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>WHSLoadPlanningProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into reservation hierarchy</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>WHSReservationHierarchyMasterInquire</p></td>
<td><p>Inquire into reservation hierarchy</p></td>
</tr>
<tr class="odd">
<td><p>Record warehouse planning masters</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>WHSWarehousePlanningMasterMaintain</p></td>
<td><p>Maintain warehouse planning master</p></td>
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
<td><p>Maintain release of output order</p></td>
<td><p>WMSOutputOrderRelease</p></td>
<td><p>Release output orders</p></td>
</tr>
<tr class="even">
<td><p>Pallet movement process financial update</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>WMSPalletMovementProcess</p></td>
<td><p>Financially update pallet movements</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into pallets master</p></td>
<td><p>WMSPalletsMasterInquire</p></td>
<td><p>Respond to inquiries about pallets master data</p></td>
</tr>
<tr class="even">
<td><p>Maintain pallet transport handling</p></td>
<td><p>WMSPalletTransportHandlingMaintain</p></td>
<td><p>Document and record pallet transport handling</p></td>
</tr>
<tr class="odd">
<td><p>Maintain activation of shipments</p></td>
<td><p>WMSShipmentPickingTransportActivate</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain release of shipment reservations and generate picking routes</p></td>
<td><p>WMSShipmentReservationAndPickingRelease</p></td>
<td><p>Release warehouse shipments</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into warehouse operation master</p></td>
<td><p>WMSWarehouseOperationMasterInquire</p></td>
<td><p>Respond to inquiries about warehouse operation master data</p></td>
</tr>
<tr class="even">
<td><p>Maintain warehouse operation master</p></td>
<td><p>WMSWarehouseOperationMasterMaintain</p></td>
<td><p>Maintain master data for warehouse operations</p></td>
</tr>
<tr class="odd">
<td><p>Enable warehouse operation process</p></td>
<td><p>WMSWarehouseOperationProcessEnable</p></td>
<td><p>Set up policies and reference data for the warehouse operation process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into warehouse operation progress</p></td>
<td><p>WMSWarehouseOperationProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the warehouse operation process</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

