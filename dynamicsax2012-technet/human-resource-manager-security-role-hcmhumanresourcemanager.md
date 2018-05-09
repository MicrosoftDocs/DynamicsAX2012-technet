---
title: Human resource manager security role (HcmHumanResourceManager)
TOCTitle: Human resource manager security role (HcmHumanResourceManager)
ms:assetid: e1c54180-f97e-439d-9178-488da2793e7a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh527144(v=AX.60)
ms:contentKeyID: 37823195
ms.date: 05/06/2014
mtps_version: v=AX.60
---

# Human resource manager security role (HcmHumanResourceManager) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Human resource manager security role represents a user who periodically reviews human resource process performance and enables the human resource process.

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
<td><p>Approve worker user requests</p></td>
<td><p>HcmWorkerUserRequestApprove</p></td>
<td><p>View and approve worker user requests</p></td>
</tr>
<tr class="even">
<td><p>Enable human resource process</p></td>
<td><p>HcmHREnable</p></td>
<td><p>Set up policies and reference data to enable the human resources process</p></td>
</tr>
<tr class="odd">
<td><p>Enable performance process</p></td>
<td><p>HcmPerformanceProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the performance process for workers</p></td>
</tr>
<tr class="even">
<td><p>Enable the global address book process</p></td>
<td><p>DirAddressBookProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the global address book process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into absence process</p></td>
<td><p>HcmAbsenceProcessInquire</p></td>
<td><p>Respond to inquiries about absence data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into absence transactions</p></td>
<td><p>HcmAbsenceTransactionInquire</p></td>
<td><p>Respond to inquiries about absence transactions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into applicant master</p></td>
<td><p>HcmApplicantInquire</p></td>
<td><p>Respond to inquiries about applicant master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into compensation process</p></td>
<td><p>HcmCompensationInquire</p></td>
<td><p>Respond to inquiries about compensation data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into compensation transactions</p></td>
<td><p>HcmCompensationTransactionInquire</p></td>
<td><p>Respond to inquiries about compensation transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into employee cases</p></td>
<td><p>CaseEmployeeCaseInquire</p></td>
<td><p>Respond to inquiries about employee cases</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into jobs and positions</p></td>
<td><p>HcmJobPositionInquire</p></td>
<td><p>Respond to inquiries about job and position data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into organizational process</p></td>
<td><p>HcmOrganizationalProcessInquire</p></td>
<td><p>Respond to inquiries about organizational reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into questionnaire process</p></td>
<td><p>HcmQuestionnaireProcessInquire</p></td>
<td><p>Respond to inquiries about questionnaire data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into questionnaire transactions</p></td>
<td><p>HcmQuestionnaireTransactionInquire</p></td>
<td><p>Respond to inquiries about questionnaire transactions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into recruitment process</p></td>
<td><p>HcmRecruitmentProcessInquire</p></td>
<td><p>Respond to inquiries about recruitment reference data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into time and attendance policies</p></td>
<td><p>JmgTimeAttendancePoliciesInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into training process</p></td>
<td><p>HcmTrainingProcessInquire</p></td>
<td><p>Respond to inquiries about training data</p></td>
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
<td><p>Maintain cases</p></td>
<td><p>CaseCasesMaintain</p></td>
<td><p>Maintain cases</p></td>
</tr>
<tr class="odd">
<td><p>Maintain document service operation</p></td>
<td><p>HcmJobServicesMaintain</p></td>
<td><p>Read/create job applications and also inquire about job postings</p></td>
</tr>
<tr class="even">
<td><p>Maintain employee cases</p></td>
<td><p>CaseEmployeeCasesMaintain</p></td>
<td><p>Maintain employee cases</p></td>
</tr>
<tr class="odd">
<td><p>Maintain global address book master</p></td>
<td><p>DirAddressBookMasterMaintain</p></td>
<td><p>Maintain global address book master</p></td>
</tr>
<tr class="even">
<td><p>Review absence information</p></td>
<td><p>HcmAbsenceReview</p></td>
<td><p>Monitor, analyze, and improve the absence process</p></td>
</tr>
<tr class="odd">
<td><p>Review case process</p></td>
<td><p>CaseCaseProcessReview</p></td>
<td><p>Monitor, analyze, and improve the case process</p></td>
</tr>
<tr class="even">
<td><p>Review compensation information</p></td>
<td><p>HcmCompensationReview</p></td>
<td><p>Monitor, analyze, and improve compensation information</p></td>
</tr>
<tr class="odd">
<td><p>Review organizational information</p></td>
<td><p>HcmOrganizationalReview</p></td>
<td><p>Monitor, analyze, and improve organizational information</p></td>
</tr>
<tr class="even">
<td><p>Review performance information</p></td>
<td><p>HcmPerformanceReview</p></td>
<td><p>Monitor, analyze, and improve worker-related performance information</p></td>
</tr>
<tr class="odd">
<td><p>Review questionnaire information</p></td>
<td><p>HcmQuestionnaireReview</p></td>
<td><p>Monitor, analyze, and improve questionnaire information</p></td>
</tr>
<tr class="even">
<td><p>Review recruitment information</p></td>
<td><p>HcmRecruitmentReview</p></td>
<td><p>Monitor, analyze, and improve recruitment information</p></td>
</tr>
<tr class="odd">
<td><p>Review training information</p></td>
<td><p>HcmTrainingReview</p></td>
<td><p>Monitor, analyze, and improve training information</p></td>
</tr>
<tr class="even">
<td><p>Review workforce management information</p></td>
<td><p>HcmWorkforceReview</p></td>
<td><p>Monitor, analyze, and improve workforce management information</p></td>
</tr>
<tr class="odd">
<td><p>Solution and online pages available in human resource area</p></td>
<td><p>HcmSitesSolutionMaintain</p></td>
<td><p></p></td>
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
<td><p>Approve worker user requests</p></td>
<td><p>HcmWorkerUserRequestApprove</p></td>
<td><p>View and approve worker user requests</p></td>
</tr>
<tr class="odd">
<td><p>Enable human resource process</p></td>
<td><p>HcmHREnable</p></td>
<td><p>Set up policies and reference data to enable the human resources process</p></td>
</tr>
<tr class="even">
<td><p>Enable human resources policy</p></td>
<td><p>HcmBenefitPolicyProcessEnable</p></td>
<td><p>Set up policies to enable human resource eligibility rules</p></td>
</tr>
<tr class="odd">
<td><p>Enable performance process</p></td>
<td><p>HcmPerformanceProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the performance process for workers</p></td>
</tr>
<tr class="even">
<td><p>Enable the global address book process</p></td>
<td><p>DirAddressBookProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the global address book process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into absence process</p></td>
<td><p>HcmAbsenceProcessInquire</p></td>
<td><p>Respond to inquiries about absence data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into absence transactions</p></td>
<td><p>HcmAbsenceTransactionInquire</p></td>
<td><p>Respond to inquiries about absence transactions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into applicant master</p></td>
<td><p>HcmApplicantInquire</p></td>
<td><p>Respond to inquiries about applicant master data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into benefits process</p></td>
<td><p>HcmBenefitInquire</p></td>
<td><p>Respond to inquiries about benefits data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into compensation process</p></td>
<td><p>HcmCompensationInquire</p></td>
<td><p>Respond to inquiries about compensation data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into compensation transactions</p></td>
<td><p>HcmCompensationTransactionInquire</p></td>
<td><p>Respond to inquiries about compensation transactions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into employee cases</p></td>
<td><p>CaseEmployeeCaseInquire</p></td>
<td><p>Respond to inquiries about employee cases</p></td>
</tr>
<tr class="even">
<td><p>Inquire into forecast positions</p></td>
<td><p>HcmForecastInquire</p></td>
<td><p>Respond to inquiries about forecast position data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into jobs and positions</p></td>
<td><p>HcmJobPositionInquire</p></td>
<td><p>Respond to inquiries about job and position data</p></td>
</tr>
<tr class="even">
<td><p>Inquire into organizational process</p></td>
<td><p>HcmOrganizationalProcessInquire</p></td>
<td><p>Respond to inquiries about organizational reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into position actions</p></td>
<td><p>HcmPositionActionProcessInquire</p></td>
<td><p>Respond to inquiries about position actions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into questionnaire process</p></td>
<td><p>HcmQuestionnaireProcessInquire</p></td>
<td><p>Respond to inquiries about questionnaire data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into questionnaire transactions</p></td>
<td><p>HcmQuestionnaireTransactionInquire</p></td>
<td><p>Respond to inquiries about questionnaire transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into recruitment process</p></td>
<td><p>HcmRecruitmentProcessInquire</p></td>
<td><p>Respond to inquiries about recruitment reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into time and attendance policies</p></td>
<td><p>JmgTimeAttendancePoliciesInquire</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into training process</p></td>
<td><p>HcmTrainingProcessInquire</p></td>
<td><p>Respond to inquiries about training data</p></td>
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
<td><p>Inquire into workforce management process</p></td>
<td><p>HcmWorkforceProcessInquire</p></td>
<td><p>Respond to inquiries about workforce reference data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire person screening records</p></td>
<td><p>HcmPersonScreeningInquire</p></td>
<td><p>Allow user to inquire person screening records</p></td>
</tr>
<tr class="even">
<td><p>Maintain cases</p></td>
<td><p>CaseCasesMaintain</p></td>
<td><p>Maintain cases</p></td>
</tr>
<tr class="odd">
<td><p>Maintain document service operation</p></td>
<td><p>HcmJobServicesMaintain</p></td>
<td><p>Read/create job applications and also inquire about job postings</p></td>
</tr>
<tr class="even">
<td><p>Maintain employee cases</p></td>
<td><p>CaseEmployeeCasesMaintain</p></td>
<td><p>Maintain employee cases</p></td>
</tr>
<tr class="odd">
<td><p>Maintain global address book master</p></td>
<td><p>DirAddressBookMasterMaintain</p></td>
<td><p>Maintain global address book master</p></td>
</tr>
<tr class="even">
<td><p>Maintain position actions</p></td>
<td><p>HcmPositionActionProcessMaintain</p></td>
<td><p>Maintain position actions</p></td>
</tr>
<tr class="odd">
<td><p>Review absence information</p></td>
<td><p>HcmAbsenceReview</p></td>
<td><p>Monitor, analyze, and improve the absence process</p></td>
</tr>
<tr class="even">
<td><p>Review case process</p></td>
<td><p>CaseCaseProcessReview</p></td>
<td><p>Monitor, analyze, and improve the case process</p></td>
</tr>
<tr class="odd">
<td><p>Review compensation information</p></td>
<td><p>HcmCompensationReview</p></td>
<td><p>Monitor, analyze, and improve compensation information</p></td>
</tr>
<tr class="even">
<td><p>Review organizational information</p></td>
<td><p>HcmOrganizationalReview</p></td>
<td><p>Monitor, analyze, and improve organizational information</p></td>
</tr>
<tr class="odd">
<td><p>Review performance information</p></td>
<td><p>HcmPerformanceReview</p></td>
<td><p>Monitor, analyze, and improve worker-related performance information</p></td>
</tr>
<tr class="even">
<td><p>Review questionnaire information</p></td>
<td><p>HcmQuestionnaireReview</p></td>
<td><p>Monitor, analyze, and improve questionnaire information</p></td>
</tr>
<tr class="odd">
<td><p>Review recruitment information</p></td>
<td><p>HcmRecruitmentReview</p></td>
<td><p>Monitor, analyze, and improve recruitment information</p></td>
</tr>
<tr class="even">
<td><p>Review training information</p></td>
<td><p>HcmTrainingReview</p></td>
<td><p>Monitor, analyze, and improve training information</p></td>
</tr>
<tr class="odd">
<td><p>Review workforce management information</p></td>
<td><p>HcmWorkforceReview</p></td>
<td><p>Monitor, analyze, and improve workforce management information</p></td>
</tr>
<tr class="even">
<td><p>Set up position action workflows</p></td>
<td><p>HcmPositionActionWFProcessEnable</p></td>
<td><p>Create or modify position action workflows</p></td>
</tr>
<tr class="odd">
<td><p>Solution and online pages available in human resource area</p></td>
<td><p>HcmSitesSolutionMaintain</p></td>
<td><p></p></td>
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
<td><p>Review case process</p></td>
<td><p>CaseCaseProcessReview</p></td>
<td><p>Monitor, analyze, and improve the case process</p></td>
</tr>
<tr class="even">
<td><p>Maintain cases</p></td>
<td><p>CaseCasesMaintain</p></td>
<td><p>Maintain cases</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into employee cases</p></td>
<td><p>CaseEmployeeCaseInquire</p></td>
<td><p>Respond to inquiries about employee cases</p></td>
</tr>
<tr class="even">
<td><p>Maintain employee cases</p></td>
<td><p>CaseEmployeeCasesMaintain</p></td>
<td><p>Maintain employee cases</p></td>
</tr>
<tr class="odd">
<td><p>Maintain global address book master</p></td>
<td><p>DirAddressBookMasterMaintain</p></td>
<td><p>Maintain global address book master</p></td>
</tr>
<tr class="even">
<td><p>Enable the global address book process</p></td>
<td><p>DirAddressBookProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the global address book process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into absence process</p></td>
<td><p>HcmAbsenceProcessInquire</p></td>
<td><p>Respond to inquiries about absence data</p></td>
</tr>
<tr class="even">
<td><p>Review absence information</p></td>
<td><p>HcmAbsenceReview</p></td>
<td><p>Monitor, analyze, and improve the absence process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into absence transactions</p></td>
<td><p>HcmAbsenceTransactionInquire</p></td>
<td><p>Respond to inquiries about absence transactions</p></td>
</tr>
<tr class="even">
<td><p>Inquire into applicant master</p></td>
<td><p>HcmApplicantInquire</p></td>
<td><p>Respond to inquiries about applicant master data</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into worker bank account master</p></td>
<td><p>HcmBankAccountsInquire</p></td>
<td><p>Respond to inquiries about worker bank account master data</p></td>
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
<td><p>Inquire into compensation process</p></td>
<td><p>HcmCompensationInquire</p></td>
<td><p>Respond to inquiries about compensation data</p></td>
</tr>
<tr class="odd">
<td><p>Review compensation information</p></td>
<td><p>HcmCompensationReview</p></td>
<td><p>Monitor, analyze, and improve compensation information</p></td>
</tr>
<tr class="even">
<td><p>Inquire into compensation transactions</p></td>
<td><p>HcmCompensationTransactionInquire</p></td>
<td><p>Respond to inquiries about compensation transactions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into records needed for compliance reporting</p></td>
<td><p>HcmComplianceInquire</p></td>
<td><p>Review data needed to complete mandatory reports</p></td>
</tr>
<tr class="even">
<td><p>Inquire into data that is available in the human resource cube</p></td>
<td><p>HcmCubeInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Inquire into forecast positions</p></td>
<td><p>HcmForecastInquire</p></td>
<td><p>Respond to inquiries about forecast position data</p></td>
</tr>
<tr class="even">
<td><p>Enable human resource process</p></td>
<td><p>HcmHREnable</p></td>
<td><p>Set up policies and reference data to enable the human resources process</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into jobs and positions</p></td>
<td><p>HcmJobPositionInquire</p></td>
<td><p>Respond to inquiries about job and position data</p></td>
</tr>
<tr class="even">
<td><p>Maintain document service operation</p></td>
<td><p>HcmJobServicesMaintain</p></td>
<td><p>Read/create job applications and also inquire about job postings</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into organizational process</p></td>
<td><p>HcmOrganizationalProcessInquire</p></td>
<td><p>Respond to inquiries about organizational reference data</p></td>
</tr>
<tr class="even">
<td><p>Review organizational information</p></td>
<td><p>HcmOrganizationalReview</p></td>
<td><p>Monitor, analyze, and improve organizational information</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into workplace incident records needed for OSHA reporting</p></td>
<td><p>HcmOSHAInquire</p></td>
<td><p>Review data needed to complete mandatory OSHA reports</p></td>
</tr>
<tr class="even">
<td><p>Enable performance process</p></td>
<td><p>HcmPerformanceProcessEnable</p></td>
<td><p>Set up policies and reference data to enable the performance process for workers</p></td>
</tr>
<tr class="odd">
<td><p>Review performance information</p></td>
<td><p>HcmPerformanceReview</p></td>
<td><p>Monitor, analyze, and improve worker-related performance information</p></td>
</tr>
<tr class="even">
<td><p>Inquire into worker personal identifications</p></td>
<td><p>HcmPersonIdentificationInquire</p></td>
<td><p>Respond to inquiries about worker personal identification</p></td>
</tr>
<tr class="odd">
<td><p>Inquire person screening records</p></td>
<td><p>HcmPersonScreeningInquire</p></td>
<td><p>Allow user to inquire person screening records</p></td>
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
<td><p>Maintain position actions</p></td>
<td><p>HcmPositionActionProcessMaintain</p></td>
<td><p>Maintain position actions</p></td>
</tr>
<tr class="odd">
<td><p>Set up position action workflows</p></td>
<td><p>HcmPositionActionWFProcessEnable</p></td>
<td><p>Create or modify position action workflows</p></td>
</tr>
<tr class="even">
<td><p>Inquire into questionnaire process</p></td>
<td><p>HcmQuestionnaireProcessInquire</p></td>
<td><p>Respond to inquiries about questionnaire data</p></td>
</tr>
<tr class="odd">
<td><p>Review questionnaire information</p></td>
<td><p>HcmQuestionnaireReview</p></td>
<td><p>Monitor, analyze, and improve questionnaire information</p></td>
</tr>
<tr class="even">
<td><p>Inquire into questionnaire transactions</p></td>
<td><p>HcmQuestionnaireTransactionInquire</p></td>
<td><p>Respond to inquiries about questionnaire transactions</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into recruitment process</p></td>
<td><p>HcmRecruitmentProcessInquire</p></td>
<td><p>Respond to inquiries about recruitment reference data</p></td>
</tr>
<tr class="even">
<td><p>Review recruitment information</p></td>
<td><p>HcmRecruitmentReview</p></td>
<td><p>Monitor, analyze, and improve recruitment information</p></td>
</tr>
<tr class="odd">
<td><p>Solution and online pages available in human resource area</p></td>
<td><p>HcmSitesSolutionMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Inquire into training process</p></td>
<td><p>HcmTrainingProcessInquire</p></td>
<td><p>Respond to inquiries about training data</p></td>
</tr>
<tr class="odd">
<td><p>Review training information</p></td>
<td><p>HcmTrainingReview</p></td>
<td><p>Monitor, analyze, and improve training information</p></td>
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
<td><p>Set up worker action workflows</p></td>
<td><p>HcmWorkerActionWFProcessEnable</p></td>
<td><p>Create or modify worker action workflows</p></td>
</tr>
<tr class="even">
<td><p>Inquire into workers</p></td>
<td><p>HcmWorkerInquire</p></td>
<td><p>Respond to inquiries about employee and contractor data</p></td>
</tr>
<tr class="odd">
<td><p>Approve worker user requests</p></td>
<td><p>HcmWorkerUserRequestApprove</p></td>
<td><p>View and approve worker user requests</p></td>
</tr>
<tr class="even">
<td><p>Inquire into workforce management process</p></td>
<td><p>HcmWorkforceProcessInquire</p></td>
<td><p>Respond to inquiries about workforce reference data</p></td>
</tr>
<tr class="odd">
<td><p>Review workforce management information</p></td>
<td><p>HcmWorkforceReview</p></td>
<td><p>Monitor, analyze, and improve workforce management information</p></td>
</tr>
<tr class="even">
<td><p>Inquire into time and attendance policies</p></td>
<td><p>JmgTimeAttendancePoliciesInquire</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Average earnings</p></td>
<td><p>RPayEarningInquire</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

