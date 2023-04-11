---
title: Set up workflows for travel and expense
TOCTitle: Set up workflows for travel and expense
ms:assetid: 2c7f5d0c-d2f9-4538-8fc3-e21f1a767363
ms:mtpsurl: https://technet.microsoft.com/library/Hh580596(v=AX.60)
ms:contentKeyID: 39519082
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- expenses
- expense
- travel
audience: Application User
ms.search.region: Global
---

# Set up workflows for travel and expense 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up a workflow process that is used to review and approve travel and expense documents. The documents for which workflows can be defined include expense reports, travel requisitions, credit card disputes, and cash advance requests.

A workflow represents a business process. It defines how a document flows through the system and indicates who must complete a task or approve a document. There are several benefits of using the workflow system in your organization:

  - **Consistent processes** — You can define the approval process for specific documents, such as purchase requisitions and expense reports. Using the workflow system helps to ensure that documents are processed and approved in a consistent and efficient manner.

  - **Process visibility** — You can track the status, history, and performance metrics of a specific workflow instance. This helps you determine whether changes should be made to the workflow to improve efficiency.

  - **Centralized work list** — Users can view a centralized work list to view the workflow tasks and approvals assigned to them. This work list is available from the Role Center pages in the Microsoft Dynamics AX client and Enterprise Portal.

## The types of workflows you can create

The following table lists the types of workflows that you can create in **Travel and expense**.

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
<td><p><strong>Expense report</strong></p></td>
<td><p>Create approval workflows for expense reports.</p></td>
</tr>
<tr class="even">
<td><p><strong>Expense report auto posting</strong></p></td>
<td><p>Create automatic posting workflows for expense reports.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Expense line item</strong></p></td>
<td><p>Create approval workflows for line items on expense reports.</p></td>
</tr>
<tr class="even">
<td><p><strong>Expense line item auto posting</strong></p></td>
<td><p>Create automatic posting workflows for line items on expense reports.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Travel requisition</strong></p></td>
<td><p>Create approval workflows for travel requisitions.</p></td>
</tr>
<tr class="even">
<td><p><strong>Cash advance request</strong></p></td>
<td><p>Create approval workflows for cash advance requests.</p></td>
</tr>
<tr class="odd">
<td><p><strong>VAT tax recovery</strong></p></td>
<td><p>Create approval workflows for the recovery of value-added tax (VAT).</p></td>
</tr>
<tr class="even">
<td><p><strong>Dispute management</strong></p></td>
<td><p>Create workflows for the management of credit card disputes.</p></td>
</tr>
</tbody>
</table>


## To create a workflow

1.  Click **Travel and expense** \> **Setup** \> **Travel and expense workflows**.

2.  On the **Action Pane**, click **New**.

3.  Select the type of workflow to create, and then click **Create workflow**.

4.  In the workflow editor, design the workflow by dragging workflow elements onto the canvas.

5.  Configure each element of the workflow. For more information, see [Configuring the workflow system](configuring-the-workflow-system.md).

6.  Repeat steps 2 through 5 to create additional workflows for **Travel and expense**.

## Working with workflows

For more information about workflows in Microsoft Dynamics AX, see the following topics:

  - [Overview of the workflow system](overview-of-the-workflow-system.md)

  - [Workflow examples](workflow-examples.md)

  - [Configure workflows](configure-workflows.md)

  


