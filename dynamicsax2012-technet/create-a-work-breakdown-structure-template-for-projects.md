---
title: Create a work breakdown structure template for projects
TOCTitle: Create a work breakdown structure template for projects
ms:assetid: 769c21ef-9958-43c4-8724-5007d1cd6776
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn528661(v=AX.60)
ms:contentKeyID: 59636746
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a work breakdown structure template for projects 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to create a template for a work breakdown structure (WBS) in Microsoft Dynamics AX. A WBS is a list of tasks that a project manager plans to complete for a project. If some tasks are the same for multiple projects, you can create a WBS template that contains those tasks. Use a WBS template as a starting point for a WBS for a project.

You can create a WBS template for projects that are frequently used. For example, an IT consulting business creates software for its customers. The company’s projects usually require five tasks: planning, design, testing, installation, and maintenance. Therefore, the project manager creates a WBS template and adds the five tasks to it. When a new IT project is started, the project manager creates a WBS for the IT project from the template, and then adds other tasks, workers, start dates, end dates, and other details to the WBS.

After you create a WBS from a WBS template, you can add or delete tasks, and modify the sequence of tasks in the WBS to meet the requirement of the project. You can also modify the effort and duration of tasks in the project’s WBS.

Create a WBS template by using any of the following procedures:

  - Create a WBS template from a blank WBS template form.

  - Save an existing WBS template as a new WBS template.

  - Save the WBS from a specific project as a WBS template.


> [!NOTE]
> <P>In Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2 you can use Microsoft Project to create a template for a WBS that you can use in Microsoft Dynamics AX. For more information, see <A href="create-or-update-a-project-by-using-microsoft-project.md">Create or update a project by using Microsoft Project</A>.</P>



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
<td><p>Related configuration tasks</p></td>
<td><p>Set up calendars for work periods that are used in projects. For more information, see <a href="create-working-time-calendars.md">Create working time calendars</a>.</p>
<p>Select a work calendar that is used by default for new projects. For more information, see <a href="set-up-parameters-for-a-timesheet-system.md">Set up parameters for a timesheet system</a>.</p>
<p>Set up project categories. For more information, see <a href="create-categories-and-category-groups-for-projects.md">Create categories and category groups for projects</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Create a WBS template from a blank WBS template form

To create a WBS template from a blank form, follow these steps.

1.  Click **Project management and accounting** \> **Setup** \> **Projects** \> **Work breakdown structure templates**. On the **Action Pane**, click **New work breakdown structure template**.

2.  In the **New WBS Template** form, enter a unique name for the WBS template. Optionally, enter a description for the WBS template.

3.  The **Active** check box is automatically selected. To make the WBS template unavailable for projects, clear the check box.
    
    When the WBS template is ready to use, you can change its status. To change the status, open the WBS template, and then on the **Line details** FastTab, select the **Active** check box.

4.  In the **New WBS Template** form, click **OK**.

5.  In the **Work breakdown structure template for %1 - %2** form, notice that the first row contains the name of the WBS template, the sum of effort in hours for all tasks, and the total duration of all tasks. These fields cannot be modified directly. Instead, the effort and duration in the first row are updated when you modify the effort and duration of the tasks.

6.  To add a task, on the **Action Pane**, click **Task**. Enter task information in the following fields.
    
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
    <td><p><strong>Predecessors</strong></p></td>
    <td><p>Enter the number of a task that must be completed before the current task can be started. A task can have multiple precedent tasks.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Category</strong></p></td>
    <td><p>Enter a project category. The category is used to define revenue and cost for the task. For more information about project categories and category groups, see <a href="about-project-category-groups.md">About project category groups</a>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Effort (hours)</strong></p></td>
    <td><p>Enter the estimated total number of hours that are required to complete the task. The number of hours might represent multiple workers for the task. The estimated total includes any hours that vendor workers might post.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Number of resources</strong></p></td>
    <td><p>Enter the number of workers that are required to complete the task. These workers include vendor workers.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Duration (days)</strong></p></td>
    <td><p>Enter the estimated number of work days that are required to complete the task. If you enter a start date and end date, the duration is automatically calculated.</p>
    <p></p></td>
    </tr>
    </tbody>
    </table>


7.  To modify the position of a task in the WBS template, use the following buttons on the **Action Pane**.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Button</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Outdent</strong></p></td>
    <td><p>Move a task up one level. The task is automatically renumbered for the new position. For example, in a WBS template that has three parent tasks and one child task, you outdent child task 2.1. The outdented task becomes task 3, and the former task 3 becomes task 4.</p>
    <p>You can select multiple tasks to outdent. When you click <strong>Outdent</strong>, the tasks that you select are elevated by one level from their former level.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Indent</strong></p></td>
    <td><p>Move a task down one level. The indented task becomes a child of the parent task above it. For example, when you indent task 2, it becomes a child of task 1 and is automatically changed to task 1.1. If there are other child tasks of task 1, the indented task is listed last under the parent task.</p>
    <p>You can select multiple tasks to indent. When you click <strong>Indent</strong>, the tasks that you select are moved down by one level from their former level.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Move task up</strong></p></td>
    <td><p>Move a task to a position that is one row up from its current position. Use this process to define the sequence of child tasks for a parent task, and to modify the sequence of parent tasks in the WBS structure. When you move a parent task, all its child tasks are moved together with it.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Move task down</strong></p></td>
    <td><p>Move a task to a position that is one row down from its current position. Use this process to define the sequence of child tasks for a parent task, and to modify the sequence of parent tasks in the WBS structure. When you move a parent task, all its child tasks are moved together with it.</p></td>
    </tr>
    </tbody>
    </table>


8.  To delete a task, select the task, and then, on the **Action Pane**, click **Delete**.

## 2\. Save an existing WBS template as a new WBS template

You can create a WBS template from another WBS template and then modify the copied template.

To create a new WBS template from an existing template, follow these steps.

1.  Click **Project management and accounting** \> **Setup** \> **Projects** \> **Work breakdown structure templates**. On the **Work breakdown structure templates** list page, open the WBS template to copy. In the **Work breakdown structure template for %1 - %2** form, on the **Action Pane**, on the **WBS ID** tab, click **Export WBS as a template**.

2.  In the **Save as** form, enter a unique name for the WBS template. Optionally, enter a description for the WBS template.

3.  Click **OK**. You receive a message that states that the copy process is completed.

4.  Refresh the **Work breakdown structure templates** list page to view the new WBS template.

## 3\. Save the WBS from a specific project as a WBS template

A project manager might want to use a project’s WBS as the starting point for a WBS template. For example, a new type of project is offered, and the tasks to complete the new project type are not fully known at the start of the project. During the project, the WBS for the project is updated as tasks are added and modified. When the project is completed, the project manager saves the WBS from the new project type as a WBS template. Then, when another customer requests a project of the same type, the project manager can use the WBS template to create a WBS for the project.

To save the WBS for a specific project as a WBS template, follow these steps.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Select a project. On the **Action Pane**, on the **Plan** tab, in the **Activities** group, click **Work breakdown structure**.

2.  In the **Work breakdown structure for %1 - %2** form, on the **Action Pane**, on the **WBS ID** tab, click **Export WBS as a template**.

3.  In the **Save as** form, enter a unique name for the WBS template. Optionally, enter a description for the WBS template.

4.  Click **OK**. You receive a message that states that the copy process is completed.

## Next step

[Create a work breakdown structure of tasks for a project](create-a-work-breakdown-structure-of-tasks-for-a-project.md)

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
<td><p>To create a WBS template, you must be a member of a security role that includes the <strong>Maintain project activity master</strong> (ProjActivityMasterMaintain) duty.</p></td>
</tr>
</tbody>
</table>


## See also

[About work breakdown structures](about-work-breakdown-structures.md)

  


