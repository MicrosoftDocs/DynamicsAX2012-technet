---
title: Set up System administration workflows
TOCTitle: Set up System administration workflows
ms:assetid: 70323721-966b-42e5-99c3-c14463482fd5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242645(v=AX.60)
ms:contentKeyID: 36058054
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up System administration workflows 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

As part of the system administration setup, you can create workflows to manage user provisioning for user requests, and to inactivate users following an inactivate user request.

A workflow represents a business process. It defines how a document flows through the system and indicates who must complete a task or approve a document. There are several benefits of using the workflow system in your organization:

  - **Consistent processes** — You can define the approval process for specific documents, such as purchase requisitions and expense reports. Using the workflow system helps to ensure that documents are processed and approved in a consistent and efficient manner.

  - **Process visibility** — You can track the status, history, and performance metrics of a specific workflow instance. This helps you determine whether changes should be made to the workflow to improve efficiency.

  - **Centralized work list** — Users can view a centralized work list to view the workflow tasks and approvals assigned to them. This work list is available from the Role Center pages in the Microsoft Dynamics AX client and Enterprise Portal.

For an overview of workflow in Microsoft Dynamics AX, see [Overview of the workflow system](overview-of-the-workflow-system.md) and [Workflow concepts](workflow-concepts.md). For information about how to set up workflows, see [Configuring the workflow system](configuring-the-workflow-system.md).

## The types of workflows you can create

The following workflow types are available for System administration.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Type</p></th>
<th><p>Use this type to</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>User request workflow</strong></p></td>
<td><p>Create user provisioning workflows for user requests.</p></td>
</tr>
<tr class="even">
<td><p><strong>Inactivate user request workflow</strong></p></td>
<td><p>Create user inactivation workflows for inactivate user requests.</p></td>
</tr>
</tbody>
</table>


## To create a workflow

1.  Click **System administration** \> **Setup** \> **Workflow** \> **User workflows**.

2.  On the **Action Pane**, click **New**.

3.  Select the type of workflow that you want to create, and then click **Create workflow**.

4.  In the workflow editor, design the workflow by dragging workflow elements onto the canvas.

5.  Configure each element in the workflow. For more information, see [Configuring the workflow system](configuring-the-workflow-system.md).

6.  Repeat steps 2 through 5 to create additional workflows for System administration.

## Types of participants

You can assign an approval step to the following groups of participants.

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
<td><p><strong>Participant</strong></p></td>
<td><p>Assign the approval step to members of a group or role.</p></td>
</tr>
<tr class="even">
<td><p><strong>Hierarchy</strong></p></td>
<td><p>Assign the approval step to users in a specific organizational hierarchy.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Workflow user</strong></p></td>
<td><p>Assign the approval step to users of this workflow.</p></td>
</tr>
<tr class="even">
<td><p><strong>User</strong></p></td>
<td><p>Assign the approval step to specific Microsoft Dynamics AX users.</p></td>
</tr>
</tbody>
</table>

  


