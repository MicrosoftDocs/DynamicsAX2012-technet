---
title: Recruiter security role (HcmRecruiter)
TOCTitle: Recruiter security role (HcmRecruiter)
ms:assetid: d09d6e24-aad7-4677-b6f0-1a310dd04707
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh527137(v=AX.60)
ms:contentKeyID: 37823188
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Recruiter security role (HcmRecruiter) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Recruiter security role represents a user who documents recruiting events, responds to recruiting inquiries, and records the financial consequences of recruiting events.

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
<td><p>Configure AIF synchronization</p></td>
<td><p>AifSyncConfigure</p></td>
<td><p>Allows specifying filters on ports</p></td>
</tr>
<tr class="even">
<td><p>Inquire into applicant master</p></td>
<td><p>HcmApplicantInquire</p></td>
<td><p>Respond to inquiries about applicant master data</p></td>
</tr>
<tr class="odd">
<td><p>Maintain applicant master</p></td>
<td><p>HcmApplicantMaintain</p></td>
<td><p>Maintain applicants</p></td>
</tr>
<tr class="even">
<td><p>Maintain job and position master</p></td>
<td><p>HcmJobPositionMaintain</p></td>
<td><p>Maintain jobs and positions</p></td>
</tr>
<tr class="odd">
<td><p>Maintain document service operation</p></td>
<td><p>HcmJobServicesMaintain</p></td>
<td><p>Read/create job applications and also inquire about job postings</p></td>
</tr>
<tr class="even">
<td><p>Inquire into organizational process</p></td>
<td><p>HcmOrganizationalProcessInquire</p></td>
<td><p>Respond to inquiries about organizational reference data</p></td>
</tr>
<tr class="odd">
<td><p>Change multiple position values simultaneously</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>HcmPositionMassUpdate</p></td>
<td><p>Update multiple position values at the same time. For example, position details, duration, relationships, financial dimensions, labor unions, and payroll position information.</p></td>
</tr>
<tr class="even">
<td><p>Enable recruitment process</p></td>
<td><p>HcmRecruitmentProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the recruitment process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into recruitment process</p></td>
<td><p>HcmRecruitmentProcessInquire</p></td>
<td><p>Respond to inquiries about recruitment reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into Sites Services for Human Resources</p></td>
<td><p>HcmSitesSolutionInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into skills data</p></td>
<td><p>HcmSkillInquire</p></td>
<td><p>Respond to inquiries about skills data</p></td>
</tr>
<tr class="even">
<td><p>Maintain skills</p></td>
<td><p>HcmSkillMaintain</p></td>
<td><p>Document and record skills</p></td>
</tr>
<tr class="odd">
<td><p>Enable skills management process</p></td>
<td><p>HcmSkillsProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the skills management process</p></td>
</tr>
<tr class="even">
<td><p>Approve worker actions</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>HcmWorkerActionApprove</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into worker actions</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>HcmWorkerActionProcessInquire</p></td>
<td><p>Respond to inquiries about worker actions</p></td>
</tr>
<tr class="even">
<td><p>Maintain worker actions</p>
<div class="alert">

> [!NOTE]
> <P>This duty is assigned to the role only in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
<td><p>HcmWorkerActionProcessMaintain</p></td>
<td><p>Create, edit, and delete worker actions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into workers</p></td>
<td><p>HcmWorkerInquire</p></td>
<td><p>Respond to inquiries about employee and contractor data</p></td>
</tr>
<tr class="even">
<td><p>Maintain worker master</p></td>
<td><p>HcmWorkerMaintain</p></td>
<td><p>Maintain workers</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into workforce management process</p></td>
<td><p>HcmWorkforceProcessInquire</p></td>
<td><p>Respond to inquiries about workforce reference data</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

