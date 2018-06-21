---
title: Project supervisor security role (ProjProjectSupervisor)
TOCTitle: Project supervisor security role (ProjProjectSupervisor)
ms:assetid: 5dfc2c06-5efa-40bf-90c0-9bf98668b7df
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh527094(v=AX.60)
ms:contentKeyID: 37823146
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Project supervisor security role (ProjProjectSupervisor) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Project supervisor security role represents a user who enables and reviews the project accounting process.

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
<td><p>Inquire into customer master</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>CustCustomerMasterInquire</p></td>
<td><p>Respond to inquiries about customer master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into product change cases</p></td>
<td><p>EngChgCaseInquire</p></td>
<td><p>Respond to inquiries about product change cases</p></td>
</tr>
<tr class="odd">
<td><p>Role center URL redirection</p></td>
<td><p>EPHomePageView</p></td>
<td><p>Enable redirection from generic role center URL</p></td>
</tr>
<tr class="even">
<td><p>Maintain invoice cancellation proposals</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MaintainInvoiceCancellationProposals_BR</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain project document print management settings</p></td>
<td><p>PrintMgmtProjectDocumentSettingsMaintain</p></td>
<td><p>Maintain project document print management settings.</p></td>
</tr>
<tr class="even">
<td><p>Maintain project setup print management settings</p></td>
<td><p>PrintMgmtProjectSettingsMaintain</p></td>
<td><p>Maintain project setup print management settings</p></td>
</tr>
<tr class="odd">
<td><p>Maintains production scheduling</p></td>
<td><p>ProdProductionSchedulingMaintain</p></td>
<td><p>Maintains the scheduling of jobs and operations for production orders</p></td>
</tr>
<tr class="even">
<td><p>Inquire into project activity master</p></td>
<td><p>ProjActivityMasterInquire</p></td>
<td><p>Respond to inquiries about project activity hierarchy master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into project activity cost tracking master</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ProjActivityMasterInquireCostTracking</p></td>
<td><p>View the cost tracking view of activity hierarchy</p></td>
</tr>
<tr class="even">
<td><p>Inquire into project activity effort tracking master</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ProjActivityMasterInquireEffortTracking</p></td>
<td><p>View the effort tracking view of activity hierarchy</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into estimate project master</p></td>
<td><p>ProjEstimateProjectMasterInquire</p></td>
<td><p>Respond to inquiries about estimate project master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into grant master</p></td>
<td><p>ProjGrantMasterInquireInquire</p></td>
<td><p>Respond to inquiries about grant master information</p></td>
</tr>
<tr class="odd">
<td><p>Enable project accounting process</p></td>
<td><p>ProjProjectAccountingProcessEnable</p></td>
<td><p>Set up policies and reference information to enable the project accounting process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into project accounting reference data</p></td>
<td><p>ProjProjectAccountingReferenceDataInqui</p></td>
<td><p>Respond to inquiries about project accounting reference information</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into project budgets</p></td>
<td><p>ProjProjectBudgetInquire</p></td>
<td><p>Respond to inquiries about project budget master information</p></td>
</tr>
<tr class="even">
<td><p>Inquire into project category master</p></td>
<td><p>ProjProjectCategoriesMasterInquire</p></td>
<td><p>Respond to inquiries about project category master information</p></td>
</tr>
<tr class="odd">
<td><p>Maintain project category master</p></td>
<td><p>ProjProjectCategoriesMasterMaintain</p></td>
<td><p>Maintain master information about project categories</p></td>
</tr>
<tr class="even">
<td><p>Inquire into project contract master</p></td>
<td><p>ProjProjectContractMasterInquire</p></td>
<td><p>Respond to inquiries about project contract master information</p></td>
</tr>
<tr class="odd">
<td><p>Review project control - cash flow</p></td>
<td><p>ProjProjectControlCashFlowReview</p></td>
<td><p>Monitor forecasted and actual project cash flow</p></td>
</tr>
<tr class="even">
<td><p>Review project control - committed cost</p></td>
<td><p>ProjProjectControlCommittedCostReview</p></td>
<td><p>Monitor the costs of a project or a set of projects</p></td>
</tr>
<tr class="odd">
<td><p>Review project control - hour utilization</p></td>
<td><p>ProjProjectControlHourUtilizationReview</p></td>
<td><p>Monitor the utilization and efficiency of assigned project hours</p></td>
</tr>
<tr class="even">
<td><p>Review project control - invoice control</p></td>
<td><p>ProjProjectControlInvoiceControlReview</p></td>
<td><p>Monitor posted project transactions</p></td>
</tr>
<tr class="odd">
<td><p>Review project control</p></td>
<td><p>ProjProjectControlReview</p></td>
<td><p>Monitor project hour utilization and efficiency</p></td>
</tr>
<tr class="even">
<td><p>Review project control - statement</p></td>
<td><p>ProjProjectControlStatementReview</p></td>
<td><p>Monitor project control statement reports</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into project groups master</p></td>
<td><p>ProjProjectGroupsMasterInquire</p></td>
<td><p>Respond to inquiries about project groups master information</p></td>
</tr>
<tr class="even">
<td><p>Inquire into project invoices</p></td>
<td><p>ProjProjectInvoiceInquire</p></td>
<td><p>Respond to inquiries about project invoice master information</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into project master</p></td>
<td><p>ProjProjectMasterInquire</p></td>
<td><p>Respond to inquiries about project master information</p></td>
</tr>
<tr class="even">
<td><p>Inquire into project timesheet delegates</p></td>
<td><p>ProjProjectTimesheetDelegatesInquire</p></td>
<td><p>Respond to inquiries about project timesheet delegates</p></td>
</tr>
<tr class="odd">
<td><p>Maintain project timesheet delegates</p></td>
<td><p>ProjProjectTimesheetDelegatesMaintain</p></td>
<td><p>Maintain project timesheet delegate information for all users</p></td>
</tr>
<tr class="even">
<td><p>Review project transactions</p></td>
<td><p>ProjProjectTransactionsReview</p></td>
<td><p>Review project transactions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into project transaction status</p></td>
<td><p>ProjProjectTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of project transactions</p></td>
</tr>
<tr class="even">
<td><p>Maintain sites service solution for project management and accounting module</p></td>
<td><p>ProjSitesSolutionMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into license plate master data</p></td>
<td><p>WHSLicensePlateStatusInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain kanban wave transactions</p></td>
<td><p>WHSWarehousePlanningKanbanMaintain</p></td>
<td><p>Maintain kanban wave transactions</p></td>
</tr>
<tr class="odd">
<td><p>Maintain production waves</p></td>
<td><p>WHSWarehousePlanningProdMaintain</p></td>
<td><p>Maintain production waves</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

