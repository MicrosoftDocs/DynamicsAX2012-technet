---
title: Compensation and benefits manager security role (HcmCompensationAndBenefitsManager)
TOCTitle: Compensation and benefits manager security role (HcmCompensationAndBenefitsManager)
ms:assetid: c2c14c33-3cf9-4e8f-a782-0a795819c80a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh527134(v=AX.60)
ms:contentKeyID: 37823185
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Compensation and benefits manager security role (HcmCompensationAndBenefitsManager) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Compensation and benefits manager security role represents a user who documents compensation and benefits events, responds to compensation and benefit inquiries and records the financial consequences of compensation and benefit events.

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
<td><p>Review case process</p></td>
<td><p>CaseCaseProcessReview</p></td>
<td><p>Monitor, analyze, and improve the case process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into employee case progress</p></td>
<td><p>CaseEmployeeCaseProgressInquire</p></td>
<td><p>Respond to inquiries about the status of employee cases</p></td>
</tr>
<tr class="odd">
<td><p>Enable absence process</p></td>
<td><p>HcmAbsenceEnable</p></td>
<td><p>Set up policies and reference data to enable the absence process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into absence process</p></td>
<td><p>HcmAbsenceProcessInquire</p></td>
<td><p>Respond to inquiries about absence data</p></td>
</tr>
<tr class="odd">
<td><p>Review absence information</p></td>
<td><p>HcmAbsenceReview</p></td>
<td><p>Monitor, analyze, and improve the absence process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into absence transactions</p></td>
<td><p>HcmAbsenceTransactionInquire</p></td>
<td><p>Respond to inquiries about absence transactions</p></td>
</tr>
<tr class="odd">
<td><p>Maintain absence transactions</p></td>
<td><p>HcmAbsenceTransactionMaintain</p></td>
<td><p>Document and record absence registration and request transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into benefits process</p></td>
<td><p>HcmBenefitInquire</p></td>
<td><p>Respond to inquiries about benefits data</p></td>
</tr>
<tr class="odd">
<td><p>Enable human resources policy</p></td>
<td><p>HcmBenefitPolicyProcessEnable</p></td>
<td><p>Setup policies to enable human resource eligibility rules</p></td>
</tr>
<tr class="even">
<td><p>Enable benefits process</p></td>
<td><p>HcmBenefitProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the benefits process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into compensation process</p></td>
<td><p>HcmCompensationInquire</p></td>
<td><p>Respond to inquiries about compensation data</p></td>
</tr>
<tr class="even">
<td><p>Enable compensation process</p></td>
<td><p>HcmCompensationProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the compensation process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into compensation transactions</p></td>
<td><p>HcmCompensationTransactionInquire</p></td>
<td><p>Respond to inquiries about compensation transactions</p></td>
</tr>
<tr class="even">
<td><p>Maintain compensation transactions</p></td>
<td><p>HcmCompensationTransactionMaintain</p></td>
<td><p>Document and record compensation transactions</p></td>
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
<td><p>Inquire into jobs and positions</p></td>
<td><p>HcmJobPositionInquire</p></td>
<td><p>Respond to inquiries about job and position data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into limited worker information</p></td>
<td><p>HcmLimitedWorkerInquire</p></td>
<td><p>Respond to inquiries about limited worker information</p></td>
</tr>
<tr class="even">
<td><p>Inquire into organizational process</p></td>
<td><p>HcmOrganizationalProcessInquire</p></td>
<td><p>Respond to inquiries about organizational reference data</p></td>
</tr>
<tr class="odd">
<td><p>Approve worker actions</p>
<div class="alert"> 

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>HcmWorkerActionApprove</p></td>
<td><p>Approve worker actions of any worker action type</p></td>
</tr>
<tr class="even">
<td><p>Inquire into worker actions</p>
<div class="alert"> 

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>HcmWorkerActionProcessInquire</p></td>
<td><p>Respond to inquiries about worker actions</p></td>
</tr>
<tr class="odd">
<td><p>Maintain worker actions</p>
<div class="alert"> 

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>HcmWorkerActionProcessMaintain</p></td>
<td><p>Create, edit, and delete worker actions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into workforce management process</p></td>
<td><p>HcmWorkforceProcessInquire</p></td>
<td><p>Respond to inquiries about workforce reference data</p></td>
</tr>
<tr class="odd">
<td><p>Set up payroll master data</p></td>
<td><p>PayrollMasterDataMaintain</p></td>
<td><p>Set up the core data for the payroll system</p></td>
</tr>
<tr class="even">
<td><p>Set up payroll positions and workers</p></td>
<td><p>PayrollPositionWorkerSetupMaintain</p></td>
<td><p>Set up positions and workers for payroll</p></td>
</tr>
<tr class="odd">
<td><p>Average earnings</p>
<div class="alert"> 

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>RPayEarningInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Reconcile pay statements</p>
<div class="alert"> 

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>RPayPayStatementReconcile</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Submit legislative reports to regulatory authorities</p>
<div class="alert"> 

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>RPayReportsSubmit</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Set up time management master data</p>
<div class="alert"> 

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>RPaySetupTimeMasterData</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into payments to workers</p>
<div class="alert"> 

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>RPayWorkerInquire</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

