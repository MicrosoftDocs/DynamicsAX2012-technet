---
title: Production manager security role (ProdProductionManager)
TOCTitle: Production manager security role (ProdProductionManager)
ms:assetid: ce34f062-0018-4bf4-ab9c-5a6c85dc092e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh527135(v=AX.60)
ms:contentKeyID: 37823186
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Production manager security role (ProdProductionManager) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Production manager security role represents a user who reviews the production plan and ensures the proper resources are available.

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
<td><p>Inquire into BOM calculations</p></td>
<td><p>BOMBillsOfMaterialsCalcStatusInquire</p></td>
<td><p>Inquire into BOM calculations</p></td>
</tr>
<tr class="even">
<td><p>Inquire into BOM master</p></td>
<td><p>BOMBillsOfMaterialsMasterInquire</p></td>
<td><p>Respond to inquiries about BOM master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into BOM management policies</p></td>
<td><p>BOMBillsOfMaterialsMgmtPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing BOM management</p></td>
</tr>
<tr class="even">
<td><p>Review case process</p></td>
<td><p>CaseCaseProcessReview</p></td>
<td><p>Monitor, analyze, and improve the case process</p></td>
</tr>
<tr class="odd">
<td><p>Maintain cases</p></td>
<td><p>CaseCasesMaintain</p></td>
<td><p>Maintain cases</p></td>
</tr>
<tr class="even">
<td><p>Maintain production cases</p></td>
<td><p>CaseProductionCasesMaintain</p></td>
<td><p>Maintain production cases</p></td>
</tr>
<tr class="odd">
<td><p>Approve and activate product changes</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>EngChgCaseApproveAndActivate</p></td>
<td><p>Authorize changes related to a product change case</p></td>
</tr>
<tr class="even">
<td><p>Inquire into product change cases</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>EngChgCaseInquire</p></td>
<td><p>Respond to inquiries about product change cases</p></td>
</tr>
<tr class="odd">
<td><p>Maintain product change cases</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>EngChgCaseMaintain</p></td>
<td><p>Create and update product change cases</p></td>
</tr>
<tr class="even">
<td><p>Role center URL redirection</p></td>
<td><p>EPHomePageView</p></td>
<td><p>Enable redirection from generic Role center URL</p></td>
</tr>
<tr class="odd">
<td><p>Enable forecast process</p></td>
<td><p>ForecastForecastProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the forecast work process</p></td>
</tr>
<tr class="even">
<td><p>Review forecast performance</p></td>
<td><p>ForecastForecastProcessPerformanceRevie</p></td>
<td><p>Monitor, analyze, and improve forecast process performance</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into limited worker information</p></td>
<td><p>HcmLimitedWorkerInquire</p></td>
<td><p>Respond to inquiries about limited worker information</p></td>
</tr>
<tr class="even">
<td><p>Enable intercompany planning process</p></td>
<td><p>IntercompanyPlanningProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the intercompany master scheduling process</p></td>
</tr>
<tr class="odd">
<td><p>Approve inventory batch movements</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>InventBatchHandlingApprove</p></td>
<td><p>Approve inventory batch movement events</p></td>
</tr>
<tr class="even">
<td><p>Inquire into batch merges</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>InventBatchHandlingInquire</p></td>
<td><p>Respond to inquiries about merge operations on inventory batches</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into inventory status</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>InventStatusInquire</p></td>
<td><p>Respond to inquiries about the status of the inventory</p></td>
</tr>
<tr class="even">
<td><p>Maintain indirect activity costs master</p></td>
<td><p>JmgIndirectActivityCostMasterMaintain</p></td>
<td><p>Maintain indirect activity costs master</p></td>
</tr>
<tr class="odd">
<td><p>Maintain indirect activities master</p></td>
<td><p>JmgIndirectActivityMasterMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Enable manufacturing execution process</p></td>
<td><p>JmgManufacturingExecutionProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the manufacturing execution</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into manufacturing execution progress</p></td>
<td><p>JmgManufacturingExecutionProgressInquir</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Enable time and attendance process</p></td>
<td><p>JmgTimeAttendanceProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the time and attendance process</p></td>
</tr>
<tr class="odd">
<td><p>Review time and attendance process performance</p></td>
<td><p>JmgTimeAttendanceProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the Time and attendance process</p></td>
</tr>
<tr class="even">
<td><p>Maintain time and attendance profiles</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>JmgTimeAttendenceProfilesMaintain</p></td>
<td><p>Document and record Time and attendance work time profiles</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into materials kanban progress</p></td>
<td><p>KanbanExecutionMaterialsProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into production kanban progress</p></td>
<td><p>KanbanExecutionProductionProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into kanban execution reference data</p></td>
<td><p>KanbanExecutionReferenceDataInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into sales events kanban progress</p></td>
<td><p>KanbanExecutionSalesEvtsProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Enable the kanban rules management process</p></td>
<td><p>KanbanRulesManagementProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the kanban rule creation and maintenance</p></td>
</tr>
<tr class="even">
<td><p>Enable the kanban scheduling process</p></td>
<td><p>KanbanScheduleProcessEnable</p></td>
<td><p>Set up policies and reference data to enable scheduling for lean manufacturing</p></td>
</tr>
<tr class="odd">
<td><p>Maintain activation of production flows</p></td>
<td><p>LeanProductionFlowActivationMaintain</p></td>
<td><p>Document and record the activation of production flow versions</p></td>
</tr>
<tr class="even">
<td><p>Enable the production flow management process</p></td>
<td><p>LeanProductionFlowMgmtProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the production flow modeling</p></td>
</tr>
<tr class="odd">
<td><p>Maintain production flow service master</p></td>
<td><p>LeanProductionFlowServiceMaintain</p></td>
<td><p>Document and record the services for subcontracted activities</p></td>
</tr>
<tr class="even">
<td><p>Maintain and configure organizational model</p></td>
<td><p>OMOrganizationsMaintain</p></td>
<td><p>Create or update organizations and organization hierarchies</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into production cost calculations</p></td>
<td><p>ProdProductionCostCalcStatusInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into production orders</p></td>
<td><p>ProdProductionOrderProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Enable production process</p></td>
<td><p>ProdProductionProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the production process</p></td>
</tr>
<tr class="even">
<td><p>Review production process</p></td>
<td><p>ProdProductionProcessPerformanceReview</p></td>
<td><p>Monitor, analyze, and improve production process performance</p></td>
</tr>
<tr class="odd">
<td><p>Review performance of demand forecasting process</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ReqDemPlanPerformanceReview</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Enable the demand forecasting process</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ReqDemPlanProcessEnable</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Enable master scheduling process</p></td>
<td><p>ReqMasterSchedulingProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the master scheduling process</p></td>
</tr>
<tr class="even">
<td><p>Review master scheduling performance</p></td>
<td><p>ReqMasterSchedulingProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve master scheduling performance</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into master scheduling statistics</p></td>
<td><p>ReqMasterSchedulingStatusInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into planned orders</p></td>
<td><p>ReqPlannedOrderProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into requirement profiles</p></td>
<td><p>ReqRequirementsProfileProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into safety stock levels</p></td>
<td><p>ReqSafetyStockProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into route management reference data</p></td>
<td><p>RouteRouteManagementReferenceDataInquir</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into route master</p></td>
<td><p>RouteRouteMasterInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into kanban wave operations</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>WHSWarehousePlanningKanbanStatusInquire</p></td>
<td><p>Inquire into kanban wave operations</p></td>
</tr>
<tr class="even">
<td><p>Inquire into production</p>
<div>

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>WHSWarehousePlanningProdStatusInquire</p></td>
<td><p>Inquire into production</p></td>
</tr>
<tr class="odd">
<td><p>Maintain calendar master</p></td>
<td><p>WorkCalendarMasterMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Enable calendar management process</p></td>
<td><p>WorkCalendarsEnable</p></td>
<td><p>Set up policies and reference data to enable the use of calendars</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into resource capacity</p></td>
<td><p>WrkCtrResourceCapacityStatusInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Enable resource management process</p></td>
<td><p>WrkCtrResourceManagementProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the resource management process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into resource master</p></td>
<td><p>WrkCtrResourcesMasterInquire</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

