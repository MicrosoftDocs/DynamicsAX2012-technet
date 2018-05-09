---
title: Production planner security role (ReqProductionPlanner)
TOCTitle: Production planner security role (ReqProductionPlanner)
ms:assetid: 92417a0c-f66d-4375-950e-f30863da0921
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh527112(v=AX.60)
ms:contentKeyID: 37823163
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Production planner security role (ReqProductionPlanner) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Production planner security role represents a user who schedules and plans production.

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
<td><p>Inquire into inventory case progress</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>CaseInventoryCaseProgressInquire</p></td>
<td><p>Respond to inquiries about the status of inventory cases</p></td>
</tr>
<tr class="even">
<td><p>Inquire into production case progress</p></td>
<td><p>CaseProductionCaseProgressInquire</p></td>
<td><p>Respond to inquiries about the status of production cases</p></td>
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
<td><p>Maintain demand forecasts</p></td>
<td><p>ForecastDemandForecastMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain forecasts</p></td>
<td><p>ForecastForecastMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain forecast scheduling</p></td>
<td><p>ForecastForecastSchedulingMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain supply forecasts</p></td>
<td><p>ForecastSupplyForecastMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into intercompany planning policies</p></td>
<td><p>IntercompanyPlanningPoliciesInquire</p></td>
<td><p>View reference data for the intercompany master scheduling process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into manufacturing execution progress</p></td>
<td><p>JmgManufacturingExecutionProgressInquir</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into materials kanban progress</p></td>
<td><p>KanbanExecutionMaterialsProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into production kanban progress</p></td>
<td><p>KanbanExecutionProductionProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into sales events kanban progress</p></td>
<td><p>KanbanExecutionSalesEvtsProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain kanban rules master</p></td>
<td><p>KanbanRulesMasterMaintain</p></td>
<td><p>Document and record kanban rules</p></td>
</tr>
<tr class="even">
<td><p>Maintain kanban schedule</p></td>
<td><p>KanbanScheduleMaintain</p></td>
<td><p>Maintain the work cell schedules for lean manufacturing</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into production flow master</p></td>
<td><p>LeanProductionFlowMasterInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into production orders</p></td>
<td><p>ProdProductionOrderProgressInquire</p></td>
<td><p></p></td>
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
<td><p>Maintain calculation of accuracy of demand forecasts</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ReqDemPlanAccuracyReviewMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain generation of baseline demand forecasts</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ReqDemPlanGenerateMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain import of adjusted demand forecasts</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ReqDemPlanImportMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain performance of demand forecasting process</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ReqDemPlanPerformanceReview</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain the master for demand forecasting parameters</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ReqDemPlanSetupMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain master scheduling</p></td>
<td><p>ReqMasterSchedulingMaintain</p></td>
<td><p>Document and record master scheduling</p></td>
</tr>
<tr class="even">
<td><p>Maintain firming of planned orders</p></td>
<td><p>ReqPlannedOrderFirmingMaintain</p></td>
<td><p>Document and record planned order firming</p></td>
</tr>
<tr class="odd">
<td><p>Maintain planned orders</p></td>
<td><p>ReqPlannedOrdersMaintain</p></td>
<td><p>Document and record planned orders</p></td>
</tr>
<tr class="even">
<td><p>Maintain safety stock levels</p></td>
<td><p>ReqSafetyStockLevelsMaintain</p></td>
<td><p>Document and record safety stock levels</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into resource capacity</p></td>
<td><p>WrkCtrResourceCapacityStatusInquire</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

