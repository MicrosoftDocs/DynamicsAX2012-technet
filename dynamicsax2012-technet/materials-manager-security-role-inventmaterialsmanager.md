---
title: Materials manager security role (InventMaterialsManager)
TOCTitle: Materials manager security role (InventMaterialsManager)
ms:assetid: 6627dd63-fd6a-4ebb-9719-fa47afbb2c47
ms:mtpsurl: https://technet.microsoft.com/library/Hh527100(v=AX.60)
ms:contentKeyID: 37823152
author: Khairunj
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Materials manager security role (InventMaterialsManager) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Materials manager security role represents a user who enables and reviews processes, maintains master data, and responds to inquiries related to logistics and material management.

## Duties

By default, this security role is assigned the following duties in Microsoft Dynamics AX.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Duty name</p></td>
<td><p>Duty AOT name</p></td>
<td><p>Duty description</p></td>
</tr>
<tr class="even">
<td><p>Inquire into inventory case progress</p></td>
<td><p>CaseInventoryCaseProgressInquire</p></td>
<td><p>Respond to inquiries about the status of inventory cases</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into products definition master</p></td>
<td><p>EcoResProductDefinitionMasterInquire</p></td>
<td><p>Respond to inquiries about products definition master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into products for operations master</p></td>
<td><p>EcoResProductForOperationsMasterInquire</p></td>
<td><p>Respond to inquiries about products for operations master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into product change cases</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>EngChgCaseInquire</p></td>
<td><p>Respond to inquiries about product change cases</p></td>
</tr>
<tr class="even">
<td><p>Inquire into demand forecasts</p></td>
<td><p>ForecastDemandForecastProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into forecasts</p></td>
<td><p>ForecastForecastProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into supply forecasts</p></td>
<td><p>ForecastSupplyForecastProgressInquire</p></td>
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
<td><p>Enable the logistic process</p></td>
<td><p>InventLogisticProcessEnable</p></td>
<td><p>Set up policies and reference data for the logistic process</p></td>
</tr>
<tr class="even">
<td><p>Enable packing material management process</p></td>
<td><p>InventPackMaterialManagementProcessEnab</p></td>
<td><p>Set up policies and reference data for the packing material management process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into packing materials progress</p></td>
<td><p>InventPackMaterialsProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the packing materials process</p></td>
</tr>
<tr class="even">
<td><p>View product types</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>InventProductTypeInquire_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into quality control progress</p></td>
<td><p>InventQualityControlProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the quality control process</p></td>
</tr>
<tr class="even">
<td><p>Review quality control process performance</p></td>
<td><p>InventQualityCtrlProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the quality control process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into related inventory status</p></td>
<td><p>InventRelatedInventoryStatusInquire</p></td>
<td><p>Respond to inquiries about the status of the related inventory</p></td>
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
<td><p>Review warehouse process performance</p></td>
<td><p>InventWarehouseProcessPerformanceReview</p></td>
<td><p>Monitor, analyze, and improve the warehouse process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into materials kanban progress</p></td>
<td><p>KanbanExecutionMaterialsProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Enable kanban execution process</p></td>
<td><p>KanbanExecutionProcessEnable</p></td>
<td><p>Set up policies and reference data to enable lean production and replenishment</p></td>
</tr>
<tr class="odd">
<td><p>Enable the kanban rules management process</p></td>
<td><p>KanbanRulesManagementProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the kanban rule creation and maintenance</p></td>
</tr>
<tr class="even">
<td><p>Inquire into kanban schedule status</p></td>
<td><p>KanbanScheduleStatusInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain production flow service master</p></td>
<td><p>LeanProductionFlowServiceMaintain</p></td>
<td><p>Document and record the services for subcontracted activities</p></td>
</tr>
<tr class="even">
<td><p>Review material consumption</p></td>
<td><p>ProdMaterialConsumptionPerfReview</p></td>
<td><p>Monitor, analyze, and improve material consumption performance</p></td>
</tr>
<tr class="odd">
<td><p>Enable master scheduling process</p></td>
<td><p>ReqMasterSchedulingProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the master scheduling process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into planned orders</p></td>
<td><p>ReqPlannedOrderProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Approve posting of safety stock levels</p></td>
<td><p>ReqSafetyStockLevelsPost</p></td>
<td><p>Journalize item coverage journals in order to set new safety stock levels</p></td>
</tr>
<tr class="even">
<td><p>View fiscal classification</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>TaxFiscalClassificationInquire_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>View service code</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>TaxServiceCodeInquire_BR</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain unit of measure master</p></td>
<td><p>UnitOfMeasureMasterMaintain</p></td>
<td><p>Maintain units of measure</p></td>
</tr>
<tr class="odd">
<td><p>Maintain inventory status changes</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>WHSInventoryStatusChangesMaintain</p></td>
<td><p>Maintain inventory status changes</p></td>
</tr>
<tr class="even">
<td><p>Set up reservation hierarchy</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>WHSReservationHierarchyMasterMaintain</p></td>
<td><p>Set up reservation hierarchy</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into warehouse operation progress</p></td>
<td><p>WMSWarehouseOperationProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the warehouse operation process</p></td>
</tr>
</tbody>
</table>

  


