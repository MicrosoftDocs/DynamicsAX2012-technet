---
title: Budget clerk security role (BudgetBudgetClerk)
TOCTitle: Budget clerk security role (BudgetBudgetClerk)
ms:assetid: 440f10d6-e123-4305-aa16-c2c4b54e52fa
ms:mtpsurl: https://technet.microsoft.com/library/Hh527083(v=AX.60)
ms:contentKeyID: 37823135
author: tonyafehr
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Budget clerk security role (BudgetBudgetClerk) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Budget clerk security role represents a user who documents budget events and responds to budget inquiries.

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
<td><p>Approve budget plans</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>BudgetPlanApprove</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Approve budget register entries</p></td>
<td><p>BudgetBudgetTransactionsApprove</p></td>
<td><p>Approve ledger budget business events</p></td>
</tr>
<tr class="odd">
<td><p>Enable financial reports generator</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>RRGEnable</p></td>
<td><p>Set up templates, report format, and other information to enable the financial reports generator</p></td>
</tr>
<tr class="even">
<td><p>Inquire about accounting data</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>LedgerRRGGInquire</p></td>
<td><p>Respond to inquiries about accounting data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into budget check errors or warnings</p></td>
<td><p>BudgetBudgetCheckResultsInquire</p></td>
<td><p>Respond to inquiries about budget check results</p></td>
</tr>
<tr class="even">
<td><p>Inquire into budget control process policies</p></td>
<td><p>BudgetBudgetCtrlProcPoliciesInquire</p></td>
<td><p>Respond to inquiries about policies governing the budget control process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into budget control process reference data</p></td>
<td><p>BudgetBudgetCtrlProcRefDataInquire</p></td>
<td><p>Respond to inquiries about budget control process reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into budget master</p></td>
<td><p>BudgetBudgetsInquire</p></td>
<td><p>Respond to inquiries about budget master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into budget process policies</p></td>
<td><p>BudgetBudgetProcessPoliciesInquire</p></td>
<td><p>Respond to inquiries about budget policy data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into budget register entry status</p></td>
<td><p>BudgetBudgetTransStatusInquire</p></td>
<td><p>Respond to inquiries about the status of budget register entries</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into chart of account master</p></td>
<td><p>LedgerChartOfAccountsInquire</p></td>
<td><p>Respond to inquiries about chart of accounts</p></td>
</tr>
<tr class="even">
<td><p>Inquire into organizational model</p></td>
<td><p>OMOrganizationsInquire</p></td>
<td><p>Respond to inquiries about organization and organization hierarchy master data</p></td>
</tr>
<tr class="odd">
<td><p>Maintain budget plans</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>BudgetPlanMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Maintain budget register entries</p></td>
<td><p>BudgetBudgetTransactionsMaintain</p></td>
<td><p>Document and record ledger budget business events</p></td>
</tr>
<tr class="odd">
<td><p>Maintain fixed asset budgets</p></td>
<td><p>AssetFixedAssetBudgetsMaintain</p></td>
<td><p>Maintain fixed asset budgets</p></td>
</tr>
<tr class="even">
<td><p>Maintain fixed assets budget transactions</p></td>
<td><p>AssetBudgetMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Maintain forecast position master</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>HcmForecastMaintain</p></td>
<td><p>Maintain forecast positions</p></td>
</tr>
<tr class="even">
<td><p>Select forecast positions</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>BudgetPlanningSelectPositionMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>View budget planning configuration and processes</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>BudgetPlanningConfigProcessView</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

  


