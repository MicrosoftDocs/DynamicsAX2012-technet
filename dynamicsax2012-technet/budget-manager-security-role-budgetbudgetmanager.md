---
title: Budget manager security role (BudgetBudgetManager)
TOCTitle: Budget manager security role (BudgetBudgetManager)
ms:assetid: 60833b73-f679-4777-b40f-e87de6f85c2c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh527096(v=AX.60)
ms:contentKeyID: 37823148
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Budget manager security role (BudgetBudgetManager) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Budget manager security role represents a user who reviews budget process performance and enables the budget process.

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
<td><p>Approve fixed assets budget entries</p></td>
<td><p>AssetBudgetApprove</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain fixed assets budget transactions</p></td>
<td><p>AssetBudgetMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain fixed asset budgets</p></td>
<td><p>AssetFixedAssetBudgetsMaintain</p></td>
<td><p>Maintain fixed asset budgets</p></td>
</tr>
<tr class="even">
<td><p>Inquire into fixed assets</p></td>
<td><p>AssetFixedAssetsInquire</p></td>
<td><p>Respond to inquiries about fixed assets master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into fixed asset transaction status</p></td>
<td><p>AssetFixedAssetTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of fixed asset transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into budget check errors or warnings</p></td>
<td><p>BudgetBudgetCheckResultsInquire</p></td>
<td><p>Respond to inquiries about budget check results</p></td>
</tr>
<tr class="odd">
<td><p>Enable budget control process</p></td>
<td><p>BudgetBudgetControlProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the budget control process</p></td>
</tr>
<tr class="even">
<td><p>Review budget control process performance</p></td>
<td><p>BudgetBudgetControlProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the budget control process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into budget control process policies</p></td>
<td><p>BudgetBudgetCtrlProcPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the budget control process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into budget control process reference data</p></td>
<td><p>BudgetBudgetCtrlProcRefDataInquire</p></td>
<td><p>Respond to inquiries about budget control process reference data</p></td>
</tr>
<tr class="odd">
<td><p>Enable budget process</p></td>
<td><p>BudgetBudgetProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the budget process</p></td>
</tr>
<tr class="even">
<td><p>Review budget process performance</p></td>
<td><p>BudgetBudgetProcessPerfReview</p></td>
<td><p>Monitor, analyze, and improve the budget process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into budget process policies</p></td>
<td><p>BudgetBudgetProcessPoliciesInquire</p></td>
<td><p>Respond to inquiries about budget policy data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into budget master</p></td>
<td><p>BudgetBudgetsInquire</p></td>
<td><p>Respond to inquiries about budget master data</p></td>
</tr>
<tr class="odd">
<td><p>Maintain budget master</p></td>
<td><p>BudgetBudgetsMaintain</p></td>
<td><p>Maintain budget master</p></td>
</tr>
<tr class="even">
<td><p>Approve budget register entries</p></td>
<td><p>BudgetBudgetTransactionsApprove</p></td>
<td><p>Approve ledger budget business events</p></td>
</tr>
<tr class="odd">
<td><p>Maintain budget register entries</p></td>
<td><p>BudgetBudgetTransactionsMaintain</p></td>
<td><p>Document and record ledger budget business events</p></td>
</tr>
<tr class="even">
<td><p>Inquire into budget register entry status</p></td>
<td><p>BudgetBudgetTransStatusInquire</p></td>
<td><p>Respond to inquiries about the status of budget register entries</p></td>
</tr>
<tr class="odd">
<td><p>View positions using a list page</p></td>
<td><p>BudgetOpenPositionsInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Approve budget plans</p></td>
<td><p>BudgetPlanApprove</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain budget planning Generate</p></td>
<td><p>BudgetPlanGenerateBudgetPlanMaintain</p></td>
<td><p>Maintain budget planning Generate</p></td>
</tr>
<tr class="even">
<td><p>Generate budget register entry</p></td>
<td><p>BudgetPlanGenerateBudgetTrnsMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain budget plans</p></td>
<td><p>BudgetPlanMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain budget planning configuration and processes</p></td>
<td><p>BudgetPlanningConfigProcessMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Select forecast positions</p></td>
<td><p>BudgetPlanningSelectPositionMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into customer reference data</p></td>
<td><p>CustCustomerReferenceDataInquire</p></td>
<td><p>Respond to inquiries about customer master reference data</p></td>
</tr>
<tr class="odd">
<td><p>Maintain the Director authorization status</p></td>
<td><p>CustDirectiveDirectorMaintain_PSN</p></td>
<td><p>Maintain the Director authorization status and assign numbers for titres and bordereaux de titres</p></td>
</tr>
<tr class="even">
<td><p>View titre</p></td>
<td><p>CustDirectiveInquire_PSN</p></td>
<td><p>View titre tabs, titre reports, and the titre maintenance form</p></td>
</tr>
<tr class="odd">
<td><p>Maintain dimension configuration for integrating applications</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>DimIntegrationConfigurationMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>A parameter that is used to group and sub-total the report</p></td>
<td><p>ForecastPositionsByBudgetPlanGenerate</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into forecast positions</p></td>
<td><p>HcmForecastInquire</p></td>
<td><p>Respond to inquiries about forecast position data</p></td>
</tr>
<tr class="even">
<td><p>Maintain forecast position master</p></td>
<td><p>HcmForecastMaintain</p></td>
<td><p>Maintain forecast positions</p></td>
</tr>
<tr class="odd">
<td><p>Set up position budgeting</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>HcmForecastPositionBudgetMaintain</p></td>
<td><p>Add, edit, and delete all setup information that is used for position budgeting</p></td>
</tr>
<tr class="even">
<td><p>Inquire into chart of account master</p></td>
<td><p>LedgerChartOfAccountsInquire</p></td>
<td><p>Respond to inquiries about chart of accounts</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into journals and transaction status</p></td>
<td><p>LedgerJournalsTransactionStatusInquire</p></td>
<td><p>Respond to inquiries about the status of journals and transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire about accounting data</p></td>
<td><p>LedgerRRGGInquire</p></td>
<td><p>Respond to inquiries about accounting data</p></td>
</tr>
<tr class="odd">
<td><p>Maintain and configure organizational model</p></td>
<td><p>OMOrganizationsMaintain</p></td>
<td><p>Create or update organizations and organization hierarchies</p></td>
</tr>
<tr class="even">
<td><p>Close commitments</p></td>
<td><p>PurchCommitmentCloseMaintain_PSN</p></td>
<td><p>Maintain the commitment closing form and process the batch closing of commitments</p></td>
</tr>
<tr class="odd">
<td><p>Maintain commitment documents</p></td>
<td><p>PurchCommitmentMaintainCommitment_PSN</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Approve purchase requisitions</p></td>
<td><p>PurchReqPurchaseRequisitionApprove</p></td>
<td><p>Approve and authorize purchase requisitions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into purchase requisition</p></td>
<td><p>PurchReqPurchaseRequisitionInquire</p></td>
<td><p>Respond to inquiries about the status of purchase requisitions</p></td>
</tr>
<tr class="even">
<td><p>Enable financial reports generator</p></td>
<td><p>RRGEnable</p></td>
<td><p>Set up templates, report format, and other information to enable the financial reports generator</p></td>
</tr>
<tr class="odd">
<td><p>Maintain the Director authorization status and mandat numbers</p></td>
<td><p>VendDirectiveDirectorMaintain_PSN</p></td>
<td><p>Maintain the Director authorization status and assign numbers for mandats and bordereaux de mandat</p></td>
</tr>
<tr class="even">
<td><p>Inquire into mandats</p></td>
<td><p>VendDirectiveInquire_PSN</p></td>
<td><p>View mandat tabs, mandat reports, and the mandat maintenance form</p></td>
</tr>
</tbody>
</table>


## Privileges

By default, this security role is assigned the following privilege in Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack.

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
<td><p>URL for the budget manager role center</p></td>
<td><p>BudgetManagerRoleCenterView</p></td>
</tr>
</tbody>
</table>


No privileges are directly assigned to this role in Microsoft Dynamics AX 2012 R2 or Microsoft Dynamics AX 2012 R3.

  


