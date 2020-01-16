---
title: Project manager security role (ProjProjectManager)
TOCTitle: Project manager security role (ProjProjectManager)
ms:assetid: bc81d5f8-1a14-4798-89e7-7dbfb20254ca
ms:mtpsurl: https://technet.microsoft.com/library/Hh527132(v=AX.60)
ms:contentKeyID: 37823183
author: Khairunj
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Project manager security role (ProjProjectManager) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Project manager security role represents a user who documents project forecast budget events and responds to project forecast budget inquiries. This user maintains project accounting master information and responds to project accounting master information inquiries. This person also authorizes project accounting process events.

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
<td><p>Inquire into purchase agreement master</p></td>
<td><p>AgreementPurchaseAgreementMasterInquire</p></td>
<td><p>Respond to inquiries about purchase agreement master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into sales agreement master</p></td>
<td><p>AgreementSalesAgreementMasterInquire</p></td>
<td><p>Respond to inquiries about sales agreement master data</p></td>
</tr>
<tr class="odd">
<td><p>Enable case management</p></td>
<td><p>CaseCaseManagementEnable</p></td>
<td><p>Set up policies and reference data to enable the case management process</p></td>
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
<td><p>Inquire into project case progress</p></td>
<td><p>CaseProjectCaseProgressInquire</p></td>
<td><p>Respond to inquiries about the status of project cases</p></td>
</tr>
<tr class="odd">
<td><p>Maintain project cases</p></td>
<td><p>CaseProjectCasesMaintain</p></td>
<td><p>Maintain project cases</p></td>
</tr>
<tr class="even">
<td><p>Inquire into customer master</p></td>
<td><p>CustCustomerMasterInquire</p></td>
<td><p>Respond to inquiries about customer master data</p></td>
</tr>
<tr class="odd">
<td><p>Role center URL redirection</p></td>
<td><p>EPHomePageView</p></td>
<td><p>Enable redirection from generic role center URL</p></td>
</tr>
<tr class="even">
<td><p>Inquire into inventory status</p></td>
<td><p>InventStatusInquire</p></td>
<td><p>Respond to inquiries about the status of the inventory</p></td>
</tr>
<tr class="odd">
<td><p>Maintain invoice cancellation proposals</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>MaintainInvoiceCancellationProposals_BR</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain project document print management settings</p></td>
<td><p>PrintMgmtProjectDocumentSettingsMaintain</p></td>
<td><p>Maintain project document print management settings.</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into production orders</p></td>
<td><p>ProdProductionOrderProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain project activity master</p></td>
<td><p>ProjActivityMasterMaintain</p></td>
<td><p>Maintain project activity hierarchy</p></td>
</tr>
<tr class="odd">
<td><p>Maintain project activity cost tracking master</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ProjActivityMasterMaintainCostTracking</p></td>
<td><p>Maintain cost tracking view of activity hierarchy</p></td>
</tr>
<tr class="even">
<td><p>Maintain project activity effort tracking master</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ProjActivityMasterMaintainEffortTracking</p></td>
<td><p>Maintain the effort tracking view of activity hierarchy</p></td>
</tr>
<tr class="odd">
<td><p>Service operations for Project Contract service</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ProjContractServiceOperations</p></td>
<td><p>Service operations for Project Contract service</p></td>
</tr>
<tr class="even">
<td><p>Service operations for Project service</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ProjectServiceOperations</p></td>
<td><p>Service operations for Project service</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into estimate project master</p></td>
<td><p>ProjEstimateProjectMasterInquire</p></td>
<td><p>Respond to inquiries about estimate project master data</p></td>
</tr>
<tr class="even">
<td><p>Maintain estimate project master</p></td>
<td><p>ProjEstimateProjectMasterMaintain</p></td>
<td><p>Maintain estimate projects master information</p></td>
</tr>
<tr class="odd">
<td><p>Approve fixed-price revenue recognition</p></td>
<td><p>ProjFixedPriceRevenueRecognitionApprove</p></td>
<td><p>Approve fixed price revenue recognition</p></td>
</tr>
<tr class="even">
<td><p>Inquire into fixed price projects revenue recognition</p></td>
<td><p>ProjFixedPriceRevenueRecognitionInquire</p></td>
<td><p>Respond to inquiries about fixed-price revenue recognition master information</p></td>
</tr>
<tr class="odd">
<td><p>Maintain fixed price projects revenue recognition</p></td>
<td><p>ProjFixedPriceRevenueRecognitionMaintai</p></td>
<td><p>Document and record fixed-price revenue recognition</p></td>
</tr>
<tr class="even">
<td><p>Inquire into grant master</p></td>
<td><p>ProjGrantMasterInquireInquire</p></td>
<td><p>Respond to inquiries about grant master information</p></td>
</tr>
<tr class="odd">
<td><p>Maintain grant master</p></td>
<td><p>ProjGrantMasterMaintain</p></td>
<td><p>Maintain grants master information</p></td>
</tr>
<tr class="even">
<td><p>Maintain project invoice proposal</p></td>
<td><p>ProjInvoiceProposalMaintain</p></td>
<td><p>Inovice Proposal</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into missing timesheets</p></td>
<td><p>ProjMissingTimesheetsInquire</p></td>
<td><p>Respond into inquiries about missing timesheets</p></td>
</tr>
<tr class="even">
<td><p>Inquire into project budgets</p></td>
<td><p>ProjProjectBudgetInquire</p></td>
<td><p>Respond to inquiries about project budget master information</p></td>
</tr>
<tr class="odd">
<td><p>Maintain project budgets</p></td>
<td><p>ProjProjectBudgetsMaintain</p></td>
<td><p>Maintain master information about project budgets</p></td>
</tr>
<tr class="even">
<td><p>Inquire into project category master</p></td>
<td><p>ProjProjectCategoriesMasterInquire</p></td>
<td><p>Respond to inquiries about project category master information</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into project contract master</p></td>
<td><p>ProjProjectContractMasterInquire</p></td>
<td><p>Respond to inquiries about project contract master information</p></td>
</tr>
<tr class="even">
<td><p>Maintain project contract master</p></td>
<td><p>ProjProjectContractMasterMaintain</p></td>
<td><p>Maintain project contracts master information</p></td>
</tr>
<tr class="odd">
<td><p>Review project control - cash flow</p></td>
<td><p>ProjProjectControlCashFlowReview</p></td>
<td><p>Monitor forecasted and actual project cash flow</p></td>
</tr>
<tr class="even">
<td><p>Review project control - hour utilization</p></td>
<td><p>ProjProjectControlHourUtilizationReview</p></td>
<td><p>Monitor the utilization and efficiency of assigned project hours</p></td>
</tr>
<tr class="odd">
<td><p>Review project control - invoice control</p></td>
<td><p>ProjProjectControlInvoiceControlReview</p></td>
<td><p>Monitor posted project transactions</p></td>
</tr>
<tr class="even">
<td><p>Review project control</p></td>
<td><p>ProjProjectControlReview</p></td>
<td><p>Monitor project hour utilization and efficiency</p></td>
</tr>
<tr class="odd">
<td><p>Review project control - statement</p></td>
<td><p>ProjProjectControlStatementReview</p></td>
<td><p>Monitor project control statement reports</p></td>
</tr>
<tr class="even">
<td><p>Maintain project forecasts</p></td>
<td><p>ProjProjectForecastMaintain</p></td>
<td><p>Maintain master information about project forecasts</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into project invoices</p></td>
<td><p>ProjProjectInvoiceInquire</p></td>
<td><p>Respond to inquiries about project invoice master information</p></td>
</tr>
<tr class="even">
<td><p>This duty only include privileges that are accessible by the project manager and it does not contain the privileges related to sales order and purchase order</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ProjProjectItemTasksMaintain</p></td>
<td><p>Maintain the item tasks for the project.</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into project master</p></td>
<td><p>ProjProjectMasterInquire</p></td>
<td><p>Respond to inquiries about project master information</p></td>
</tr>
<tr class="even">
<td><p>Maintain project master</p></td>
<td><p>ProjProjectMasterMaintain</p></td>
<td><p>Maintain project master</p></td>
</tr>
<tr class="odd">
<td><p>Maintain project quotation</p></td>
<td><p>ProjProjectQuotationMaintain</p></td>
<td><p>Document and record project quotation</p></td>
</tr>
<tr class="even">
<td><p>Maintain project sales packing slips</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ProjProjectSalesPackingSlipMaintain</p></td>
<td><p>Document and record project sales packing slip</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into project schedule master</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ProjProjectScheduleMasterInquire</p></td>
<td><p>Respond to inquiries about project schedule master information</p></td>
</tr>
<tr class="even">
<td><p>Inquire into project schedule master</p></td>
<td><p>ProjProjectScheduleMasterInquire</p></td>
<td><p>Respond to inquiries about project schedule master information</p></td>
</tr>
<tr class="odd">
<td><p>Maintain project schedule master</p></td>
<td><p>ProjProjectScheduleMasterMaintain</p></td>
<td><p>Maintain project schedule master information</p></td>
</tr>
<tr class="even">
<td><p>Service Operations for project</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ProjProjectServiceOperations</p></td>
<td><p>Utilize service operations for expense management</p></td>
</tr>
<tr class="odd">
<td><p>Approve project timesheets</p></td>
<td><p>ProjProjectTimesheetsApprove</p></td>
<td><p>Approve project timesheets</p></td>
</tr>
<tr class="even">
<td><p>Maintain project timesheets</p></td>
<td><p>ProjProjectTimesheetsMaintain</p></td>
<td><p>Create and maintain project timesheets</p></td>
</tr>
<tr class="odd">
<td><p>Approve project transactions</p></td>
<td><p>ProjProjectTransactionApprove</p></td>
<td><p>Approve project transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into project transaction status</p></td>
<td><p>ProjProjectTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of project transactions</p></td>
</tr>
<tr class="odd">
<td><p>Service operations for Project WBS service</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>ProjWBSServiceOperations</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain customer retention</p></td>
<td><p>PSACustomerRetentionForManager</p></td>
<td><p>Maintain customer retention</p></td>
</tr>
<tr class="odd">
<td><p>Vendor invoices</p></td>
<td><p>PSAPwpInvoiceInquiry</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain vendor retention</p></td>
<td><p>PSAVendRetentionProjManager</p></td>
<td><p>Maintain vendor retention</p></td>
</tr>
<tr class="odd">
<td><p>Approve purchase order</p></td>
<td><p>PurchOrderApprove</p></td>
<td><p>Approve and authorize purchase order document</p></td>
</tr>
<tr class="even">
<td><p>Inquire into purchase order to invoice progress</p></td>
<td><p>PurchOrderToInvoiceProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the purchase order to invoice process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into purchase requisition consolidation</p></td>
<td><p>PurchReqConsolidationReview</p></td>
<td><p>Monitor, analyze and improve the purchase requisition consolidation process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into purchase requisition</p></td>
<td><p>PurchReqPurchaseRequisitionInquire</p></td>
<td><p>Respond to inquiries about the status of purchase requisitions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into request for quotation status</p></td>
<td><p>PurchRFQRequestForQuoteInquire</p></td>
<td><p>Respond to inquiries about the status of request for quotations</p></td>
</tr>
<tr class="even">
<td><p>Inquire into sales order progress</p></td>
<td><p>SalesOrderProgressInquire</p></td>
<td><p>Respond to inquiries about the status of the sales order process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into activities</p></td>
<td><p>smmActivityInquire</p></td>
<td><p>Respond to inquiries about activity data</p></td>
</tr>
<tr class="even">
<td><p>Maintain calendar master</p></td>
<td><p>WorkCalendarMasterMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Enable calendar management process</p></td>
<td><p>WorkCalendarsEnable</p></td>
<td><p>Set up policies and reference data to enable the use of calendars</p></td>
</tr>
<tr class="even">
<td><p>Inquire into resource capacity</p></td>
<td><p>WrkCtrResourceCapacityStatusInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Enable resource management process</p></td>
<td><p>WrkCtrResourceManagementProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the resource management process</p></td>
</tr>
<tr class="even">
<td><p>Maintain resource master</p></td>
<td><p>WrkCtrResourcesMasterMaintain</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## Privileges

In Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack, no privileges are directly assigned to this role. In Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3, this security role is assigned the following privileges by default.

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
<td><p>Maintain project report configurations</p></td>
<td><p>ProjFormletterParametersMaintain</p></td>
</tr>
<tr class="even">
<td><p>Minimum payment amount in cash</p></td>
<td><p>TaxFormulaDesignerInquire_IN</p></td>
</tr>
</tbody>
</table>

  


