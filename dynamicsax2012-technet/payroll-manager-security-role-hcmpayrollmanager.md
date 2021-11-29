---
title: Payroll manager security role (HcmPayrollManager)
TOCTitle: Payroll manager security role (HcmPayrollManager)
ms:assetid: afb4a500-e9a1-4590-9c38-86987752a3c5
ms:mtpsurl: https://technet.microsoft.com/library/Hh527121(v=AX.60)
ms:contentKeyID: 37823172
author: Khairunj
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Payroll manager security role (HcmPayrollManager) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Payroll manager security role represents a user who authorizes activity in the payroll process.

## Duties in Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack

By default, this security role is assigned the following duties in Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack.

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
<td><p>Approve time and attendance payroll</p></td>
<td><p>JmgTimeAttendancePayrollApprove</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Enable time and attendance payroll process</p></td>
<td><p>JmgTimeAttendancePayrollProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the time and attendance payroll process</p></td>
</tr>
<tr class="odd">
<td><p>Enable time and attendance process</p></td>
<td><p>JmgTimeAttendanceProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the time and attendance process</p></td>
</tr>
<tr class="even">
<td><p>Inquire into limited worker information</p></td>
<td><p>HcmLimitedWorkerInquire</p></td>
<td><p>Respond to inquiries about limited worker information</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into organizational process</p></td>
<td><p>HcmOrganizationalProcessInquire</p></td>
<td><p>Respond to inquiries about organizational reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into payroll process</p></td>
<td><p>HcmPayrollProcessInquire</p></td>
<td><p>Respond to inquiries about payroll data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into time and attendance payroll data</p></td>
<td><p>JmgTimeAttendancePayrollProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into worker bank account master</p></td>
<td><p>HcmBankAccountsInquire</p></td>
<td><p>Respond to inquiries about worker bank account master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into worker personal identifications</p></td>
<td><p>HcmPersonIdentificationInquire</p></td>
<td><p>Respond to inquiries about worker personal identification</p></td>
</tr>
<tr class="even">
<td><p>Inquire into workers</p></td>
<td><p>HcmWorkerInquire</p></td>
<td><p>Respond to inquiries about employee and contractor data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into workforce management process</p></td>
<td><p>HcmWorkforceProcessInquire</p></td>
<td><p>Respond to inquiries about workforce reference data</p></td>
</tr>
<tr class="even">
<td><p>Maintain pay agreement master</p></td>
<td><p>JmgPayAgreementMasterMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Review payroll process performance</p></td>
<td><p>JmgPayrollProcessPerformanceReview</p></td>
<td><p>Monitor, analyze, and improve the payroll process performance</p></td>
</tr>
</tbody>
</table>


## Duties in Microsoft Dynamics AX 2012 R2

By default, this security role is assigned the following duties in Microsoft Dynamics AX 2012 R2.

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
<td><p>Approve position actions</p></td>
<td><p>HcmPositionActionApprove</p></td>
<td><p>Approve personnel actions that have a Position-create type or Position-modify type</p></td>
</tr>
<tr class="even">
<td><p>Approve time and attendance payroll</p></td>
<td><p>JmgTimeAttendancePayrollApprove</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Generate Form W-2 reports</p></td>
<td><p>PayrollGenerateW2Reports</p></td>
<td><p>Generate Form W-2 reports</p></td>
</tr>
<tr class="even">
<td><p>Inquire into calendar master</p></td>
<td><p>WorkCalendarMasterInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into calendar policies</p></td>
<td><p>WorkCalendarPoliciesInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into earning entry</p></td>
<td><p>PayrollEarningStatementGenerationInquire</p></td>
<td><p>Inquire into worker payroll earnings transactions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into jobs and positions</p></td>
<td><p>HcmJobPositionInquire</p></td>
<td><p>Respond to inquiries about job and position data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into limited worker information</p></td>
<td><p>HcmLimitedWorkerInquire</p></td>
<td><p>Respond to inquiries about limited worker information</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into payroll master data</p></td>
<td><p>PayrollMasterDataInquire</p></td>
<td><p>Inquire into the core data for the payroll system</p></td>
</tr>
<tr class="even">
<td><p>Inquire into payroll payment journals</p></td>
<td><p>PayrollIssueWorkerPaymentsInquire</p></td>
<td><p>Inquire into payroll payment journal details</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into payroll payments</p></td>
<td><p>PayrollPayStatementGenerationInquire</p></td>
<td><p>Inquire into payroll payments</p></td>
</tr>
<tr class="even">
<td><p>Inquire into payroll position and worker setup</p></td>
<td><p>PayrollPositionWorkerSetupInquire</p></td>
<td><p>Inquire into position and worker setup for payroll</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into payroll process</p></td>
<td><p>HcmPayrollProcessInquire</p></td>
<td><p>Respond to inquiries about payroll data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into payroll worker tax setup</p></td>
<td><p>PayrollWorkerTaxSetupInquire</p></td>
<td><p>Inquire into the worker tax information for payroll</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into position actions</p></td>
<td><p>HcmPositionActionProcessInquire</p></td>
<td><p>Respond to inquiries about position actions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into time and attendance payroll data</p></td>
<td><p>JmgTimeAttendancePayrollProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into worker bank account master</p></td>
<td><p>HcmBankAccountsInquire</p></td>
<td><p>Respond to inquiries about worker bank account master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into worker personal identifications</p></td>
<td><p>HcmPersonIdentificationInquire</p></td>
<td><p>Respond to inquiries about worker personal identification</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into workers</p></td>
<td><p>HcmWorkerInquire</p></td>
<td><p>Respond to inquiries about employee and contractor data</p></td>
</tr>
<tr class="even">
<td><p>Review payroll process performance</p></td>
<td><p>JmgPayrollProcessPerformanceReview</p></td>
<td><p>Monitor, analyze, and improve the payroll process performance</p></td>
</tr>
</tbody>
</table>


## Duties in Microsoft Dynamics AX 2012 R3

By default, this security role is assigned the following duties in Microsoft Dynamics AX 2012 R3.

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
<td><p>Inquire into worker bank account master</p></td>
<td><p>HcmBankAccountsInquire</p></td>
<td><p>Respond to inquiries about worker bank account master data</p></td>
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
<td><p>Inquire into payroll process</p></td>
<td><p>HcmPayrollProcessInquire</p></td>
<td><p>Respond to inquiries about payroll data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into worker personal identifications</p></td>
<td><p>HcmPersonIdentificationInquire</p></td>
<td><p>Respond to inquiries about worker personal identification</p></td>
</tr>
<tr class="even">
<td><p>Approve position actions</p></td>
<td><p>HcmPositionActionApprove</p></td>
<td><p>Approve personnel actions that have a Position-create type or Position-modify type</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into position actions</p></td>
<td><p>HcmPositionActionProcessInquire</p></td>
<td><p>Respond to inquiries about position actions</p></td>
</tr>
<tr class="even">
<td><p>Approve worker actions</p></td>
<td><p>HcmWorkerActionApprove</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into worker actions</p></td>
<td><p>HcmWorkerActionProcessInquire</p></td>
<td><p>Respond to inquiries about worker actions</p></td>
</tr>
<tr class="even">
<td><p>Maintain worker actions</p></td>
<td><p>HcmWorkerActionProcessMaintain</p></td>
<td><p>Create, edit, and delete worker actions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into workers</p></td>
<td><p>HcmWorkerInquire</p></td>
<td><p>Respond to inquiries about employee and contractor data</p></td>
</tr>
<tr class="even">
<td><p>Review payroll process performance</p></td>
<td><p>JmgPayrollProcessPerformanceReview</p></td>
<td><p>Monitor, analyze, and improve the payroll process performance</p></td>
</tr>
<tr class="odd">
<td><p>Approve time and attendance payroll</p></td>
<td><p>JmgTimeAttendancePayrollApprove</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into time and attendance payroll data</p></td>
<td><p>JmgTimeAttendancePayrollProgressInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into data that is available in the payroll cube</p></td>
<td><p>PayrollCubeInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into earning entry</p></td>
<td><p>PayrollEarningStatementGenerationInquire</p></td>
<td><p>Inquire into worker payroll earnings transactions</p></td>
</tr>
<tr class="odd">
<td><p>Generate payroll tax reports</p></td>
<td><p>PayrollGenerateTaxReport</p></td>
<td><p>Generate reports to use when preparing payroll taxes</p></td>
</tr>
<tr class="even">
<td><p>Generate Form W-2 reports</p></td>
<td><p>PayrollGenerateW2Reports</p></td>
<td><p>Generate Form W-2 reports</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into payroll payment journals</p></td>
<td><p>PayrollIssueWorkerPaymentsInquire</p></td>
<td><p>Inquire into payroll payment journal details</p></td>
</tr>
<tr class="even">
<td><p>Inquire into payroll master data</p></td>
<td><p>PayrollMasterDataInquire</p></td>
<td><p>Inquire into the core data for the payroll system</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into payroll payments</p></td>
<td><p>PayrollPayStatementGenerationInquire</p></td>
<td><p>Inquire into payroll payments</p></td>
</tr>
<tr class="even">
<td><p>Inquire into payroll position and worker setup</p></td>
<td><p>PayrollPositionWorkerSetupInquire</p></td>
<td><p>Inquire into position and worker setup for payroll</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into payroll positive payments</p></td>
<td><p>PayrollPositivePayInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into payroll worker tax setup</p></td>
<td><p>PayrollWorkerTaxSetupInquire</p></td>
<td><p>Inquire into the worker tax information for payroll</p></td>
</tr>
<tr class="odd">
<td><p>Create earnings statement</p></td>
<td><p>RPayEarningMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into calendar master</p></td>
<td><p>WorkCalendarMasterInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into calendar policies</p></td>
<td><p>WorkCalendarPoliciesInquire</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

  


