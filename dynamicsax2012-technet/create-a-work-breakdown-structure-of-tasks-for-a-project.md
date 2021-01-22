---
title: Create a work breakdown structure of tasks for a project
TOCTitle: Create a work breakdown structure of tasks for a project
ms:assetid: 0edfa121-3126-4dbd-84fa-81e096df838b
ms:mtpsurl: https://technet.microsoft.com/library/Dn528660(v=AX.60)
ms:contentKeyID: 59636744
author: Khairunj
ms.author: daxcpft
ms.date: 06/09/2014
mtps_version: v=AX.60
f1_keywords:
- Project
- project activities
- work breakdown structure
- WBS
audience: Application User
ms.search.region: Global
---

# Create a work breakdown structure of tasks for a project 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

A project often consists of multiple activities, or tasks. A work breakdown structure (WBS) is a hierarchical representation of the tasks for a project. This topic explains how to create a WBS, add tasks to it, and add requirements and other information for each task. It also provides information about working with revenue and costs in a WBS, working with estimated and actual hours for tasks in a WBS, and working with a WBS in Microsoft Project.

You can enter the following information for tasks in a WBS:

  - The sequence of tasks in a hierarchy

  - Other tasks, if any, that must be completed before a task can be started

  - The starting date, ending date, and duration of a task

  - The number of hours required for a task

  - Any required worker skills and education

  - The workers who are assigned to a task

  - Estimated revenue and costs

You can create a WBS manually or import tasks from another WBS or a WBS template.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX prior to cumulative update 7 for Microsoft Dynamics AX 2012 R2. If you are using an earlier version of Microsoft Dynamics AX 2012, see <A href="https://technet.microsoft.com/library/hh209089(v=ax.60)">Work breakdown structure (form)</A>.</P>



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
<td><p>Related configuration tasks</p></td>
<td><ul>
<li><p>Set up calendars for work periods that are used in projects. For more information, see <a href="create-working-time-calendars.md">Create working time calendars</a>. If you have not assigned a work calendar to the related project, a message is displayed in the WBS form.</p></li>
<li><p>Select a work calendar that is used by default for new projects. For more information, see <a href="set-up-parameters-for-a-timesheet-system.md">Set up parameters for a timesheet system</a>.</p></li>
<li><p>Set up project categories. For more information, see <a href="create-categories-and-category-groups-for-projects.md">Create categories and category groups for projects</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Manually create a WBS for a project

You can create a WBS for a specific project by starting with a blank WBS form.

To create a WBS for a project, follow these steps:

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Open the project that you want to create a WBS for. On the **Action Pane**, on the **Plan** tab, in the **Activities** group, click **Work breakdown structure**.
    
    In the **Work breakdown structure** form, the first row in the grid contains the name of the project and a sum of the values that you enter for tasks. You can’t modify these fields directly.

2.  To add a task, on the **Action Pane**, click **Task**, and then enter information about the task. The following table shows the information to enter in each field.
    
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
    <td><p><strong>Task name</strong></p></td>
    <td><p>Enter a name for the task.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Predecessors</strong></p></td>
    <td><p>Enter the identification number of the tasks that must be completed before the current task can be started. A task can have multiple predecessors.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Category</strong></p></td>
    <td><p>By default, the category is automatically copied from the default category for hours in the <strong>Project management and accounting parameters</strong> form. You can modify the category for a task.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Effort (hours)</strong></p></td>
    <td><p>Enter the estimated total number of hours that are required to complete the task. The number of hours can represent multiple workers for the task, and can also include any hours that vendor workers might post to the project.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Number of resources</strong></p></td>
    <td><p>Enter the number of workers that are required to complete the task, including vendor workers.</p>
    <p>If you enter the duration and effort in hours for a task, the number of worker resources is automatically calculated.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Start</strong></p></td>
    <td><p>Enter the estimated starting date for a task.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Finish</strong></p></td>
    <td><p>Enter the estimated ending date for a task. If you enter a starting date and the duration in days for a task, the ending date is automatically added.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Duration (days)</strong></p></td>
    <td><p>Enter the estimated number of work days that are required to complete the task. If you enter a start date and end date, the duration is automatically calculated.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Workers</strong></p></td>
    <td><p>Select one or more workers to schedule for the task.</p>
    <p>You can choose from a list of workers whose time is already book for the project by selecting the check boxes by their names, or you can click <strong>View more workers</strong> to open the <strong>Worker assignment</strong> form. In the <strong>Worker assignment</strong> form you can select other workers to assign to the task and add to the project team.</p>
    <p>For information about how to select additional workers for the task and project team, and about how Microsoft Dynamics AX distributes time among workers in certain situation, see Assign workers to tasks manually in a work breakdown structure.</p></td>
    </tr>
    </tbody>
    </table>


3.  To add a task at a level under another task, select the task, and then on the **Action Pane**, click **Task**. Complete the information in the fields for the new task. For information about how to modify the structure of tasks in a WBS, see “Organize tasks in a WBS,” later in this topic.

## Import tasks into a WBS

You can import tasks from a WBS for one project into the WBS for another project. You can also import tasks from a WBS template into the WBS for a specific project. For information about how to create a WBS template, see [Create a work breakdown structure template for projects](create-a-work-breakdown-structure-template-for-projects.md).


> [!IMPORTANT]
> <P>When you import tasks from another project’s WBS or from a WBS template, all of the tasks are imported. After you import tasks, you can delete any tasks that are not applicable to the current project.</P>



To import tasks into a WBS, follow these steps:

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Open a project to create a WBS for. On the **Action Pane**, on the **Plan** tab, in the **Activities** group, click **Work breakdown structure**.

2.  In the **Work breakdown structure** form, select the task under which to import tasks. The imported tasks are added to the selected task as subtasks. After you import the tasks, you can move them as appropriate for the current project and WBS.

3.  On the **Action Pane**, on the **WBS** tab, click **Import template under selected task**.

4.  In the **Copy from** form, you can specify whether to import tasks from a WBS for another project or from a WBS template. By default, only WBS templates are listed in the **Name** field. To select from a list of projects, clear the **Show only templates** check box.

5.  In the **Name** field, select the name of the WBS or WBS template that contains the tasks to import, and then click **OK**.

## Organize tasks in a WBS

As work on a project progresses, you can modify the sequence of tasks, modify the predecessor tasks, and change the level for a task. For example, you might import tasks from another project, and then decide that an imported subtask is a major first step in the current project. You can elevate the subtask to a higher level in the hierarchy to make it a task, move it up in the sequence of tasks, and then modify the predecessors for it.

To organize tasks in a WBS, follow these steps:

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Open a project. On the **Action Pane**, on the **Plan** tab, in the **Activities** group, click **Work breakdown structure**.

2.  Reorganize the tasks in the WBS as required. The following table shows what actions you can take to modify the WBS.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Action</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Move a task to a position earlier in the WBS</p></td>
    <td><p>Select the task, and then, on the <strong>Action Pane</strong>, click <strong>Move task up</strong>.</p>
    <p>When you move a task, any subtasks move with it. The tasks in the WBS are automatically renumbered when a task is moved.</p></td>
    </tr>
    <tr class="even">
    <td><p>Move a task to a position later in the WBS</p></td>
    <td><p>Select the task, and then, on the <strong>Action Pane</strong>, click <strong>Move task down</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p>Elevate a subtask to a higher level in the hierarchy of tasks</p></td>
    <td><p>Select the task, and then, on the <strong>Action Pane</strong>, click <strong>Outdent</strong>.</p>
    <p>The elevated task is automatically renumbered for the new position. For example, in a WBS template that has three parent tasks and one subtask, you elevate subtask 2.1. The elevated task becomes task 3, and the former task 3 becomes task 4.</p>
    <p>You can select multiple tasks to outdent. When you click <strong>Outdent</strong>, the tasks that you select are elevated by one level from their former level.</p></td>
    </tr>
    <tr class="even">
    <td><p>Move a task down a level in the WBS</p></td>
    <td><p>Select the task, and then, on the <strong>Action Pane</strong>, click <strong>Indent</strong>.</p>
    <p>The task becomes a subtask of the preceding task. For example, a WBS has two tasks. When you indent task 2, it becomes a subtask of task 1 and is automatically renumbered. If task 1 has no other subtasks, the new subtask is renumbered 1.1. If task 1 has other subtasks, the new subtask is added after the other subtasks and is renumbered accordingly.</p>
    <p>You can select multiple tasks to indent. When you click <strong>Indent</strong>, the tasks that you select are moved down by one level from their former level.</p></td>
    </tr>
    <tr class="odd">
    <td><p>Delete a task</p></td>
    <td><p>Select the task, and then, on the <strong>Action Pane</strong>, click <strong>Delete</strong>.</p>
    <p>When you delete a task that has subtasks, all its subtasks are also deleted. Also, the deleted task is removed as a predecessor from any tasks that were dependent on it.</p>
    <p>If you want to delete a parent task but don’t want to delete one or more of its subtasks, before you delete the parent task, do either of the following:</p>
    <ul>
    <li><p>Elevate the subtasks to the same level as the parent task.</p></li>
    <li><p>Move the subtasks to another parent task.</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


## Find and resolve scheduling conflicts in a WBS

When you enter dates and hours for tasks, the information that you enter might result in scheduling conflicts. You can manually change the effort, dates, and duration for tasks to resolve scheduling conflicts or you can let the system automatically identify and resolve them. By default, the system is set to identify and correct scheduling conflicts as you enter information for tasks.

To use the automatic scheduling assistance for a WBS, follow these steps:

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Open a project. On the **Action Pane**, on the **Plan** tab, in the **Activities** group, click **Work breakdown structure**.

2.  In the **Work breakdown structure** form, verify that the automatic scheduling assistance is turned on. If automatic scheduling assistance is turned on, the **Automatic scheduling assistance is on** button is displayed on the **Action Pane**.

3.  If automatic scheduling assistance is not turned on, click **Automatic scheduling assistance is off**. The name of the button changes to **Automatic scheduling assistance is on**.

4.  To correct scheduling issues that existed before you turned on automatic scheduling, on the **Action Pane**, click **Fix all scheduling discrepancies**.

To disable automatic scheduling assistance and manually resolve scheduling conflicts, follow these steps:

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Open a project. On the **Action Pane**, on the **Plan** tab, in the **Activities** group, click **Work breakdown structure**.

2.  In the **Work breakdown structure** form, on the **Action Pane**, click **Automatic scheduling assistance is on**. When you click this button, the name of the button changes to **Automatic scheduling assistance is off**.

3.  Modify the values in the **Effort (hours)**, **Number of resources**, **Start**, **Finish**, and **Duration (days)** fields as applicable.

## Work with estimated and actual revenue and costs in a WBS

When you select a project category for a task, and the sales price and cost per hour are specified for the project category, the price and cost amounts are automatically added to the WBS for the task. In the cost tracking view of a WBS, you can view a comparison between planned, estimated, and actual revenue and costs for a task.

To compare planned, estimated, and actual revenue and costs for a task, follow these steps:

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Open a project. On the **Action Pane**, on the **Plan** tab, in the **Activities** group, click **Work breakdown structure**.

2.  On the **Task** tab, in the **View** section, click **Cost tracking view**.

3.  Review the status of revenue and costs for each task. The following table shows the information that is displayed in the fields in this view.
    
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
    <td><p><strong>% Cost consumed</strong></p></td>
    <td><p>The percentage of posted cost divided by the estimated total cost of the task. The total estimated cost is displayed in the <strong>Estimate at complete</strong> field.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Actual cost</strong></p></td>
    <td><p>The total cost of hours that are posted to date for a task.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Cost to complete</strong></p></td>
    <td><p>The remaining cost of hours to complete a task. The value is automatically calculated as Estimate at complete – Actual cost.</p>
    <p>You can modify the value in this field. When you do, the value in the <strong>Estimate at complete</strong> field is also updated.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Estimate at complete</strong></p></td>
    <td><p>The estimated total cost when this task is complete, calculated as Actual cost to date + Cost to complete.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Planned cost</strong></p></td>
    <td><p>The estimated total cost for a task.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Projected cost variance</strong></p></td>
    <td><p>The estimated cost variance for the task, calculated as Estimate at complete - Planned cost. A negative value indicates that the estimated cost exceeds the budgeted total cost.</p></td>
    </tr>
    </tbody>
    </table>
    
    In the field at the right of the values, a checkmark indicates that the total projected variance is positive or zero. A warning symbol indicates that the projected variance is negative, and that the cost of hours for a task is expected to exceed the budgeted cost for the task.

## Work with estimated and actual hours for tasks in a WBS

In the WBS form, you can enter the estimated number of hours that are required to complete a task. When you enter estimated hours for tasks, the values are automatically added to fields in the effort tracking view of the WBS.

To compare planned, estimated, and actual hours posted for a task, follow these steps:

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Open a project. On the **Action Pane**, on the **Plan** tab, in the **Activities** group, click **Work breakdown structure**.

2.  On the **Task** tab, in the **View** section, click **Effort tracking view**.

3.  Review the status of hours for tasks. The following table shows the information that is displayed in the fields in this view.
    
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
    <td><p><strong>Progress percent</strong></p></td>
    <td><p>The percentage of actual hours divided by the estimated number of remaining hours to complete the task. The estimated hours are displayed in the <strong>Effort at complete</strong> field.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Actual effort (hours)</strong></p></td>
    <td><p>The total number of hours in transactions that are posted to date for a task.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Remaining effort (hours)</strong></p></td>
    <td><p>The estimated number of remaining hours that are required to complete a task. The value is automatically calculated as Effort at complete – Actual effort.</p>
    <p>You can modify the value in this field. When you do, the number of hours in the <strong>Effort at complete</strong> field is also modified.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Effort at complete</strong></p></td>
    <td><p>The estimated total hours of this task when it is completed, calculated as Actual hours to date + Remaining effort.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Planned effort</strong></p></td>
    <td><p>The estimated total hours for a task.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Projected effort variance</strong></p></td>
    <td><p>The estimated variance for the task, calculated as Effort at complete - Planned effort. A negative value indicates that the estimated hours exceed the budgeted total hours.</p></td>
    </tr>
    </tbody>
    </table>
    
    In the field at the right of the values, a checkmark indicates that the total projected variance is positive or zero. A warning symbol indicates that the projected variance is negative, and that the number of hours for a task is expected to exceed the budgeted hours for the task.

## Work with a WBS in Microsoft Project

You can create a link between a project in Microsoft Dynamics AX and a corresponding project in Microsoft Project. You can then use Microsoft Project to create or update the WBS of your project, and also create a WBS template that you can use in Microsoft Dynamics AX.

You can also use Microsoft Project to replace the work breakdown structure of a project that is maintained in Microsoft Dynamics AX. For more information, see [Create or update a project by using Microsoft Project](create-or-update-a-project-by-using-microsoft-project.md).

To update a WBS for a project that is integrated with Microsoft Project, follow these steps:

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Open a project. On the **Action Pane**, on the **Plan** tab, in the **Activities** group, click **Work breakdown structure**.

2.  In the **Work breakdown structure** form, on the **Action Pane**, on the **WBS** tab, click **Open in Microsoft Project**.

3.  Modify the WBS as needed. When you close the WBS, the changes are also saved to Microsoft Project.


> [!NOTE]
> <P>You can remove the link between a project in Microsoft Dynamics AX and Microsoft Project and work on the project’s WBS only in Microsoft Dynamics AX. To remove the link, in the <STRONG>Work breakdown structure</STRONG>, on the <STRONG>Action Pane</STRONG>, on the <STRONG>WBS</STRONG> tab, click <STRONG>Unlink from Microsoft Project</STRONG>.</P>



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
<td><p>No configuration key is required for this task.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>To create a WBS, you must be a member of a security role that includes the <strong>Maintain project activity master</strong> (ProjActivityMasterMaintain) duty.</p></td>
</tr>
</tbody>
</table>


## See also

[About work breakdown structures](about-work-breakdown-structures.md)

[Create a work breakdown structure template for projects](create-a-work-breakdown-structure-template-for-projects.md)

[Transfer work breakdown estimates to project forecasts](transfer-work-breakdown-estimates-to-project-forecasts.md)

  


