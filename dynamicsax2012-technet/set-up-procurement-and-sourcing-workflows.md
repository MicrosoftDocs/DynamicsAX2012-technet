---
title: Set up Procurement and sourcing workflows
TOCTitle: Set up Procurement and sourcing workflows
ms:assetid: e8a8595c-859a-4549-93a1-015f3086d0b2
ms:mtpsurl: https://technet.microsoft.com/library/Hh227472(v=AX.60)
ms:contentKeyID: 36059837
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- workflows
- workflow
- procurement
- sourcing
- purchasing
- procurement and sourcing
audience: Application User
ms.search.region: Global
---

# Set up Procurement and sourcing workflows 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Some organizations require that vendor requests, purchase requisitions, and unconfirmed product receipts be approved by a user other than the person who entered the transaction. To set up an approval process, you can create a workflow.

A workflow represents a business process. It defines how a document flows through the system and indicates who must complete a task or approve a document. There are several benefits of using the workflow system in your organization:

  - **Consistent processes** — You can define the approval process for specific documents, such as purchase requisitions and expense reports. Using the workflow system helps to ensure that documents are processed and approved in a consistent and efficient manner.

  - **Process visibility** — You can track the status, history, and performance metrics of a specific workflow instance. This helps you determine whether changes should be made to the workflow to improve efficiency.

  - **Centralized work list** — Users can view a centralized work list to view the workflow tasks and approvals assigned to them. This work list is available from the Role Center pages in the Microsoft Dynamics AX client and Enterprise Portal.

For an overview of workflow in Microsoft Dynamics AX, see [Overview of the workflow system](overview-of-the-workflow-system.md) and [Workflow concepts](workflow-concepts.md). For information about how to set up workflows, see [Configuring the workflow system](configuring-the-workflow-system.md).

## The types of workflows that you can create

The following workflow types are available for Procurement and sourcing.

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
<td><p><strong>Catalog import product approval</strong></p></td>
<td><p>Create review workflows for imported catalog products.</p></td>
</tr>
<tr class="even">
<td><p><strong>Catalog import approval</strong></p></td>
<td><p>Create review workflows for imported catalogs.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Delivery due date notification workflow</strong></p></td>
<td><p>Create delivery due-date notification workflows for unconfirmed product receipts.</p></td>
</tr>
<tr class="even">
<td><p><strong>Invoice received notification workflow</strong></p></td>
<td><p>Create invoice-received notification workflows for unconfirmed product receipts.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Product receipt failed notification workflow</strong></p></td>
<td><p>Create notification workflows for failed product receipts.</p></td>
</tr>
<tr class="even">
<td><p><strong>Unconfirmed product receipt rejection notification workflow</strong></p></td>
<td><p>Create notification workflows for rejected unconfirmed product receipts.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Purchase order line workflow</strong></p></td>
<td><p>Create review and approve workflows for purchase order lines.</p></td>
</tr>
<tr class="even">
<td><p><strong>Purchase requisition line review</strong></p></td>
<td><p>Create review workflows for purchase requisition lines.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Purchase requisition review</strong></p></td>
<td><p>Create review workflows for purchase requisitions.</p></td>
</tr>
<tr class="even">
<td><p><strong>Purchase order workflow</strong></p></td>
<td><p>Create review and approval workflows for purchase orders.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Vendor category application workflow</strong></p></td>
<td><p>Create approval workflows for vendor category application requests.</p></td>
</tr>
<tr class="even">
<td><p><strong>Vendor category justification workflow</strong></p></td>
<td><p>Create approval workflows for vendor category justification requests.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Vendor add application workflow</strong></p></td>
<td><p>Create approval workflows for vendor-add application requests.</p></td>
</tr>
<tr class="even">
<td><p><strong>Vendor status change request workflow</strong></p></td>
<td><p>Create approval workflows for vendor status change requests.</p></td>
</tr>
</tbody>
</table>


## To create a workflow

1.  Click **Procurement and sourcing** \> **Setup** \> **Procurement and sourcing workflows**.

2.  On the **Action Pane**, click **New**.

3.  Select the type of workflow that you want to create, and then click **Create workflow**.

4.  In the workflow editor, design the workflow by dragging workflow elements onto the canvas.

5.  Configure each element of the workflow. For more information, see [Configuring the workflow system](configuring-the-workflow-system.md).

6.  Repeat steps 2 through 5 to create additional workflows for Procurement and sourcing.

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
<td><p><strong>Queue</strong></p></td>
<td><p>Assign the approval step to a work item queue.</p></td>
</tr>
<tr class="odd">
<td><p><strong>User</strong></p></td>
<td><p>Assign the approval step to specific Microsoft Dynamics AX users.</p></td>
</tr>
</tbody>
</table>

  


