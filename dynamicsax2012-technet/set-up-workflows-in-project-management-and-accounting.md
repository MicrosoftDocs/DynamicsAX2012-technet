---
title: Set up workflows in Project management and accounting
TOCTitle: Set up workflows in Project management and accounting
ms:assetid: 76435fe5-560c-4190-bab6-317471ddcc6c
ms:mtpsurl: https://technet.microsoft.com/library/Hh209244(v=AX.60)
ms:contentKeyID: 36058186
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up workflows in Project management and accounting 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In some organizations, project budgets or timesheets must be approved by a user other than the person who entered the budget or timesheet. To set up an approval process, you can create a *workflow*.

A workflow represents a business process. It defines how a document flows through the system and indicates who must complete a task or approve a document. There are several benefits of using the workflow system in your organization:

  - **Consistent processes** — You can define the approval process for specific documents, such as purchase requisitions and expense reports. Using the workflow system helps to ensure that documents are processed and approved in a consistent and efficient manner.

  - **Process visibility** — You can track the status, history, and performance metrics of a specific workflow instance. This helps you determine whether changes should be made to the workflow to improve efficiency.

  - **Centralized work list** — Users can view a centralized work list to view the workflow tasks and approvals assigned to them. This work list is available from the Role Center pages in the Microsoft Dynamics AX client and Enterprise Portal.

In Project management and accounting, you must be assigned as an approver to approve budgets, budget revisions, or timesheets.

## The types of workflows you can create

The following table lists the types of workflows you can create in Project management and accounting.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Type</p></th>
<th><p>Use this type to do this</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Review original budget workflow</strong></p></td>
<td><p>Create approval workflows for original project budgets.</p></td>
</tr>
<tr class="even">
<td><p><strong>Review budget revision workflow</strong></p></td>
<td><p>Create approval workflows for project budget revisions.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Review project invoice proposals</strong></p></td>
<td><p>Create approval workflows for project invoice proposals.</p></td>
</tr>
<tr class="even">
<td><p><strong>Review project quotations</strong></p></td>
<td><p>Create approval workflows for project quotations.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Review timesheet workflow</strong></p></td>
<td><p>Create approval workflows for project timesheets at the document level.</p></td>
</tr>
<tr class="even">
<td><p><strong>Review timesheet line workflow</strong></p></td>
<td><p>Create approval workflows for project timesheets at the line item level by adding line item workflow elements to a timesheet document workflow.</p></td>
</tr>
</tbody>
</table>


## Create a workflow

To create a workflow, follow these steps.

1.  Click **Project management and accounting** \> **Setup** \> **Project management and accounting workflows**.

2.  On the **Action Pane**, click **New**.

3.  Select the type of workflow to create, and then click **Create workflow**.

4.  In the workflow editor, design the workflow by dragging workflow elements onto the workflow canvas.

5.  Configure each element of the workflow. For more information, see [Configuring the workflow system](configuring-the-workflow-system.md).

6.  Repeat steps 2 through 5 to create additional workflows for Project management and accounting.

## Submitting a journal for processing

If workflow approval is set up for project budgets or timesheets, additional controls are displayed at the top of the **Project budget** or **New timesheet** form. These controls include a yellow information bar and, depending on the submittal status, a **Submit** or **Actions** button. For more information, see [Submit a document](submit-a-document.md) and [Workflow actions](workflow-actions.md).

## See also

[Get started with the workflow system](get-started-with-the-workflow-system.md)

[Configure the workflow system](configure-the-workflow-system.md)

[Design and configure workflows for Microsoft Dynamics AX](design-and-configure-workflows-for-microsoft-dynamics-ax.md)

[Monitor the status of workflows](monitor-the-status-of-workflows.md)

[Using workflows](using-workflows.md)

  


