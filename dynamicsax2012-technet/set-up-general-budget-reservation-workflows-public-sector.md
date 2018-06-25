---
title: Set up general budget reservation workflows (Public sector)
TOCTitle: Set up general budget reservation workflows (Public sector)
ms:assetid: 39e61fe2-1143-43f4-94f8-0d21ba778190
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn906410(v=AX.60)
ms:contentKeyID: 65205494
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- workflows
- workflow
- public sector
- budget reservation
- budget reservations
- general budget reservation
- general budget reservations
- budget reservation workflow
- general budget reservation workflow
---

# Set up general budget reservation workflows (Public sector) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up one or more workflow configurations for general budget reservations. When workflow approval is set up for general budget reservations, additional controls appear at the top of the general budget reservation list and form. These include a yellow information bar, and either a **Submit** button or an **Actions** menu. For more information, see [Workflow actions](workflow-actions.md).


> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>



When a general budget reservation is approved through workflow, it remains editable. The options in the **Post** group on the **Action Pane** are available, but the other controls and fields in the form are not. Note that if you edit an approved reservation, its workflow status is reset to **Draft**, and the options in the **Post** group are not available, but the other controls and fields are available. You must resubmit the changed reservation for approval.

The following illustration shows how to set up a general budget reservation workflow. The numbers correspond to the procedures later in this topic.

![General budget reservation workflow setup](images/Dn906410.SetUpGBRWorkflow(AX.60).jpg "General budget reservation workflow setup")

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
<td><p>Microsoft Dynamics AX 2012 R3 Cumulative Update 8, with Procurement and Sourcing and the following hotfix: KB3047235</p>
<p><a href="set-up-general-budget-reservation-rules-and-reservation-types-public-sector.md">Set up general budget reservation rules and reservation types (Public sector)</a></p></td>
</tr>
</tbody>
</table>


## 1\. Optional: Set up reviewers for general budget reservations

You can set up reviewer workflow elements to route general budget reservations for review. The workflow process uses the specified owner of the project role or financial dimension to determine whom to route the expenditure to.

Alternatively, you can simply assign a specific user or user group as a reviewer when you define the workflow. However, if you have a complex organization, you can improve the efficiency of the approval process by specifying reviewer elements, and you won’t have to change the workflow reviewer assignments every time that a reviewer changes job roles.

For more information, see [Workflow actions](workflow-actions.md).

## 2\. Create a workflow for general budget reservations

General budget reservation workflows are based on reservation type. You can therefore create multiple workflows for general budget reservations.


> [!NOTE]
> <P>If the general budget reservation requires a purchase requisition, note that purchase requisitions require their own workflow. The workflow for the purchase requisition must be completed before the general budget reservation can reference it. For more information about creating a purchase requisition workflow, see <A href="overview-of-a-purchase-requisition-workflow.md">Overview of a purchase requisition workflow</A>.</P>



To create a workflow for general budget reservations, use the following steps.

1.  Click **Budgeting \> Setup \> Budgeting workflows**.

2.  In the **Budgeting workflows** list, on the **Action Pane**, click **New**.

3.  In the **Create workflow** form, click the **General budget reservation workflow** template, and then click **Create workflow**.

4.  In the workflow form, under **Approvals** in the **Workflow elements** list, click **Approve general budget reservation**, and then drag it under the **Start** icon.

5.  Drag the border of the **Start** icon to create a connecting line to the approval element.

6.  Click the approval element, and then, on the **Action Pane**, click **Basic settings** to configure the element. For more information, see [Configure an approval process](configure-an-approval-process.md).

## 3\. Optional: Configure manual and automated tasks for general budget reservation workflows

Complete this step to reflect the approval or review tasks that are part of your business practice:

  - A manual review of a general budget reservation

  - An automated process to evaluate field values for general budget reservation

You can use a combination of these tasks in the same workflow. The difference between a review manual task and an approval workflow element is as follows:

  - If the manual review task is assigned to multiple users, the workflow can continue after any one of those users completes the task.

  - If you assign an approval workflow element to multiple users, you can specify whether all those users must approve the document before the workflow can continue.

When defining the steps for the review in the description section of the workflow, you assign the task to a user who is authorized to review the lines that are in the general budget reservation. For more information, see Step 5, “Assign participants to workflow elements.”

For instructions on how to configure manual tasks, see [Configure a manual task](configure-a-manual-task.md).

## 4\. Optional: Create conditional decisions

Complete this step if your business processes require different workflow processes depending on the amount of the general budget reservation. You can also create decisions based accounting date, reservation type, reservation title, start or end date, and other criteria.

For instructions on how to create conditions, see [Configure a conditional decision](configure-a-conditional-decision.md).

## 5\. Assign participants to workflow elements

You can associate a workflow element with the following groups of participants.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>User group</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Security role participants</p></td>
<td><p>Assign the workflow element to a Microsoft Dynamics AX security role. You might use this option if a group of workers can approve general budget reservations and it doesn’t matter which person approves a particular document.</p></td>
</tr>
<tr class="even">
<td><p>User group participants</p></td>
<td><p>Assign the workflow element to a Microsoft Dynamics AX user group. You might use this option if a group of workers can approve general budget reservations and anyone in that group can approve a particular document.</p></td>
</tr>
</tbody>
</table>


You can also have the workflow element assigned based on a hierarchy or user. For instructions on how to assign participants to a workflow, see the “Assign the task” section in [Configure a manual task](configure-a-manual-task.md). See also [Workflow with multiple users in a task](workflow-with-multiple-users-in-a-task.md).

## 6\. Save the workflow

When you have finished adding elements, use the following steps to check it for errors and then save it.


> [!NOTE]
> <P>The <STRONG>Errors and warnings</STRONG> pane, located at the bottom of the workflow editor, displays messages that are generated for the workflow. To locate the element where an error or warning occurs, double-click the error or warning message. All errors and warnings must be resolved before you can make the workflow active.</P>



1.  When the workflow is completed and error-free, click **Save and close**. Click **OK** in the **Save workflow - {0}** dialog box.

2.  If you want to activate the workflow now, click **OK** in the **Activate workflow - {0}** dialog box.
    
    –or–
    
    If you want to activate the workflow later, do the following at any time:
    
    1.  Go to **Budgeting \> Setup \> Budgeting workflows**.
    
    2.  Select the workflow you created.
    
    3.  On the **Action Pane**, in the **Manage** group, click **Versions**.
    
    4.  Select the version of the workflow that you want.
    
    5.  On the Action strip, click **Make active**, and then click **OK**.

## Related tasks

[Submit a general budget reservation to workflow (Public sector)](submit-a-general-budget-reservation-to-workflow-public-sector.md)

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
<td><p><strong>Public Sector</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>Budget manager</p></td>
</tr>
</tbody>
</table>


## See also

[Set up Budgeting workflows](set-up-budgeting-workflows.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

