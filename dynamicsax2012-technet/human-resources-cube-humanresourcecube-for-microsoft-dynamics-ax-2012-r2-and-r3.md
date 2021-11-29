---
title: Human resources cube (HumanResourceCube) for Microsoft Dynamics AX 2012 R2 and R3
TOCTitle: Human resources cube (HumanResourceCube)
ms:assetid: 8c46617d-cb6a-4700-ac0b-1e9c170cdad6
ms:mtpsurl: https://technet.microsoft.com/library/Dn530765(v=AX.60)
ms:contentKeyID: 59683044
author: Khairunj
ms.date: 07/30/2014
mtps_version: v=AX.60
---

# Human resources cube (HumanResourceCube) for Microsoft Dynamics AX 2012 R2 and R3 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Human resources cube for Microsoft Dynamics AX is used to analyze data for applicants, workers, positions, jobs, and courses. Analysis of human resources data is required for organizations to effectively manage their workforce and make decisions based on accurate information. This article provides details about the cube.


> [!NOTE]
> <P>This cube is available with cumulative update 7 for Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>



<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/JJ710380.TopicIcons_Reference(AX.60).png" title="Reference" alt="Reference" />
<p>Deployment</p>
<p>Configuration keys</p>
<p>Tables and views</p>
<p>Measures</p>
<p>Calculated measures</p>
<p>Key performance indicators</p>
<p>Security</p></td>
<td><img src="images/Dn507140.TopicIcons_Resources(AX.60).png" title="Resources" alt="Resources" />
<p><a href="analytics-in-microsoft-dynamics-ax.md">Analytics in Microsoft Dynamics AX</a></p>
<p><a href="cube-and-kpi-reference-for-microsoft-dynamics-ax-2012-r2-and-r3.md">Cube and KPI reference for Microsoft Dynamics AX 2012 R2 and R3</a></p>
<p><a href="cube-and-kpi-reference-for-microsoft-dynamics-ax-2012-and-microsoft-dynamics-ax-2012-feature-pack.md">Cube and KPI reference for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack</a></p></td>
</tr>
</tbody>
</table>


## Deployment

The Human resources cube is included in the Dynamics AX project. For information about how deploy the Dynamics AX project—and the cubes that it contains—see [Deploy the default cubes](deploy-the-default-cubes.md).

## Configuration keys

The following configuration keys are required to use all features of the Human resources cube:

  - Human resource I (HRMAdministration)

  - Human resource II (HRMManagment)

  - Human resource III (HRMCollaborative)

## Tables and views

The Human resources cube uses data from the following tables and views:

  - HcmBenefitOption table

  - HcmBenefitPlan table

  - HcmBenefitType table

  - HcmJob table

  - HcmPersonProfessionalExperience table

  - HcmPersonProjectRole table

  - HcmPersonTrustedPosition table

  - HcmPosition table

  - HcmPositionWorkerAssignment table

  - HcmRatingModel table

  - HcmSkillType table

  - HRMApplication table

  - HRMApplicationBasket table

  - HRMCompFixedAction table

  - HRMCompFixedEmpl table

  - HRMCompFixedPlanTable table

  - HRMCompPayFrequency table

  - HRMCompVarAwardEmpl table

  - HRMCompVarEnrollEmpl table

  - HRMCompVarPlanTable table

  - HRMCompVarPlanType table

  - HRMCompVesting table

  - HRMCourseTable table

  - HRMMedia table

  - HRMRecruitingTable table

  - HcmApplicantCube view

  - HcmCompetenciesCube view

  - HcmCourseTypeCube view

  - HcmDepartmentCube view

  - HcmEmploymentCube view

  - HcmEmploymentDetailCube view

  - HcmEmploymentTurnOverCube view

  - HcmJobCertificatesCube view

  - HcmJobCube view

  - HcmJobEducationDisciplineCube view

  - HcmJobResponsibilityCube view

  - HcmJobScreeningCube view

  - HcmJobSkillsCube view

  - HcmJobTaskAssignmentCube view

  - HcmJobTestsCube view

  - HcmPersonCertificateCube view

  - HcmPersonDetailsCube view

  - HcmPersonEducationCube view

  - HcmPersonScreeningCube view

  - HcmPersonSkillCube view

  - HcmPersonTestsCube view

  - HcmPositionDetailCube view

  - HcmUnionAgreementCube view

  - HcmWorkerEnrolledBenefitsCube view

  - HRMCompFixedEmplCube view

  - HRMCompVarAwardEmplCube view

  - HRMCompVarEnrollEmplCube view

  - HRMCourseAttendeeCube view

  - HRMCourseInstructorCube view

  - HRMRecruitingProjectCube view

## Measures

The Human resources cube includes the following measure groups.

## Fixed compensation

This measure group is based on the HRMCompFixedEmpl table and includes the following measures.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Measure</p></th>
<th><p>Measure field name</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
<th><p>Associated dimensions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Fixed compensation count</p></td>
<td><p>Not applicable</p></td>
<td><p>Count</p></td>
<td><p>This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.</p></td>
<td><p>Company</p>
<p>Fixed compensation</p>
<p>Position</p>
<p>Fixed compensation action</p>
<p>Compensation pay frequency</p>
<p>Compensation fixed plan</p>
<p>Worker</p>
<p>Date (effective date)</p></td>
</tr>
</tbody>
</table>


## Variable compensation enrollment

This measure group is based on the HRMCompVarEnrollEmpl table and includes the following measures.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Measure</p></th>
<th><p>Measure field name</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
<th><p>Associated dimensions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Variable compensation enrollment count</p></td>
<td><p>Not applicable</p></td>
<td><p>Count</p></td>
<td><p>This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.</p></td>
<td><p>Company</p>
<p>Variable compensation enrollment</p>
<p>Compensation variable plan</p>
<p>Worker</p>
<p>Date (effective date)</p></td>
</tr>
</tbody>
</table>


## Variable compensation

This measure group is based on the HRMCompVarAwardEmpl table and includes the following measures.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Measure</p></th>
<th><p>Measure field name</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
<th><p>Associated dimensions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Variable compensation count</p></td>
<td><p>Not applicable</p></td>
<td><p>Count</p></td>
<td><p>This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.</p></td>
<td><p>Company</p>
<p>Compensation variable plan</p>
<p>Compensation variable type</p>
<p>Compensation vesting rules</p>
<p>Compensation fixed plan</p>
<p>Variable compensation</p>
<p>Worker</p></td>
</tr>
</tbody>
</table>


## Application basket

This measure group is based on the HRMApplicationBasket table and includes the following measures.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Measure</p></th>
<th><p>Measure field name</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
<th><p>Associated dimensions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Application basket count</p></td>
<td><p>HRMApplicationBasket.HRMApplicantID</p></td>
<td><p>Count</p></td>
<td><p>The number of job applications in an application basket.</p></td>
<td><p>Company</p>
<p>Recruitment projects</p></td>
</tr>
</tbody>
</table>


## Applications

This measure group is based on the HRMApplication table and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th colspan="1"> <p>
   
	 Measure field name
  </p> </th>
    <th colspan="1"> <p>
   
	 Aggregation
  </p> </th>
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Count of applications
  </p> </td>
    <td colspan="1"> <p>
   
	 HRMApplication.Applicant
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of job applications related to a recruitment project.
  </p> </td>
    <td rowspan="4"> <p>
   
	 Company
  </p> <p>
   
	 Job
  </p> <p>
   
	 Applications
  </p> <p>
   
	 Media
  </p> <p>
   
	 Recruitment projects
  </p> <p>
   
	 Applicant
  </p> <p>
   
	 Departments
  </p> <p>
   
	 Application and recruitment project cube
  </p> <p>
   
	 Worker
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Sum of travel cost
  </p> </td>
    <td> <p>
   
	 HRMApplication.TravelCostMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of Travel Cost on the Application form.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Sum of lodging cost
  </p> </td>
    <td> <p>
   
	 HRMApplication.LodgingCostMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of Lodging Cost on the Application form.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Sum of other cost
  </p> </td>
    <td> <p>
   
	 HRMApplication.OtherCostMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The sum of Other Cost on the Application form.
  </p> </td>
  </tr>
</table>


## Workers

This measure group is based on the HCMEmploymentCube view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th colspan="1"> <p>
   
	 Measure field name
  </p> </th>
    <th colspan="1"> <p>
   
	 Aggregation
  </p> </th>
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Workers count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td rowspan="8"> <p>
   
	 See the Calculated measures section.
  </p> <p></p> <p></p> <p></p> <p></p> <p></p> <p></p> <p></p> </td>
    <td rowspan="8"> <p>
   
	 Company
  </p> <p>
   
	 Position worker assignments
  </p> <p>
   
	 Employment
  </p> <p>
   
	 Employment details
  </p> <p>
   
	 Jobs
  </p> <p>
   
	 Departments
  </p> <p>
   
	 Positions
  </p> <p>
   
	 Union agreement
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Date (employment end date)
  </p> <p>
   
	 Date (assignment start date)
  </p> <p>
   
	 Date (assignment end date)
  </p> <p>
   
	 Date (leave start date)
  </p> <p>
   
	 Date (leave end date)
  </p> <p>
   
	 Date (employment start date)
  </p> <p>
   
	 Worker (recruiter)
  </p> <p>
   
	 Worker (hiring manager)
  </p> <p>
   
	 Worker details
  </p> <p></p> <p></p> <p></p> <p></p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 EmployeeServiceLength0to5
  </p> </td>
    <td> <p>
   
	 HCMEmploymentCube.EmployeeServiceLength0To5
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 EmployeeServiceLength11to15
  </p> </td>
    <td> <p>
   
	 HCMEmploymentCube.EmployeeServiceLength11To15
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 EmployeeServiceLength6to10
  </p> </td>
    <td> <p>
   
	 HCMEmploymentCube.EmployeeServiceLength6To10
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 EmployeeServiceLengthMoreThan15
  </p> </td>
    <td> <p>
   
	 HCMEmploymentCube.EmployeeServiceLengthMoreThan15
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 LengthOfService
  </p> </td>
    <td> <p>
   
	 HCMEmploymentCube.LengthOfService
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 IsEmployeeActive
  </p> </td>
    <td> <p>
   
	 HCMEmploymentCube.IsEmployeeActive
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Count of employee leaves
  </p> </td>
    <td> <p>
   
	 HCMEmploymentCube.HCMEmploymentLeaveRecID
  </p> </td>
    <td> <p>
   
	 Count
  </p> </td>
  </tr>
</table>


## Employment turnover

This measure group is based on the HCMEmploymentTurnoverCube view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th colspan="1"> <p>
   
	 Measure field name
  </p> </th>
    <th colspan="1"> <p>
   
	 Aggregation
  </p> </th>
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Employment turnover count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td rowspan="2"> <p>
   
	 See the Calculated measures section.
  </p> <p></p> </td>
    <td rowspan="2"> <p>
   
	 Company
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Date (employment end date)
  </p> <p>
   
	 Worker (recruiter)
  </p> <p>
   
	 Worker (hiring manager)
  </p> <p></p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Employment turnover count of workers
  </p> </td>
    <td> <p>
   
	 HCMEmploymentTurnoverCube.Worker
  </p> </td>
    <td> <p>
   
	 Distinct count
  </p> </td>
  </tr>
</table>


## Job - certificates

This measure group is based on the HCMCompetenciesCube view, HCMApplicantCube view, and HCMJobCertificatesCube view and includes the following measures.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Measure</p></th>
<th><p>Measure field name</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
<th><p>Associated dimensions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Count of certificates</p></td>
<td><p>HCMJobCertificatesCube.HCMJobPreferredCertificateRecID</p></td>
<td><p>Distinct count</p></td>
<td><p>The number of certificates for a job. For details, see the Certificates tab on the Job Details form.</p></td>
<td><p>Job - certificates</p>
<p>Jobs</p></td>
</tr>
</tbody>
</table>


## Competencies

This measure group is based on the HCMCompetenciesCube view, HCMPersonScreeningCube view, HCMPersonTestsCube view, HCMPersonCertificateCube view, HCMPersonEducationCube view, and HCMPersonSkillCube view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th colspan="1"> <p>
   
	 Measure field name
  </p> </th>
    <th colspan="1"> <p>
   
	 Aggregation
  </p> </th>
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Count of workers
  </p> </td>
    <td colspan="1"> <p>
   
	 HCMCompetenciesCube.Worker
  </p> </td>
    <td colspan="1"> <p>
   
	 Distinct count
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of workers having competencies as defined on the Competencies tab of the Worker list page.
  </p> </td>
    <td rowspan="2"> <p>
   
	 Company
  </p> <p>
   
	 Professional experience
  </p> <p>
   
	 Project experience
  </p> <p>
   
	 Position of trust
  </p> <p>
   
	 Rating models
  </p> <p>
   
	 Skill type
  </p> <p>
   
	 Courses
  </p> <p>
   
	 Applicant
  </p> <p>
   
	 Certificates
  </p> <p>
   
	 Education
  </p> <p>
   
	 Screenings
  </p> <p>
   
	 Skills
  </p> <p>
   
	 Tests
  </p> <p>
   
	 Worker
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Count of applicants
  </p> </td>
    <td> <p>
   
	 HCMCompetenciesCube.Applicant
  </p> </td>
    <td> <p>
   
	 Count
  </p> </td>
    <td> <p>
   
	 The number of applicants having competencies as defined on the Competencies tab of the Applicants list page.
  </p> </td>
  </tr>
</table>


## Job - education

This measure group is based on the HCMCompetenciesCube view, HCMApplicantCube view, and HCMJobEducationDisciplineCube view and includes the following measures.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Measure</p></th>
<th><p>Measure field name</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
<th><p>Associated dimensions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Count of education disciplines</p></td>
<td><p>HCMJobEducationDisciplineCube.HCMJobPreferredEducationDisciplineRecID</p></td>
<td><p>Distinct count</p></td>
<td><p>The job details that cover the Education FastTab for a job.</p></td>
<td><p>Jobs</p>
<p>Job - education</p></td>
</tr>
</tbody>
</table>


## Job – areas of responsibility

This measure group is based on the HCMCompetenciesCube view, HCMApplicantCube view, and HCMJobResponsibilityCube view and includes the following measures.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Measure</p></th>
<th><p>Measure field name</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
<th><p>Associated dimensions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Count of responsibilities</p></td>
<td><p>HCMJobResponsibilityCube.HCMJobResponsibilityRecID</p></td>
<td><p>Distinct count</p></td>
<td><p>The number of areas of responsibility for a job. For details, see the Areas of Responsibility tab in the Job Details form.</p></td>
<td><p>Jobs</p>
<p>Job – areas of responsibility</p></td>
</tr>
</tbody>
</table>


## Job - screening

This measure group is based on the HCMCompetenciesCube view, HCMApplicantCube view, and HCMJobScreeningCube view and includes the following measures.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Measure</p></th>
<th><p>Measure field name</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
<th><p>Associated dimensions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Count of screenings</p></td>
<td><p>HCMJobScreeningCube.HCMJobScreeningRecID</p></td>
<td><p>Distinct count</p></td>
<td><p>The number of screenings for a job. For details, see the Screenings tab in the Job Details form.</p></td>
<td><p>Jobs</p>
<p>Job - screening</p></td>
</tr>
</tbody>
</table>


## Job - skills

This measure group is based on the HCMCompetenciesCube view, HCMApplicantCube view, and HCMJobSkillsCube view and includes the following measures.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Measure</p></th>
<th><p>Measure field name</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
<th><p>Associated dimensions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Count of skills</p></td>
<td><p>HCMJobSkillsCube.HCMJobPreferredRecID</p></td>
<td><p>Distinct count</p></td>
<td><p>The number of skills for a job. For details, see the Skills tab in the Job Details form.</p></td>
<td><p>Jobs</p>
<p>Job - skills</p></td>
</tr>
</tbody>
</table>


## Job – work tasks

This measure group is based on the HCMCompetenciesCube view, HCMApplicantCube view, and HCMJobTasksCube view and includes the following measures.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Measure</p></th>
<th><p>Measure field name</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
<th><p>Associated dimensions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Count of task assignments</p></td>
<td><p>HCMJobTaskAssignmentCube.HCMJobTaskAssignmentRecID</p></td>
<td><p>Distinct count</p></td>
<td><p>The number of job tasks associated with a job. For details, see the Job Tasks tab of the Job Details form.</p></td>
<td><p>Job</p>
<p>Jobs</p>
<p>Job – work tasks</p></td>
</tr>
</tbody>
</table>


## Job - Tests

This measure group is based on the HCMCompetenciesCube view, HCMApplicantCube view, and HCMJobTestsCube view and includes the following measures.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Measure</p></th>
<th><p>Measure field name</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
<th><p>Associated dimensions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Count of tests</p></td>
<td><p>HCMJobTestsCube.HCMJobPreferredExamRedID</p></td>
<td><p>Distinct count</p></td>
<td><p>The number of tests for a job. For details, see the Tests tab of the Job Details form.</p></td>
<td><p>Jobs</p>
<p>Job - tests</p></td>
</tr>
</tbody>
</table>


## Worker enrolled benefits

This measure group is based on the HCMWorkerEnrolledBenefitsCube view and includes the following measures.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Measure</p></th>
<th><p>Measure field name</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
<th><p>Associated dimensions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Number of benefit enrollments</p></td>
<td><p>HCMWorkerEnrolledBenefitsCube.HCMWorkerEnrolledBenefitRecID</p></td>
<td><p>Distinct count</p></td>
<td><p>The number of benefit enrollments, so that you can analyze which workers are associated with which benefits.</p></td>
<td><p>Benefit plan</p>
<p>Benefit option</p>
<p>Benefit type</p>
<p>Jobs</p>
<p>Positions</p>
<p>Union agreement</p>
<p>Worker enrolled benefits</p>
<p>Worker</p>
<p>Date (worker enrolled benefit valid from)</p>
<p>Date (worker enrolled benefit valid to)</p></td>
</tr>
</tbody>
</table>


## Employee fixed compensation

This measure group is based on the HRMComFixedEmplCube view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th colspan="1"> <p>
   
	 Measure field name
  </p> </th>
    <th colspan="1"> <p>
   
	 Aggregation
  </p> </th>
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Employee fixed compensation count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td rowspan="4"> <p>
   
	 See the Calculated measures section.
  </p> <p></p> <p></p> <p></p> </td>
    <td rowspan="4"> <p>
   
	 Company
  </p> <p>
   
	 Fixed compensation
  </p> <p>
   
	 Position
  </p> <p>
   
	 Fixed compensation action
  </p> <p>
   
	 Compensation pay frequency
  </p> <p>
   
	 Compensation fixed plan
  </p> <p>
   
	 Jobs
  </p> <p>
   
	 Positions
  </p> <p>
   
	 Union agreement
  </p> <p>
   
	 Employee fixed compensation
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Date (effective date)
  </p> <p>
   
	 Date (employment end date)
  </p> <p></p> <p></p> <p></p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Increase amount
  </p> </td>
    <td> <p>
   
	 HRMCompFixedEmplCube.IncreaseAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Increase percent
  </p> </td>
    <td> <p>
   
	 HRMCompFixedEmplCube.IncreasePercent
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Pay rate
  </p> </td>
    <td> <p>
   
	 HRMCompFixedEmplCube.PayRate
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
  </tr>
</table>


## Employee variable compensation

This measure group is based on the HRMCompVarAwardEmplCube view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th colspan="1"> <p>
   
	 Measure field name
  </p> </th>
    <th colspan="1"> <p>
   
	 Aggregation
  </p> </th>
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Employee variable compensation count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 See the Calculated measures section.
  </p> </td>
    <td rowspan="3"> <p>
   
	 Company
  </p> <p>
   
	 Compensation variable plan
  </p> <p>
   
	 Compensation variable type
  </p> <p>
   
	 Compensation vesting rules
  </p> <p>
   
	 Compensation fixed plan
  </p> <p>
   
	 Variable compensation
  </p> <p>
   
	 Jobs
  </p> <p>
   
	 Positions
  </p> <p>
   
	 Union agreement
  </p> <p>
   
	 Employee variable compensation
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Date (award date)
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Number of units
  </p> </td>
    <td> <p>
   
	 HRMCompVarAwardEmplCube.Units
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Unit value
  </p> </td>
    <td> <p>
   
	 HRMCompVarAwardEmplCube.UnitValue
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
</table>


## Employee variable compensation enrollment

This measure group is based on the HRMCompVarEnrollEmplCube view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th colspan="1"> <p>
   
	 Measure field name
  </p> </th>
    <th colspan="1"> <p>
   
	 Aggregation
  </p> </th>
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Employee variable compensation enrollment count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td rowspan="4"> <p>
   
	 See the Calculated measures section.
  </p> <p></p> <p></p> <p></p> </td>
    <td rowspan="4"> <p>
   
	 Company
  </p> <p>
   
	 Variable compensation enrollment
  </p> <p>
   
	 Compensation variable plan
  </p> <p>
   
	 Jobs
  </p> <p>
   
	 Departments
  </p> <p>
   
	 Positions
  </p> <p>
   
	 Union agreement
  </p> <p>
   
	 Employee variable compensation enrollment
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Date (effective date)
  </p> <p>
   
	 Date (employment end date)
  </p> <p></p> <p></p> <p></p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Award amount
  </p> </td>
    <td> <p>
   
	 HRMCompVarEnrollEmplCube.AwardAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Award percent
  </p> </td>
    <td> <p>
   
	 HRMCompVarEnrollEmplCube.AwardPercent
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Organization percentage
  </p> </td>
    <td> <p>
   
	 HRMCompVarEnrollEmplCube.OrganizationPercent
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
  </tr>
</table>


## Course participants

This measure group is based on the HCMCourseTypeCube view, HRMCourseAttendeeCube view, HRMCourseInstructorCube view and includes the following measures. See also the Calculated measures section for calculated measures in this measure group.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Measure</p></th>
<th><p>Measure field name</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
<th><p>Associated dimensions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Count of participants with training status</p></td>
<td><p>HRMCourseAttendeeCube.CourseAtteddeID</p></td>
<td><p>Distinct count</p></td>
<td><p>The number of participants that are related to a course.</p></td>
<td><p>Company</p>
<p>Courses</p>
<p>Course type and group</p>
<p>Course participants</p>
<p>Course instructors</p>
<p>Date (course end date)</p>
<p>Date (course start date)</p></td>
</tr>
</tbody>
</table>


## Recruitment projects

This measure group is based on the HRMApplicationRecruitmentProjectCube view, HCMPositionDetailCube view, and HCMJobCube view and includes the following measure. See also the Calculated measures section for calculated measures in this measure group.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th colspan="1"> <p>
   
	 Measure field name
  </p> </th>
    <th colspan="1"> <p>
   
	 Aggregation
  </p> </th>
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Recruitment projects count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of applicants whose applications have a status of employed and an application start date in the time period specified.
  </p> </td>
    <td rowspan="3"> <p>
   
	 Company
  </p> <p>
   
	 Job
  </p> <p>
   
	 Applications
  </p> <p>
   
	 Media
  </p> <p>
   
	 Recruitment projects
  </p> <p>
   
	 Jobs
  </p> <p>
   
	 Applicant
  </p> <p>
   
	 Departments
  </p> <p>
   
	 Positions
  </p> <p>
   
	 Union agreement
  </p> <p>
   
	 Application and recruitment project cube
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Date (effective date)
  </p> <p>
   
	 Date (employment end date)
  </p> <p>
   
	 Worker (recruiter)
  </p> <p>
   
	 Worker (hiring manager)
  </p> <p>
   
	 Date (applicant employment start date)
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Applicants hired count
  </p> </td>
    <td> <p>
   
	 HRMRecruitingProjectCube.HRMApplicationID
  </p> </td>
    <td> <p>
   
	 Distinct count
  </p> </td>
    <td> <p>
   
	 The number of applicants whose applications have a status of employed and an application start date in the time period specified.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 RecruitingDays
  </p> </td>
    <td> <p>
   
	 HRMRecruitingProjectCube.RecruitingDays
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 This measure is used in the calculated measure and is hidden from end users. See the Calculated measures section.
  </p> </td>
  </tr>
</table>


## Calculated measures

The Human resources cube contains the following calculated measures.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Calculated measure</p></th>
<th><p>Aggregation</p></th>
<th><p>Associated measure group</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Average days to recruit</p></td>
<td><p>Number of days from the open date of the recruitment project to the start date of the application for one record. This number is then calculated for all records and added together, and then divided by the number of records.</p></td>
<td><p>Recruitment projects</p></td>
<td><p>All applications that have a status of Employed and have a start date in the time period that is specified are included. This calculated measure uses the Open Date field from the recruitment project and the Start Date field from the application to find the number of days to recruit for each record in the timeframe. The numbers are added for all records and then divided by the number of records. The calculation excludes records that do not have an Open Date and applications without a recruitment project.</p>
<p>The most frequently used dimensions associated with this calculated measure are the following: Recruiter, Department, Hiring manager, Media source, Recruitment projects, Interviewer, Applications, Applicant, Positions, and Jobs.</p></td>
</tr>
<tr class="even">
<td><p>Percentage of participants with confirmation training status</p></td>
<td><p>Number of participants with Confirmation training status divided by total number of participants related to any course.</p></td>
<td><p>Course participants</p></td>
<td><p>Defines the percentage of course participants who have been confirmed for the course.</p>
<p>The most frequently used dimensions associated with this calculated measure are the following: Courses, Course type and group, Course participants, Course instructors, Course start date, and Course end date.</p></td>
</tr>
<tr class="odd">
<td><p>Percentage of participants with completed training status</p></td>
<td><p>Number of participants with Completed training status divided by total number of participants related to any course.</p></td>
<td><p>Course participants</p></td>
<td><p>Defines the percentage of course participants who have completed the course.</p>
<p>The most frequently used dimensions associated with this calculated measure are the following: Courses, Course type and group, Course participants, Course instructors, Course start date, and Course end date.</p></td>
</tr>
<tr class="even">
<td><p>Percentage of participants with passed training status</p></td>
<td><p>Number of participants with Passed training status divided by total number of participants related to any course.</p></td>
<td><p>Course participants</p></td>
<td><p>Defines the percentage of course participants who have passed the course.</p>
<p>The most frequently used dimensions associated with this calculated measure are the following: Courses, Course type and group, Course participants, Course instructors, Course start date, and Course end date.</p></td>
</tr>
<tr class="odd">
<td><p>Percentage of participants with waiting list training status</p></td>
<td><p>Number of participants with Waiting List training status divided by total number of participants related to any course.</p></td>
<td><p>Course participants</p></td>
<td><p>Defines the percentage of course participants who are on the waiting list for the course.</p>
<p>The most frequently used dimensions associated with this calculated measure are the following: Courses, Course type and group, Course participants, Course instructors, Course start date, and Course end date.</p></td>
</tr>
<tr class="even">
<td><p>Percentage of participants with canceled training status</p></td>
<td><p>Number of participants with Canceled training status divided by total number of participants related to any course.</p></td>
<td><p>Course participants</p></td>
<td><p>Defines the percentage of course participants who have canceled.</p>
<p>The most frequently used dimensions associated with this calculated measure are the following: Courses, Course type and group, Course participants, Course instructors, Course start date, and Course end date.</p></td>
</tr>
<tr class="odd">
<td><p>Percentage of participants with dropout training status</p></td>
<td><p>Number of participants with Dropout training status divided by total number of participants related to any course.</p></td>
<td><p>Course participants</p></td>
<td><p>Defines the percentage of course participants who have dropped out of the course.</p>
<p>The most frequently used dimensions associated with this calculated measure are the following: Courses, Course type and group, Course participants, Course instructors, Course start date, and Course end date.</p></td>
</tr>
<tr class="even">
<td><p>Percentage of participants with registered training status</p></td>
<td><p>Number of participants with Registered training status divided by total number of participants related to any course.</p></td>
<td><p>Course participants</p></td>
<td><p>Defines the percentage of course participants who have registered for the course.</p>
<p>The most frequently used dimensions associated with this calculated measure are the following: Courses, Course type and group, Course participants, Course instructors, Course start date, and Course end date.</p></td>
</tr>
<tr class="odd">
<td><p>Number of months of service for a worker</p></td>
<td><p>Length of service divided by count of workers.</p></td>
<td><p>Workers</p></td>
<td><p>Defines seniority at the organization.</p>
<p>The most frequently used dimensions associated with this calculated measure are the following: Worker, Department, Company, and Is employment detail active.</p></td>
</tr>
<tr class="even">
<td><p>Workers with years of service 0-5 count</p></td>
<td><p>Number of workers whose length of service is greater than 0 years and less than 6 years.</p></td>
<td><p>Workers</p></td>
<td><p>Defines seniority at the organization.</p>
<p>The most frequently used dimensions associated with this calculated measure are the following: Worker, Department, Company, Is position detail active, Is position worker assignment active, Is position assigned, and Is employment detail active.</p></td>
</tr>
<tr class="odd">
<td><p>Workers with years of service 6-10 count</p></td>
<td><p>Number of workers whose length of service is greater than 5 years and less than 11 years.</p></td>
<td><p>Workers</p></td>
<td><p>Defines seniority at the organization.</p>
<p>The most frequently used dimensions associated with this calculated measure are the following: Worker, Department, Company, Is position detail active, Is position worker assignment active, Is position assigned, and Is employment detail active.</p></td>
</tr>
<tr class="even">
<td><p>Workers with years of service 11-15 count</p></td>
<td><p>Number of workers whose length of service is greater than 10 years and less than 16 years.</p></td>
<td><p>Workers</p></td>
<td><p>Defines seniority at the organization.</p>
<p>The most frequently used dimensions associated with this calculated measure are the following: Worker, Department, Company, Is position detail active, Is position worker assignment active, Is position assigned, and Is employment detail active.</p></td>
</tr>
<tr class="odd">
<td><p>Workers with more than 15 years of service count</p></td>
<td><p>Number of workers whose length of service is greater than or equal to 15 years.</p></td>
<td><p>Workers</p></td>
<td><p>Defines seniority at the organization.</p>
<p>The most frequently used dimensions associated with this calculated measure are the following: Worker, Department, Company, Is position detail active, Is position worker assignment active, Is position assigned, and Is employment detail active.</p></td>
</tr>
<tr class="even">
<td><p>Number of workers</p></td>
<td><p>Sum of workers with the condition below:</p>
<p>If workers count is greater than zero, then return 1 or return the workers count.</p></td>
<td><p>Workers</p></td>
<td><p>Defines the total number of workers in the Workers form.</p>
<p>The most frequently used dimensions associated with this calculated measure are the following: Worker, Positions, Departments, Company, Is employment detail active, and Is position detail active.</p></td>
</tr>
<tr class="odd">
<td><p>Number of workers terminated</p></td>
<td><p>Sum of workers with the condition below:</p>
<p>If workers count is greater than zero and employment is not active, then return 1 or return null.</p></td>
<td><p>Workers</p></td>
<td><p>Defines the total number of workers terminated.</p>
<p>The most frequently used dimensions associated with this calculated measure are the following: Worker, Positions, Departments, Company, Is employment detail active, and Is position detail active.</p></td>
</tr>
<tr class="even">
<td><p>Number of position assignments</p></td>
<td><p>Sum of position worker assignments.</p></td>
<td><p>Workers</p></td>
<td><p>Defines the total number of position assignments.</p>
<p>The most frequently used dimensions associated with this calculated measure are the following: Worker, Positions, Departments, Company, Is employment detail active, and Is position detail active.</p></td>
</tr>
<tr class="odd">
<td><p>Sum of increase amount</p></td>
<td><p>Sum of the Increase Amount field in the Employee Fixed Compensation form.</p></td>
<td><p>Employee fixed compensation</p></td>
<td><p>The most frequently used dimensions associated with this calculated measure are the following: Company, Employee fixed compensation, Compensation fixed plan, and Worker.</p></td>
</tr>
<tr class="even">
<td><p>Average of increase amount</p></td>
<td><p>Sum of the Increase Amount field divided by the total number of records in the Employee Fixed Compensation form.</p></td>
<td><p>Employee fixed compensation</p></td>
<td><p>The most frequently used dimensions associated with this calculated measure are the following: Company, Employee fixed compensation, Compensation fixed plan, and Worker.</p></td>
</tr>
<tr class="odd">
<td><p>Average of increase percentage</p></td>
<td><p>Sum of the Increase Percent field divided by the total number of records in the Employee Fixed Compensation form.</p></td>
<td><p>Employee fixed compensation</p></td>
<td><p>The most frequently used dimensions associated with this calculated measure are the following: Company, Employee fixed compensation, Compensation fixed plan, and Worker.</p></td>
</tr>
<tr class="even">
<td><p>Sum of annual equivalent</p></td>
<td><p>Sum of the Annual Equivalent field in the Employee Fixed Compensation form.</p></td>
<td><p>Employee fixed compensation</p></td>
<td><p>The most frequently used dimensions associated with this calculated measure are the following: Company, Employee fixed compensation, Compensation fixed plan, and Worker.</p></td>
</tr>
<tr class="odd">
<td><p>Average of annual equivalent</p></td>
<td><p>Sum of Annual Equivalent field divided by the total number of records in the Employee Fixed Compensation form.</p></td>
<td><p>Employee fixed compensation</p></td>
<td><p>The most frequently used dimensions associated with this calculated measure are the following: Company, Employee fixed compensation, Compensation fixed plan, and Worker.</p></td>
</tr>
<tr class="even">
<td><p>Sum of units</p></td>
<td><p>Sum of the Number of Units field in the Employee Variable Compensation Awards form.</p></td>
<td><p>Employee variable compensation</p></td>
<td><p>The most frequently used dimensions associated with this calculated measure are the following: Company, Employee variable compensation, Compensation variable plan, and Worker.</p></td>
</tr>
<tr class="odd">
<td><p>Sum of unit value</p></td>
<td><p>Sum of the Unit Value field in the Employee Variable Compensation Awards form.</p></td>
<td><p>Employee variable compensation</p></td>
<td><p>The most frequently used dimensions associated with this calculated measure are the following: Company, Employee variable compensation, Compensation variable plan, and Worker.</p></td>
</tr>
<tr class="even">
<td><p>Average of units</p></td>
<td><p>Sum of the number of units divided by the total number of records in the Employee Variable Compensation Awards form.</p></td>
<td><p>Employee variable compensation</p></td>
<td><p>The most frequently used dimensions associated with this calculated measure are the following: Company, Employee variable compensation, Compensation variable plan, and Worker.</p></td>
</tr>
<tr class="odd">
<td><p>Average of unit value</p></td>
<td><p>Sum of the Unit Value field divided by the total number of records in the Employee Variable Compensation Awards form.</p></td>
<td><p>Employee variable compensation</p></td>
<td><p>The most frequently used dimensions associated with this calculated measure are the following: Company, Employee variable compensation, Compensation variable plan, and Worker.</p></td>
</tr>
<tr class="even">
<td><p>Sum of award amount</p></td>
<td><p>Sum of the Award Amount field in the Employee Variable Compensation Enrollment form.</p></td>
<td><p>Employee variable compensation enrollment</p></td>
<td><p>The most frequently used dimensions associated with this calculated measure are the following: Company, Employee variable compensation enrollment, Compensation variable plan, and Worker.</p></td>
</tr>
<tr class="odd">
<td><p>Average of award amount</p></td>
<td><p>Sum of the Award Amount field divided by the total number of records in the Employee Variable Compensation Enrollment form.</p></td>
<td><p>Employee variable compensation enrollment</p></td>
<td><p>The most frequently used dimensions associated with this calculated measure are the following: Company, Employee variable compensation enrollment, Compensation variable plan, and Worker.</p></td>
</tr>
<tr class="even">
<td><p>Average of award percentage</p></td>
<td><p>Sum of the Award Percent field divided by the total number of records in the Employee Variable Compensation Enrollment form.</p></td>
<td><p>Employee variable compensation enrollment</p></td>
<td><p>The most frequently used dimensions associated with this calculated measure are the following: Company, Employee variable compensation enrollment, Compensation variable plan, and Worker.</p></td>
</tr>
<tr class="odd">
<td><p>Average of organization percentage</p></td>
<td><p>Sum of the Percent field divided by the total number of records in the Employee Variable Compensation Enrollment form.</p></td>
<td><p>Employee variable compensation enrollment</p></td>
<td><p>The most frequently used dimensions associated with this calculated measure are the following: Company, Employee variable compensation enrollment, Compensation variable plan, and Worker.</p></td>
</tr>
<tr class="even">
<td><p>Sum of monthly equivalent</p></td>
<td><p>Sum of the Monthly Equivalent field in the Employee Fixed Compensation form.</p></td>
<td><p>Employee fixed compensation</p></td>
<td><p>The most frequently used dimensions associated with this calculated measure are the following: Company, Employee fixed compensation, Compensation fixed plan, and Worker.</p></td>
</tr>
<tr class="odd">
<td><p>Sum of hourly equivalent</p></td>
<td><p>Sum of the Hourly Equivalent field in the Employee Fixed Compensation form.</p></td>
<td><p>Employee fixed compensation</p></td>
<td><p>The most frequently used dimensions associated with this calculated measure are the following: Company, Employee fixed compensation, Compensation fixed plan, and Worker.</p></td>
</tr>
<tr class="even">
<td><p>Average of monthly equivalent</p></td>
<td><p>Sum of the Monthly Equivalent field divided by the total number of records in the Employee Fixed Compensation form.</p></td>
<td><p>Employee fixed compensation</p></td>
<td><p>The most frequently used dimensions associated with this calculated measure are the following: Company, Employee fixed compensation, Compensation fixed plan, and Worker.</p></td>
</tr>
<tr class="odd">
<td><p>Average of hourly equivalent</p></td>
<td><p>Sum of the Hourly Equivalent field divided by the total number of records in the Employee Fixed Compensation form.</p></td>
<td><p>Employee fixed compensation</p></td>
<td><p>The most frequently used dimensions associated with this calculated measure are the following: Company, Employee fixed compensation, Compensation fixed plan, and Worker.</p></td>
</tr>
<tr class="even">
<td><p>Employee fixed compensation distinct count</p></td>
<td><p>Count</p></td>
<td><p>Employee fixed compensation</p></td>
<td><p>This calculated measure is hidden to end users. It is used in other calculations.</p></td>
</tr>
<tr class="odd">
<td><p>Workers on leave count</p></td>
<td><p>Number of workers with a leave start and end date. Specifying a time range is optional.</p></td>
<td><p>Workers</p></td>
<td><p>Defines employment leaves at the organization.</p>
<p>The most frequently used dimensions associated with this calculated measure are the following: Worker, Leave start date, Leave end date, and Company.</p></td>
</tr>
<tr class="even">
<td><p>Number of employments</p></td>
<td><p>The number of employments of workers, it sums all of the employments of workers in different legal entities.</p></td>
<td><p>Workers</p></td>
<td><p>Define the total number of worker employments.</p>
<p>The most frequently used dimensions associated with this calculated measure are the following: Worker, Positions, Departments, Company, Is employment detail active, and Is position detail active.</p></td>
</tr>
<tr class="odd">
<td><p>Employment turnover rate</p></td>
<td><p>Total number of employees terminated in the time period, divided by the average number of employees in the time period, then multiplied by 100. (The average number of employees in the time period is calculated as: number of employees at the start of the time period, plus the number of employees at the end of the time period, divided by two.)</p></td>
<td><p>Employment turnover</p></td>
<td><p>The most frequently used dimensions associated with this calculated measure are the following: Company, Employment end date, and Worker.</p></td>
</tr>
<tr class="even">
<td><p>Number of hired workers</p></td>
<td><p>Total number of workers hired in any legal entity.</p></td>
<td><p>Employment turnover</p></td>
<td><p>The most frequently used dimensions associated with this calculated measure are the following: Company, Employment end date, and Worker.</p></td>
</tr>
<tr class="odd">
<td><p>Number of active workers</p></td>
<td><p>Total number of workers that have an active employment in any legal entity.</p></td>
<td><p>Employment turnover</p></td>
<td><p>The most frequently used dimensions associated with this calculated measure are the following: Company, Employment end date, and Worker.</p></td>
</tr>
<tr class="even">
<td><p>Number of active workers - local</p></td>
<td><p>Count</p></td>
<td><p>Employment turnover</p></td>
<td><p>This calculated measure is hidden to end users. It is used in other calculations.</p></td>
</tr>
<tr class="odd">
<td><p>Number of workers terminated - local</p></td>
<td><p>Count</p></td>
<td><p>Workers</p></td>
<td><p>This calculated measure is hidden to end users. It is used in other calculations.</p></td>
</tr>
</tbody>
</table>


## Key performance indicators

The Human resources cube does not include any key performance indicators (KPIs).

## Security

The Human resources cube can be accessed by users assigned to the following Microsoft SQL Server Analysis Services roles.

  - Chief financial officer

  - Compensation and benefits manager

  - Human resource assistant

  - Human resource manager

  - Manager

  - Recruiter

  - Training manager

  


