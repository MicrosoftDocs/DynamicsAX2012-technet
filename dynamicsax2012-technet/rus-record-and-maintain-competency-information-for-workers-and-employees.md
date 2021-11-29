---
title: (RUS) Record and maintain competency information for workers and employees
TOCTitle: (RUS) Record and maintain competency information for workers and employees
ms:assetid: f872123c-2da2-4eed-b68e-c7a8e8efaa6b
ms:mtpsurl: https://technet.microsoft.com/library/Dn744249(v=AX.60)
ms:contentKeyID: 62286791
author: Khairunj
ms.date: 05/13/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RHRMVirtualNetworkBenefit
- Forms.RHRMVirtualNetworkEvaluation
- Forms.RHRMVirtualNetworkQualification
- Forms.RHRMVirtualNetworkLanguageSkill
- Forms.RHRMVirtualNetworkEducation
- Forms.RHRMVirtualNetworkViolation
- Forms.RHRMVirtualNetworkVocationalRetraining
- Forms.RHRMVirtualNetworkRaisingSkill
audience: Application User
ms.search.region: Russia
---

# (RUS) Record and maintain competency information for workers and employees 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can hire a worker for a legal entity, and then assign the worker to a single position or to multiple positions. When you assign the worker to a position or positions, an employee identification code is assigned to the worker for the position or positions. For example, you hire worker W1, and then assign the worker to three positions, such as P1, P2, and P3. Three employee identification codes are assigned to the worker, such as E1, E2, and E3.

When you create a worker record in the Human resources module, and then hire the worker as an employee in the Payroll (Russia) module, you can copy the skill related information that is defined in the Human resources module to the Payroll (Russia) module. For more information, see [Competency - Skills (form)](https://technet.microsoft.com/library/aa616428\(v=ax.60\)).

You can record and maintain the following competency information for workers and employees:

  - Education, educational degrees, professional experience, language proficiency, qualification improvement, and retraining information.

  - Evaluation, disciplinary actions, and privilege information for employees depending on their positions.

Follow the steps in this topic to record and maintain the competency information for workers and employees in the Payroll (Russia) module.

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
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><ul>
<li><p>Create employee categories, job titles, positions, and branches. For more information, see <a href="rus-configure-staff-administration-information-for-workers.md">(RUS) Configure staff administration information for workers</a>.</p></li>
<li><p>Create tax registration numbers, social insurance information, and the organizational structure for a legal entity. Create departments in an organization, assign each department to a branch, and reserve a position for a department. For more information, see <a href="rus-configure-organizational-information.md">(RUS) Configure organizational information</a>.</p></li>
<li><p>Create a worker record. For more information, see <a href="rus-create-a-worker.md">(RUS) Create a worker</a>.</p></li>
<li><p>Hire a new employee, transfer an existing employee, and dismiss an employee. For more information, see <a href="rus-hire-transfer-and-dismiss-a-worker.md">(RUS) Hire, transfer, and dismiss a worker</a>.</p></li>
<li><p>Set up education codes, degree codes, language codes, evaluation result codes, violation codes, and privilege codes for workers and employees. For more information, see <a href="rus-set-up-competency-information-for-workers-and-employees.md">(RUS) Set up competency information for workers and employees</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Enter the educational information for a worker

Use the **Education** form to enter and maintain information about worker’s education and degrees.

To perform this task, follow these steps:

1.  Click **Payroll (Russia)** \> **Common** \> **Employees**.

2.  Select a worker to enter the education information for.

3.  On the **Action pane**, on the **Resume** tab, in the **Worker** group, click **Education** to open the **Education** form.

4.  Press CTRL+N to create a line, and then on the **Overview** tab, specify the education code, educational institution, starting and ending dates, and specialization.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Education</strong></p></td>
    <td><p>Select the identification code for the education type.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Educational institution</strong></p></td>
    <td><p>Enter the name of the educational institution where the worker completed education.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Start date</strong></p></td>
    <td><p>Enter the starting date of the worker’s education.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>End date</strong></p></td>
    <td><p>Enter the ending date of the worker’s education.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Specialization</strong></p></td>
    <td><p>Enter the educational specialization.</p></td>
    </tr>
    </tbody>
    </table>


5.  On the **General** tab, specify the education level, diploma details, and specialization details.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Educational level</strong></p></td>
    <td><p>Select the identification code of the degree that was received by the worker.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Diploma</strong></p></td>
    <td><p>Enter the series and number of the diploma that was received by the worker, if required.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Document type</strong></p></td>
    <td><p>Select <strong>Diploma</strong>, <strong>Certificate</strong>, or <strong>Identity Card</strong> as the type of document that confirms the completion of education.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Postgraduate</strong></p></td>
    <td><p>If the worker pursued postgraduate education, select <strong>Candidate</strong>, <strong>Assistant</strong>, or <strong>Doctor</strong> as the level of postgraduate education.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Qualification</strong></p></td>
    <td><p>Enter the name of the qualification that was awarded to the worker, such as Engineer or Specialist Technician.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>OKCO code</strong></p></td>
    <td><p>Enter the Russian identification code of the educational specialization that was completed by the worker.</p></td>
    </tr>
    </tbody>
    </table>


6.  Repeat steps 4 and 5 to add additional educational qualification information for the worker.

## Enter the professional experience information for a worker

Use the **Professional experience** form to enter and maintain the professional experience information for a worker.

To perform this task, follow these steps:

1.  Click **Payroll (Russia)** \> **Common** \> **Employees**.

2.  Select a worker to enter the professional experience information for.

3.  On the **Action pane**, on the **Resume** tab, in the **Worker** group, click **Professional experience** to open the **Professional experience** form.

4.  Press CTRL+N to create a line.

5.  On the **Overview** tab, in the **Name of the organization**, **Position**, **Start date**, and **End date** fields, specify the name of the organization, position, starting date, and ending date for the worker’s previous employment.

6.  On the **General** tab, in the **Location** field, enter the address of the worker’s previous employer.

7.  On the **Note** tab, enter any additional information about the previous employment of the worker.

8.  Repeat steps 4 through 7 to add additional professional experience information for the worker.

## Enter the language proficiency information for a worker

Use the **Language proficiency** form to enter and maintain the language proficiency information for a worker.

To perform this task, follow these steps:

1.  Click **Payroll (Russia)** \> **Common** \> **Employees**.

2.  Select a worker to enter the language proficiency information for.

3.  On the **Action pane**, on the **Resume** tab, in the **Worker** group, click **Language proficiency** to open the **Language proficiency** form.

4.  Press CTRL+N to create a line.

5.  On the **Overview** tab, in the **Language code** field, select the identification code for a language.

6.  In the **Level** field, select **Elementary**, **Average**, or **Fluent** as the language proficiency level of the worker.

7.  Select the **Native language** check box to indicate that the language is the native language of the worker.

8.  On the **General** tab, in the **Level** field group, select the **Elementary**, **Average**, or **Fluent** check boxes for the speaking, reading, and writing language proficiency levels of the worker.

9.  Repeat steps 4 through 8 to add proficiency information for additional languages for the worker.

## If required: Enter the qualification improvement information for a worker

If a worker pursues a qualification improvement program, use the **Improvement of qualification** form to enter and maintain the qualification improvement information for the worker.

To perform this task, follow these steps:

1.  Click **Payroll (Russia)** \> **Common** \> **Employees**.

2.  Select a worker to enter the qualification improvement information for.

3.  On the **Action pane**, on the **Resume** tab, in the **Worker** group, click **Improvement of qualification** to open the **Improvement of qualification** form.

4.  Press CTRL+N to create a line.

5.  On the **Overview** tab, in the **Start date** field, specify the starting date for the qualification improvement program.

6.  If the worker has completed the qualification improvement program, in the **End date** field, specify the ending date for the program.

7.  In the **Type of improvement** field, enter a description for the type of improvement in the worker’s qualifications.

8.  In the **Educational institution** field, enter the name and address of the educational institution.

9.  If the worker has completed the program, specify values in the following fields on the **General** tab:
    
    1.  In the **Document date** and **Document** fields, specify the issuing date and number of the qualification improvement document.
    
    2.  In the **Resolution** field, enter a short description about the completion result, such as passed, passed with honors, or graduated with honors.

10. On the **Reason** tab, in the **Reason** field, enter the reason for the qualification improvement.

11. Repeat steps 4 through 10 to add additional qualification improvement information for a worker.

## If required: Enter the vocational retraining information for a worker

If a worker pursues retraining, use the **Vocational retraining** form to enter and maintain the vocational retraining information for the worker.

To perform this task, follow these steps:

1.  Click **Payroll (Russia)** \> **Common** \> **Employees**.

2.  Select a worker to enter the vocational retraining information for.

3.  On the **Action pane**, on the **Resume** tab, in the **Worker** group, click **Retraining** to open the **Vocational retraining** form.

4.  Press CTRL+N to create a line.

5.  On the **Overview** tab, in the **Start date** field, specify the starting date of the retraining.

6.  If the worker has completed the retraining, in the **End date** field, specify the ending date of the retraining.

7.  In the **Type of improvement** field, enter the description of how the worker was retrained.

8.  In the **Specialty** field, enter the name of the specialization for the retraining.

9.  If the worker has completed the retraining, specify values in the following fields on the **General** tab:
    
    1.  In the **Document date** field, specify the issuing date of the vocational training document.
    
    2.  In the **Document** field, enter the number of the vocational retraining document.
    
    3.  In the **Resolution** field, enter a short description about the completion result, such as passed, passed with honors, or graduated with honors.

10. On the **Reason** tab, in the **Reason** field, enter the reason for the vocational retraining.

## Enter the evaluation information for an employee

Use the **Evaluation** form to enter and maintain the results of an employee’s evaluation by the evaluation committee.

To perform this task, follow these steps:

1.  Click **Payroll (Russia)** \> **Common** \> **Employees**.

2.  Select an employee to enter evaluation information for.

3.  On the **Action pane**, on the **Resume** tab, in the **Employee** group, click **Evaluation** to open the **Evaluation** form.

4.  Press CTRL+N to create a line.

5.  On the **Overview** tab, in the **Evaluation date** field, specify the date of the evaluation meeting between the employee and the evaluation committee.

6.  In the **Evaluation result** field, select **Unsatisfactory**, **Satisfactory**, **Average**, or **Perfectly** as the result, depending on the employee evaluation by the evaluation committee.

7.  In the **Result** field, select the identification code for the evaluation result.

8.  On the **General** tab, in the **Document date** field, specify the issuing date of the evaluation document.

9.  In the **Document** field, enter the number of the evaluation document.

10. On the **Reason** tab, in the **Reason** field, enter the reason for the employee’s evaluation by the evaluation committee.

## If required: Enter disciplinary information for an employee

If disciplinary action is taken by the legal entity against an employee, use the **Punishments** form to enter and maintain the information about the disciplinary actions.

To perform this task, follow these steps:

1.  Click **Payroll (Russia)** \> **Common** \> **Employees**.

2.  Select an employee to enter the disciplinary information for.

3.  On the **Action pane**, on the **Resume** tab, in the **Employee** group, click **Punishments** to open the **Punishments** form.

4.  Press CTRL+N to create a line.

5.  On the **Overview** tab, in the **Date of punishment** field, specify the date when the disciplinary action is taken.

6.  In the **Violations** field, select the identification code for the type of violation.

7.  In the **Type of punishment** field, enter the description of the disciplinary measure that is taken against the employee.

8.  If a penalty amount is to be taken from the employee's wages, in the **Penalty** field, enter the penalty amount.

9.  On the **General** tab, in the **Document date** field, specify the issuing date of the disciplinary action document.

10. In the **Document** field, select the disciplinary action document number.

11. On the **Reason** tab, in the **Reason** field, enter the reason for the disciplinary actions that are taken against the employee.

## If required: Enter the privilege information for an employee

If benefits are given to an employee by the legal entity as an employer or by local state authorities, use the **Privileges** form to enter and maintain the information about employee benefits.

To perform this task, follow these steps:

1.  Click **Payroll (Russia)** \> **Common** \> **Employees**.

2.  Select an employee to enter the privilege information for.

3.  On the **Action pane**, on the **Resume** tab, in the **Employee** group, click **Privileges** to open the **Privileges** form.

4.  Press CTRL+N to create a line.

5.  On the **Overview** tab, in the **Privilege** field, select the identification code of the privilege that is given to the employee.

6.  In the **Document date** field, specify the issuing date of the document that indicates the details of the privilege.

7.  In the **Document** field, enter the number of the document that indicates the details of the privilege.

8.  On the **Reason** tab, in the **Reason** field, enter the reason for these additional employee benefits.

## Next step

After you record or update the competency information for a worker or employee, you can confirm the updated details by generating and printing the **Form T-2** report or the **Form T-4** report. For more information, see [(RUS) Staff administration reports](rus-staff-administration-reports.md).

## Related tasks

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

  


