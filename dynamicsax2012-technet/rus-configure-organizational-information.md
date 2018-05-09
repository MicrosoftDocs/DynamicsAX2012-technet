---
title: (RUS) Configure organizational information
TOCTitle: (RUS) Configure organizational information
ms:assetid: d07f0628-c9fe-4689-ae01-8945a767352f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn452010(v=AX.60)
ms:contentKeyID: 56713183
ms.date: 07/02/2014
mtps_version: v=AX.60
f1_keywords:
- position
- department
- organization
- branch
- Forms.OMLegalEntity
- tax registration
- legal entity
- Forms.Branches_RU
- Forms.RHRMOrderTable
- Forms.RHRMOrderTrans
- Forms.RpayHrmOrganization
- insurance fund
- d07f0628-c9fe-4689-ae01-8945a767352f
---

# (RUS) Configure organizational information 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to create tax registration numbers, social insurance information, and the organizational structure for a legal entity and its branches. You can create departments in an organization, assign each department to a branch, and reserve a position for a department.

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
<th><p>Prerequisites</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Version</p></td>
<td><p>Microsoft Dynamics AX 2012 R2 Payroll for Russia Feature Pack</p></td>
</tr>
<tr class="even">
<td><p>Country/region</p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Russia</p></td>
</tr>
<tr class="odd">
<td><p>Configuration task</p></td>
<td><p>A legal entity must be created for the processes that are related to Russian payroll using the <strong>Legal entities</strong> form in the <strong>Organization administration</strong> module. For more information, see <a href="create-or-modify-a-legal-entity.md">Create or modify a legal entity</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Create tax registration numbers and insurance fund information for a legal entity

You can create the tax registration details and insurance fund details for a legal entity. Legal entities are required to register in insurance funds. If the hired employee is eligible for social allowances and pension provision, then the employer becomes an insurant, and the employer must contribute to the social and pension insurance funds. These insurance identification numbers are considered to be legal entity registration codes for the local subsidiaries of insurers.

To create social insurance details, pension fund numbers, and registration numbers for the legal entity, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Legal entities**.

2.  On the **Additional registration** FastTab, in the **Registration code in FSS** field, enter the registration code for the federal social insurance fund.

3.  In the **Territorial authority of the insurer** field, select the code for the territorial authority of the insurer, or the local subsidiary of the social insurance fund.

4.  In the **Code of subordination** field, enter the subordination code of the local subsidiary of the social insurance fund.

5.  In the **Registration pension fund number** field, enter the registration pension fund number.

6.  To open the **Manage addresses** form, click **Taxes**.

7.  To add the tax registration information for the legal entity, on the **Tax registration** FastTab, click **Add**.

8.  In the **Registration type** field, select the tax registration type that is specified by the tax authorities. The following registration types are available:
    
      - OGRN - The unique code for the legal entity in the Russian federation.
    
      - OKDP – The special code that is assigned to the company based on the business.
    
      - INN ORG – The unique identification code for the individual taxpayer.
    
      - KPP - The code that is provided by the tax authority during the registration.
    
      - OKPO - The code that is assigned to the legal entity from the list of Russian professional organizations.

9.  In the **Registration number** field, enter the registration number for the legal entity that is specified by the tax authorities.

10. In the **Organizational-legal form** field, enter the legal entity’s type of incorporation.

## 2\. Create a branch

You can create a branch to identify groups of departments as individual taxpayers. These branches that you create can also be used by the **Fixed assets** module for functions that are separate from the payroll process. You can create or update a branch in the **Separate divisions** form.

To create a branch, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Separate divisions**.

2.  Click **New** to create a new branch.

3.  In the **Separate division ID** field, enter the identification code for the branch.

4.  In the **Vendor account** field, select the vendor account that is associated with the branch.
    

    > [!NOTE]
    > <P>The name of the vendor is automatically displayed in the <STRONG>Name</STRONG> field.</P>



5.  To indicate that the selected branch can report the tax declarations independently, select the **Independent** check box.

## 3\. Create a department and assign it to a branch

You can create departments in an organization, assign a director, and assign a person in charge for the department in the **Organization** form.

To create a department and assign it to a branch, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Structure** \> **Organization**.
    
    –or–

2.  Click **Payroll (Russia)** \> **Setup** \> **Department** \> **Organization**.

3.  Press CTRL+N to create a new department in the organizational structure.

4.  On the **Overview** tab, in the **Department code** field, enter a code for the department.

5.  In the **Description** field, enter a description for the department.

6.  In the **Person in charge** field, select the code for the employee who is responsible for the department. The employees who are already part of this department are available for selection.

7.  On the **General** FastTab, in the **Director** field, select the code of the employee who leads the department. The registered workers of the company are available for selection.

8.  To assign the department to a branch, on the **Branch** FastTab, click **New**.

9.  In the **Start date** field, enter the date when the department is assigned to the branch.

10. In the **Separate division ID** field, select the code of the branch.

To detach a department from a branch, follow these steps:

1.  On the **Branch** FastTab, click **New**, and then in the **Start date** field, enter the date when the department’s assignment to the branch should be completed.

2.  Leave the **Separate division ID** field blank. The department is detached from the branch, and it becomes a part of the legal entity’s head office.

## 4\. Reserve a position for a department

You can reserve a position for a department in the **Organizational chart** form. The head count for the reserved position must be approved by the Human Resources administrator in the **Changing staff list resolution lines** form so that an employee can be hired for the approved position.

To reserve a position for a department, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Structure** \> **Organizational chart**.

2.  To reserve a position for a department, in the left pane, select the department, and then click **New**.

3.  On the **Overview** tab, in the **Position** field, select an employee position for the selected department. For more information about job titles and positions, see "Create job titles, ranks, categories, and classes" in [(RUS) Configure staff administration information for workers](rus-configure-staff-administration-information-for-workers.md).

4.  Click **Payroll (Russia)** \> **Staff administration** \> **Resolution journals** \> **Changing staff list**.

5.  Click **New** to create a new record.

6.  In the **Name** and **Resolution date** fields, select the journal name and the date of issue of the resolution.

7.  Click **Lines** to open the **Changing staff list resolution lines** form, and specify the following field details.
    
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
    <td><p><strong>Department code</strong></p></td>
    <td><p>Select the department code.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The position is displayed automatically for the selected department.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Quantity</strong></p></td>
    <td><p>The number of establishing positions.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Minimum salary</strong></p></td>
    <td><p>The minimum salary for the position.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Maximum salary</strong></p></td>
    <td><p>The maximum salary for the position.</p>
    <div class="alert">

    > [!NOTE]
    > <P>On the <STRONG>General</STRONG> tab, in the <STRONG>Scale of charges</STRONG> field group, you can select the minimum and maximum wage grade codes for the approved pay scale that is selected in the <STRONG>Code</STRONG> field. The values in the <STRONG>Minimum salary</STRONG> and <STRONG>Maximum salary</STRONG> fields are automatically updated according to the selected wage grades.</P>


    </div></td>
    </tr>
    </tbody>
    </table>


8.  On the **General** tab, in the **Work conditions** field group, specify the conditions that need to be met for employees who work on specific positions (class of hazard, necessity of the attestation, and special conditions of work). For example, a work condition for a welder may be the dustiness. Use the information in the following table to decide the type of work condition information to be displayed in the report.
    
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
    <td><p><strong>Class</strong></p></td>
    <td><p>Select the class of the working condition (normal, harmful, and hazard).</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Attestation</strong></p></td>
    <td><p>Select this check box to indicate that the work place requires attestation confirming the working conditions of the position.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Special work conditions</strong></p></td>
    <td><p>Select the code for the special work condition. The codes are defined in the <strong>Special work conditions</strong> form.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>List position</strong></p></td>
    <td><p>The code for the list position that indicates the level of the harmfulness of the conditions.</p></td>
    </tr>
    </tbody>
    </table>


9.  Click **Validate** to validate the resolution lines, and then click **OK** in the **Check journal** form.

10. Click **Post** to post the journal, and then click **OK** in the **Post journal** form.
    

    > [!NOTE]
    > <P>The <STRONG>Posted</STRONG> check box is automatically selected in the <STRONG>Changing staff list</STRONG> form to indicate that the position that is reserved for the department is approved by the Human Resources administrator.</P>



11. Click **Restore** to cancel the posted journal, if needed.

To view the reserved position for a department, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Structure** \> **Organizational chart**.

2.  In the left pane, select the department for which the position was reserved. You can view the approved headcount for the position in the **Quantity** field.

3.  To view the actual and planned head count for the selected department, click **Total** to open the **Department total** form.

You can generate a special report to view the organizational positions on a particular date, and view the selected resolution journal.

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Reports** \> **Form T-3**.

2.  In the **Journal** field, select the journal for which you need to generate the report.

3.  In the **Current date** field, select the date on which you need to print the details about the organizational positions.

You can generate a report about the changes that you made to the staff list as an official document that is provided by the Human Resources department for the introduction of the new positions in the **Changing staff list** form.

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Resolution journals** \> **Changing staff list**.

2.  To generate a report about the changes that you made to the staff list, click **Print**, and then click **Changing staff list**.

## Next step

[(RUS) Create a worker](rus-create-a-worker.md)

## Related tasks

[(RUS) Configure staff administration information for workers](rus-configure-staff-administration-information-for-workers.md)

[(RUS) Configure parameters for time management](rus-configure-parameters-for-time-management.md)

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
<td><p>To perform this task, you must have the following roles:</p>
<ul>
<li><p><strong>Human resources administrator</strong></p></li>
<li><p><strong>Human resources manager</strong></p></li>
</ul>
<p>To configure organizational information, you must be a member of a security role that includes the following duties:</p>
<ul>
<li><p><strong>Enable workforce management process</strong> (HcmWorkforceProcessEnable)</p></li>
<li><p><strong>Enable organizational process</strong> (HcmOrganizationalProcessEnable)</p></li>
<li><p><strong>Enable time management process</strong> (RPayTimeManageProcessEnable)</p></li>
<li><p><strong>Inquire into organizational model</strong> (OMOrganizationsInquire)</p></li>
<li><p><strong>Inquire into organizational process</strong> (HcmOrganizationalProcessInquire)</p></li>
<li><p><strong>Inquire into time management process</strong> (RPayTimeProcessInquire)</p></li>
<li><p><strong>Maintain and configure organizational model</strong> (OMOrganizationsMaintain)</p></li>
<li><p><strong>Maintain job and position master</strong> (HcmJobPositionMaintain)</p></li>
<li><p><strong>Set up payroll positions and workers</strong> (PayrollPositionWorkerSetupMaintain)</p></li>
<li><p><strong>Inquire into jobs and positions</strong> (HcmJobPositionInquire)</p></li>
<li><p><strong>Inquire into payroll position and worker setup</strong> (PayrollPositionWorkerSetupInquire)</p></li>
<li><p><strong>Review organizational information</strong> (HcmOrganizationalReview)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To configure organizational information, you must be a member of a security role that includes the privileges that are described in the following table.</p>
<div class="caption">
</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Privileges</p></th>
<th><p>Name</p></th>
<th><p>Procedure</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Maintain departments</strong></p></td>
<td><p>OMDepartmentMaintain</p></td>
<td><p>Create a department and assign it to a branch.</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain department rates values</strong></p></td>
<td><p>RPayDepRatesMaintain</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>View department rates values</strong></p></td>
<td><p>RPayDepRatesView</p></td>
<td></td>
</tr>
<tr class="even">
<td><p><strong>View departments</strong></p></td>
<td><p>OMDepartmentView</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>Maintain organizational chart</strong></p></td>
<td><p>RPayOrgChartMaintain</p></td>
<td><p>Reserve a position for a department.</p></td>
</tr>
<tr class="even">
<td><p><strong>View organizational chart</strong></p></td>
<td><p>RPayOrgChartView</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>Maintain positions</strong></p></td>
<td><p>HcmPositionMaintain</p></td>
<td></td>
</tr>
<tr class="even">
<td><p><strong>View positions</strong></p></td>
<td><p>HcmPositionView</p></td>
<td></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

