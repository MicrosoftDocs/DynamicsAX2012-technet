---
title: Workflow with a line-item workflow element
TOCTitle: Workflow with a line-item workflow element
ms:assetid: d2542818-0fbf-49b0-9ca0-fc34919e6d72
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh538461(v=AX.60)
ms:contentKeyID: 39508890
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Workflow with a line-item workflow element [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You may want documents, and all the line items on those documents, to be processed by the workflow system. In this scenario, you must complete the following tasks:

1.  Create the workflows that are used to process the line items.

2.  Create the workflow that is used to process the whole document.

For example, suppose that you want timesheets, and the line items on those timesheets, to be processed by the workflow system. This topic provides examples of the workflows that you would create to support this scenario.

## The workflows that are used to process the line items

For this example, assume that each line item on a timesheet contains a project ID, and that the employees in your organization work on the projects that are listed in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Project ID</p></th>
<th><p>Project manager</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1111</p></td>
<td><p>Mary</p></td>
</tr>
<tr class="even">
<td><p>2222</p></td>
<td><p>Hans</p></td>
</tr>
<tr class="odd">
<td><p>3333</p></td>
<td><p>Jen</p></td>
</tr>
</tbody>
</table>


Now suppose that you want each line item to be approved by the appropriate project manager. In this scenario, you would create line-item workflows that resemble the workflows in the following figure.

![Line-item workflows](images/Hh538461.Workflow_LineItemWorkflows(AX.60).gif "Line-item workflows")

## The workflow that is used to process the whole document

After you create line-item workflows, you can create the workflow that processes the whole document. This workflow must contain the line-item workflow element, which runs the line-item workflows. For example, the following figure shows a workflow that contains a line-item workflow element.

![Workflow with a line-item workflow element](images/Hh538461.Workflow_WithLineItemElement(AX.60).gif "Workflow with a line-item workflow element")

To understand how a document moves through this workflow, assume that Mike has submitted a timesheet that has 42 hours on it. The line-item workflow element is run, and it, in turn, runs the line-item workflows. In this scenario, the following events occur:

  - The lines items for project 1111 are sent to Mary for approval.

  - The line items for project 2222 are sent to Hans for approval.

  - The line items for project 3333 are sent to Jen for approval.

When all the line items have been approved by the appropriate managers, the timesheet is assigned to Dianne, the vice president, for approval. After Dianne approves the timesheet, the workflow ends.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

