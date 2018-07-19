---
title: About departments, jobs, and positions
TOCTitle: About departments, jobs, and positions
ms:assetid: 3d68cfa2-c80c-486e-ade9-251a3aaf8e74
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242239(v=AX.60)
ms:contentKeyID: 36056680
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- position
- department
- job
audience: Application User
ms.search.region: Global
---

# About departments, jobs, and positions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Departments, jobs, and positions are organizational elements that are maintained within Human resources. This topic contains conceptual information about these elements.

The following example is referenced multiple times in this topic.

**Example**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Department</p></th>
<th><p>Position</p></th>
<th><p>Job</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Sales</p></td>
<td><p>Sales manager (East)</p></td>
<td><p>Sales manager</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>Sales manager (West)</p></td>
<td><p>Sales manager</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>Sales manager (Central)</p></td>
<td><p>Sales manager</p></td>
</tr>
<tr class="even">
<td><p>Accounting</p></td>
<td><p>Accounting supervisor</p></td>
<td><p>Accounting manager</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>Accountant-A</p></td>
<td><p>Accountant</p></td>
</tr>
<tr class="even">
<td><p>Human resources</p></td>
<td><p>HR manager (East)</p></td>
<td><p>HR manager</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>HR manager (West)</p></td>
<td><p>HR manager</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>HR manager (Central)</p></td>
<td><p>HR manager</p></td>
</tr>
</tbody>
</table>


## Departments

A department is an operating unit that represents a category or functional area of an organization that is responsible for a specific area of the organization, such as sales or accounting. For more information about operating units, see [About organizations and organizational hierarchies](about-organizations-and-organizational-hierarchies.md).

A department is used to report on functional areas and may have profit and loss responsibility. Also, a department might include a group of cost centers. Sales, accounting, and human resources are some examples of departments in an organization.

## Jobs and positions

A job is a collection of tasks and responsibilities that are required of a person who performs a job. A position is an individual instance of a job. Areas of responsibility, job tasks, job functions, skills, education information, and certificates that are required for a job are also required for positions that are associated with a job.

## Job tasks

You can create job tasks that describe the basic tasks that a worker in a position for that job must complete. The same job task can be added to multiple jobs, and positions for those jobs will inherit those job tasks. For examples of job tasks, see the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Job</p></th>
<th><p>Job task</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Sales manager</p></td>
<td><ul>
<li><p>Perf-review – Review each salesperson’s job performance.</p></li>
<li><p>Abs-review – Approve or reject each salesperson’s absence requests or registrations.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Accountant</p></td>
<td><p>FIN-Report – Present weekly financial reports to chief financial officer.</p></td>
</tr>
</tbody>
</table>


## Job functions

Job functions are like job tasks. A job function describes one or more tasks, duties or responsibilities that are assigned to a job. Job functions can be assigned to jobs and used to set up and implement eligibility rules for compensation plans. For more information, see [Key tasks: Compensation plans](key-tasks-compensation-plans.md). For examples of job functions, see the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Job</p></th>
<th><p>Job function</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Sales manager</p></td>
<td><p>Mng-people – Manage people who report to you.</p></td>
</tr>
<tr class="even">
<td><p>Accountant</p></td>
<td><p>FIN-Review – Maintain financial data for a set of accounts.</p></td>
</tr>
</tbody>
</table>


## Job types

Use job types to classify similar jobs into categories. Job types, just like job functions, can be assigned to jobs and used to set up and implement eligibility rules for compensation plans. For more information, see [Key tasks: Compensation plans](key-tasks-compensation-plans.md). Some examples of job types are included in the following list:

  - Full-time

  - Part-time

  - Salary

  - Hourly pay

## Areas of responsibility

Use areas of responsibility to indicate the work roles, processes, and products that a worker in a position for that job would be responsible for. An example of an area of responsibility for a job titled “Accountant” might be “Financial reporting for Product A”.

## Positions

Positions are an important element of the lower level of an organization hierarchy. A position is an individual instance of a job. For example, the position, “Sales manager (East),” is just one of the positions that is associated with the job, “Sales manager.” Positions exist in a department and are assigned to workers.

## Position creation and maintenance

If your organization requires a formal process to create positions and modify positions, you can turn on the [Personnel actions configuration key (HcmPersonnelActions)](personnel-actions-configuration-key-hcmpersonnelactions.md). If this key is selected, the following options are available:

  - You can view a history of position-related system changes in an easy-to-access list page.

  - You can create reason codes that your users can select when they create or modify positions.

  - You can create personnel action types and assign a number sequence to personnel actions.

  - You can set up workflow so that position additions and changes can require approval.

## Position duration

Every position has a length of time that the position is effective. This length of time is referred to as duration. For example, summer positions might have duration of May 1, 2012 until August 31, 2012.

## Worker assignments

When you assign a worker to a position, you fill that position. You can assign workers to multiple positions, but only one worker can be assigned to a position at the same time. For more information, see [About workers](about-workers.md).

## Reporting relationships

Positions are important elements of the lower level of an organization hierarchy. In the **Position** form, you can specify the position that a position reports to. When you assign a worker to a position that reports to another position, you create a reporting relationship between the workers who are assigned to the two positions. For example, position “Accountant-A” reports to position “Accounting Supervisor”. Kim Akers is assigned to position “Accounting Supervisor” and Sanjay Patel is assigned to position “Accountant-A”. This means that Sanjay Patel reports to Kim Akers.

If your organization uses a matrix hierarchy or another custom hierarchy, you can set up position hierarchy types and then add reporting relationships to positions for each hierarchy type that you set up. For example, Lori Penor is a general manager at Adventure Works and is assigned to the “General Manager” position. Lori manages the development of a product that is used to clean widgets. Lori requires an accountant to help her with the finances for developing the product. Therefore, she has recruited Sanjay Patel to be her accountant. Sanjay reports directly to Kim Akers, but also works with Lori Penor on his work related to the finances for developing the widget cleaner.

For the previous example, you would complete the following tasks to set up the working relationship between Sanjay Patel and Lori Penor:

1.  Create a custom position hierarchy type called “Widget” to create a hierarchy that includes positions responsible for working on the widget cleaner product.

2.  Assign the General Manager position to be the position that the Accountant-A position reports to in the Widget hierarchy.

Use the position hierarchy to view the reporting structure of positions. If you have multiple position hierarchies, you can view the hierarchy for each hierarchy type in the position hierarchy. Also, you can search for a position by position ID or by the name of the worker who is assigned to the position. The position hierarchy is an organizational hierarchy. For more information about organizational hierarchies, see [About organizations and organizational hierarchies](about-organizations-and-organizational-hierarchies.md).

## Payroll

If your organization is using the Payroll module, enter payroll-related information for each position.


> [!NOTE]
> <P>This control is available only if Payroll for Microsoft Dynamics AX 2012 is installed.</P>



## Labor union

Enter labor union agreement information and the legal entity that holds the contract for the position.


> [!NOTE]
> <P>This control is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed.</P>



## Financial dimensions

Enter financial dimensions and budgeting information for budget forecasting.


> [!NOTE]
> <P>This control is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed.</P>



## Date effective records

For some records, you can specify future changes to the record. The following information is date effective.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Records</p></th>
<th><p>Date effective information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Jobs</p></td>
<td><ul>
<li><p>Some detailed job information</p></li>
<li><p>Job classification information</p></li>
<li><p>Compensation information</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Positions</p></td>
<td><ul>
<li><p>Some detailed position information</p></li>
<li><p>Worker assignments</p></li>
<li><p>Position durations</p></li>
<li><p>Position hierarchies</p></li>
</ul></td>
</tr>
</tbody>
</table>


You can modify the information mentioned in the previous table for a position or a job and specify a date when the modifications to the position or job should take effect. For example, a position can only be assigned to one worker, but Sanjay Patel, who is assigned to the position Accountant-A, will be leaving in two weeks. Joe Healy will replace Sanjay Patel when he leaves. Even though Sanjay is still assigned to his position, you can assign Joe Healy to the same position so that the assignment is effective only after Sanjay’s last day. For more information about date effective records, see [Maintain records](maintain-records.md).

## See also

[Key tasks: Departments](key-tasks-departments.md)

[Key tasks: Jobs](key-tasks-jobs.md)

[Key tasks: New worker positions](key-tasks-new-worker-positions.md)

[Operating units (form)](https://technet.microsoft.com/en-us/library/hh208817\(v=ax.60\))

[Job (form)](https://technet.microsoft.com/en-us/library/hh209557\(v=ax.60\))

[Positions (form)](https://technet.microsoft.com/en-us/library/aa590982\(v=ax.60\))

[Position hierarchy types (form)](https://technet.microsoft.com/en-us/library/hh242466\(v=ax.60\))

  


