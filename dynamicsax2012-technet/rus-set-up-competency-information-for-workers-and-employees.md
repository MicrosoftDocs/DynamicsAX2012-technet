---
title: (RUS) Set up competency information for workers and employees
TOCTitle: (RUS) Set up competency information for workers and employees
ms:assetid: 9b2ebb09-42b1-4215-8344-f8329c4a9abd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn745531(v=AX.60)
ms:contentKeyID: 62336124
ms.date: 05/14/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RHRMEducationDegree
- Forms.RHRMEducationType
- Forms.RHRMEvaluationCode
- Forms.RHRMLanguageCode
- Forms.RHRMSocialBenefit
- Forms.RHRMViolationCode
---

# (RUS) Set up competency information for workers and employees 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can hire a worker in a legal entity, and then assign the worker to a single position or multiple positions. When you assign the worker to a position, an employee identification code is assigned to the worker for the position. For example, you hire a worker W1, and then assign the worker to three positions, such as P1, P2, and P3. Three employee identification codes are assigned to the worker, such as E1, E2, and E3.

You can set up the following competency information for workers and employees:

  - Education codes, degree codes, and language codes that are used to record the competency information for workers.

  - Evaluation result codes, violation codes, and privilege codes that are used to record the competency information for employees based on their positions.

When you create a worker record in the Human resources module, and then hire the worker as an employee in the Payroll (Russia) module, you can copy the skill related information of the worker that is defined in the Human resources module to the Payroll (Russia) module. For more information, see [Competency - Skills (form)](https://technet.microsoft.com/en-us/library/aa616428\(v=ax.60\)).

Follow the steps in this topic to set up competency information for workers and employees in the Payroll (Russia) module.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Version</strong></p></td>
<td><p>Microsoft Dynamics AX 2012 R2 Payroll for Russia Feature Pack</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Russia</p></td>
</tr>
</tbody>
</table>


## Set up an education type code and a degree code

Use the **Education** and **Degrees** forms to set up an education type code and an educational degree code that are used to record and maintain competency information for workers.

To perform this task, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Setup** \> **Education** \> **Education**.

2.  Click **New** or press CTRL+N to create a record.

3.  In the **Education** field, enter an identification code that indicates the type of education.

4.  In the **Level** field, select **Secondary**, **Vocational**, or **Higher** as the level of education.

5.  In the **Description** field, enter a description for the education type.

6.  Close the form

7.  Click **Payroll (Russia)** \> **Staff administration** \> **Setup** \> **Education** \> **Degrees**.

8.  Click **New** or press CTRL+N to create a record.

9.  In the **Educational level** field, enter an identification code that indicates the degree of education.

10. In the **Description** field, enter a description for the degree.

## Set up a language code

Use the **Codes of languages** form to set up a code that is used to record and maintain the language proficiency information for workers.

To perform this task, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Setup** \> **Codes of languages**.

2.  Click **New** or press CTRL+N to create a record.

3.  In the **Language code** field, enter an identification code for the language.

4.  In the **Description** field, enter a description for the language code.

## Set up an evaluation result code

Use the **Evaluation results** form to set up an evaluation result code that is used to record and maintain the decisions that are made by the evaluation committee after an employee is evaluated.

To perform this task, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Setup** \> **Evaluation results**.

2.  Click **New** or press CTRL+N to create a record.

3.  In the **Result** field, enter an identification code for the evaluation result.

4.  In the **Description** field, enter a description for the evaluation result.

## Set up a violation code

Use the **Violation codes** form to set up a violation code that is used to record and maintain the information about the disciplinary actions that are taken against an employee.

To perform this task, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Setup** \> **Violation codes**.

2.  Click **New** or press CTRL+N to create a record.

3.  In the **Violations** field, enter an identification code for an employee violation.

4.  In the **Description** field, enter a description of the violation.

## Set up a privilege code

Use the **Privileges** form to set up a privilege code that is used to record and maintain employee benefits.

To perform this task, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Setup** \> **Privileges**.

2.  Click **New** or press CTRL+N to create a record.

3.  In the **Privilege** field, enter an identification code for the employee benefit.

4.  In the **Description** field, enter a description for the benefit code.

## Next step

[(RUS) Record and maintain competency information for workers and employees](rus-record-and-maintain-competency-information-for-workers-and-employees.md)

## Related tasks

[(RUS) Configure staff administration information for workers](rus-configure-staff-administration-information-for-workers.md)

[(RUS) Create a worker](rus-create-a-worker.md)

[(RUS) Hire, transfer, and dismiss a worker](rus-hire-transfer-and-dismiss-a-worker.md)

[(RUS) Support the workforce management process](rus-support-the-workforce-management-process.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Select the <strong>CIS Payroll</strong> and <strong>CIS Staff administration</strong> configuration keys.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To perform this task, you must be a member of a security role that includes the following duties:</p>
<ul>
<li><p><strong>Enable workforce management process</strong> (HcmWorkforceProcessEnable)</p></li>
<li><p><strong>Enable skills management process</strong> (HcmSkillsProcessEnable)</p></li>
<li><p><strong>Inquire into workforce management process</strong> (HcmWorkforceProcessInquire)</p></li>
<li><p><strong>Inquire into compensation process</strong> (HcmCompensationInquire)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To perform this task, you must be a member of a security role that includes the following privileges:</p>
<ul>
<li><p><strong>Maintain competency information for people</strong> (HcmPersonCompetenceMaintain)</p></li>
<li><p><strong>View competency information for people</strong> (HcmPersonCompetenceView)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

