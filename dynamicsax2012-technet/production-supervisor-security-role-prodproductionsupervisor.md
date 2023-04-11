---
title: Production supervisor security role (ProdProductionSupervisor)
TOCTitle: Production supervisor security role (ProdProductionSupervisor)
ms:assetid: c1a0a090-1c54-4cd1-b377-f1dab88c918f
ms:mtpsurl: https://technet.microsoft.com/library/Hh527133(v=AX.60)
ms:contentKeyID: 37823184
author: tonyafehr
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Production supervisor security role (ProdProductionSupervisor) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Production supervisor security role represents a user who enables the production process.

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
<td><p>Maintain activation of BOMs</p></td>
<td><p>BOMBillsOfMaterialsActivationMaintain</p></td>
<td><p>Document and record activation of BOMs</p></td>
</tr>
<tr class="even">
<td><p>Inquire into BOM master</p></td>
<td><p>BOMBillsOfMaterialsMasterInquire</p></td>
<td><p>Respond to inquiries about BOM master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into production case progress</p></td>
<td><p>CaseProductionCaseProgressInquire</p></td>
<td><p>Respond to inquiries about the status of production cases</p></td>
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
<td><p>Role center URL redirection</p></td>
<td><p>EPHomePageView</p></td>
<td><p>Enable redirection from generic Role center URL</p></td>
</tr>
<tr class="odd">
<td><p>Maintain on-hand inventory reservations</p></td>
<td><p>InventOnHandReservationMaintain</p></td>
<td><p>Document and record on-hand inventory reservations</p></td>
</tr>
<tr class="even">
<td><p>Inquire into inventory status</p></td>
<td><p>InventStatusInquire</p></td>
<td><p>Respond to inquiries about the status of the inventory</p></td>
</tr>
<tr class="odd">
<td><p>Approve indirect activity costs</p></td>
<td><p>JmgActivityCostsPost</p></td>
<td><p>Authorize the posting of indirect activity costs</p></td>
</tr>
<tr class="even">
<td><p>Maintain flex time process</p></td>
<td><p>JmgFlexProcessMaintain</p></td>
<td><p>Document and record the flex time registration process</p></td>
</tr>
<tr class="odd">
<td><p>Maintain job approvals</p></td>
<td><p>JmgJobApprovalMaintain</p></td>
<td><p>Document and record the job approval process</p></td>
</tr>
<tr class="even">
<td><p>Maintain job assignments</p></td>
<td><p>JmgJobAssignmentsMaintain</p></td>
<td><p>Document and record job assignments</p></td>
</tr>
<tr class="odd">
<td><p>Maintain job calculations</p></td>
<td><p>JmgJobCalculationMaintain</p></td>
<td><p>Document and record job calculations</p></td>
</tr>
<tr class="even">
<td><p>Maintain job corrections</p></td>
<td><p>JmgJobCorrectionsMaintain</p></td>
<td><p>Document and record job corrections</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into manufacturing execution progress</p></td>
<td><p>JmgManufacturingExecutionProgressInquir</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain messages</p></td>
<td><p>JmgNoticeBoardMaintain</p></td>
<td><p>Document and record the messages functionality</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into time and attendance progress</p></td>
<td><p>JmgTimeAttendanceProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain time and attendance profiles</p></td>
<td><p>JmgTimeAttendenceProfilesMaintain</p></td>
<td><p>Document and record Time and attendance work time profiles</p></td>
</tr>
<tr class="odd">
<td><p>Maintain time supervision</p></td>
<td><p>JmgTimeSupervisionMaintain</p></td>
<td><p>Document and record time supervision in Time and attendance</p></td>
</tr>
<tr class="even">
<td><p>Enable kanban execution process</p></td>
<td><p>KanbanExecutionProcessEnable</p></td>
<td><p>Set up policies and reference data to enable lean production and replenishment</p></td>
</tr>
<tr class="odd">
<td><p>Maintain service receipts kanban execution</p></td>
<td><p>KanbanExecutionServiceReceiptsMaintain</p></td>
<td><p>Generate and maintain service receipts for lean manufacturing</p></td>
</tr>
<tr class="even">
<td><p>Maintain kanban rules master</p></td>
<td><p>KanbanRulesMasterMaintain</p></td>
<td><p>Document and record kanban rules</p></td>
</tr>
<tr class="odd">
<td><p>Maintain kanban purchase orders schedule</p></td>
<td><p>KanbanSchedulePurchaseOrdersMaintain</p></td>
<td><p>Generate and maintain the purchase orders for subcontracting services in lean manufacturing</p></td>
</tr>
<tr class="even">
<td><p>Maintain production order completion</p></td>
<td><p>ProdProductionOrderCompletionMaintain</p></td>
<td><p>Document and record production order completion</p></td>
</tr>
<tr class="odd">
<td><p>Maintain production orders</p></td>
<td><p>ProdProductionOrderMaintain</p></td>
<td><p>Document and record production orders</p></td>
</tr>
<tr class="even">
<td><p>Maintain production order preparation</p></td>
<td><p>ProdProductionOrderPreparationMaintain</p></td>
<td><p>Document and record production order preparation</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into production orders</p></td>
<td><p>ProdProductionOrderProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain release of production orders</p></td>
<td><p>ProdProductionOrderReleaseMaintain</p></td>
<td><p>Document and record production order release</p></td>
</tr>
<tr class="odd">
<td><p>Maintains production scheduling</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ProdProductionSchedulingMaintain</p></td>
<td><p>Maintains the scheduling of jobs and operations for production orders</p></td>
</tr>
<tr class="even">
<td><p>Inquire into planned orders</p></td>
<td><p>ReqPlannedOrderProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into route master</p></td>
<td><p>RouteRouteMasterInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain license plate master</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>WHSLicensePlateStatusInquire</p></td>
<td><p>Maintain license plate master</p></td>
</tr>
<tr class="odd">
<td><p>Maintain kanban wave transactions</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>WHSWarehousePlanningKanbanMaintain</p></td>
<td><p>Maintain kanban wave transactions</p></td>
</tr>
<tr class="even">
<td><p>Maintain production waves</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>WHSWarehousePlanningProdMaintain</p></td>
<td><p>Maintain production waves</p></td>
</tr>
<tr class="odd">
<td><p>Maintain calendar master</p></td>
<td><p>WorkCalendarMasterMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into resource capacity</p></td>
<td><p>WrkCtrResourceCapacityStatusInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain resource master</p></td>
<td><p>WrkCtrResourcesMasterMaintain</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

  


