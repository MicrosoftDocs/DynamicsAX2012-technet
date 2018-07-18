---
title: Set up Fixed assets workflows
TOCTitle: Set up Fixed assets workflows
ms:assetid: f8d27156-2fa5-4c3b-851e-f74fbd4af240
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh227561(v=AX.60)
ms:contentKeyID: 36060051
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up Fixed assets workflows 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Some organizations require that journals be approved by a user other than the person who entered the journal. To set up an approval process, you can create a workflow.

A workflow represents a business process. It defines how a document flows through the system and indicates who must complete a task or approve a document. There are several benefits of using the workflow system in your organization:

  - **Consistent processes** — You can define the approval process for specific documents, such as purchase requisitions and expense reports. Using the workflow system helps to ensure that documents are processed and approved in a consistent and efficient manner.

  - **Process visibility** — You can track the status, history, and performance metrics of a specific workflow instance. This helps you determine whether changes should be made to the workflow to improve efficiency.

  - **Centralized work list** — Users can view a centralized work list to view the workflow tasks and approvals assigned to them. This work list is available from the Role Center pages in the Microsoft Dynamics AX client and Enterprise Portal.

## Journal workflows

Based on journal names, you can require manual approval, workflow approval, or no approval. Use this information to set up one or more workflow configurations for each journal type, and then select a configuration for each journal name and activate workflow for that journal. If workflow approval is set up for a journal, additional controls are displayed at the top of the **Journal** form. These include a yellow information bar and a **Submit** button or an **Actions** menu. For more information, see [Submit a document](submit-a-document.md) and [Workflow actions](workflow-actions.md).

Some buttons in the **Journal** and **Journal voucher** forms are not available when a journal has been submitted for workflow journal approval. When the journal is approved, the options in the **Post** menu are available, and the other controls and fields in the form are not. If a user edits an approved journal, the workflow status is reset, the options in the **Post** menu are not available, and the other controls and fields are available. When the changes have been made, the journal must be resubmitted for approval.

You can use workflow approvals for the following journals and journal types in Fixed assets.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Journal menu item</p></th>
<th><p>Journal type</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Fixed assets</strong></p></td>
<td><p><strong>Post fixed assets</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Fixed asset budget</strong></p></td>
<td><p><strong>Fixed asset budget</strong></p></td>
</tr>
</tbody>
</table>


For an overview of workflow in Microsoft Dynamics AX, see [Overview of the workflow system](overview-of-the-workflow-system.md) and [Workflow concepts](workflow-concepts.md). For information about how to set up journal approvals, see [Set up financial journal approvals](set-up-financial-journal-approvals.md).

## The types of workflows you can create

The following table lists the types of workflows that you can create in Fixed assets.

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
<td><p><strong>Ledger post fixed assets journal workflow</strong></p></td>
<td><p>Create approval workflows for fixed asset journals.</p></td>
</tr>
<tr class="even">
<td><p><strong>Ledger fixed assets budget journal workflow</strong></p></td>
<td><p>Create approval workflows for fixed asset budget journals.</p></td>
</tr>
</tbody>
</table>


## To create a workflow

To create a workflow, follow these steps.

1.  Click **Fixed assets** \> **Setup** \> **Fixed assets workflows**.

2.  On the **Action Pane**, click **New**.

3.  Select the type of workflow that you want to create, and then click **Create workflow**. The workflow editor is displayed. Design the workflow by dragging workflow elements onto the canvas.

4.  Configure each element of the workflow. For more information, see [Configure workflow elements](configure-workflow-elements.md).

5.  Repeat steps 2 through 4 to create additional workflows for Fixed assets.

6.  Set up journal approvals for specific journals using the **Journal names** form. For more information, see [Set up financial journal approvals](set-up-financial-journal-approvals.md).

## Calculated fields and expressions

The following calculated fields and expressions are used with Fixed assets workflow journal approvals. For each configuration, you can set up conditions that include these calculated fields and expressions. For more information, see [Test workflow condition (form)](https://technet.microsoft.com/en-us/library/hh597214\(v=ax.60\)).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Calculated field</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Journal credit total</strong></p></td>
<td><p>The total credit amount for the whole journal.</p></td>
</tr>
<tr class="even">
<td><p><strong>Journal debit total</strong></p></td>
<td><p>The total debit amount for the whole journal.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Maximum voucher credit amount</strong></p></td>
<td><p>The highest credit voucher amount in the journal.</p></td>
</tr>
<tr class="even">
<td><p><strong>Maximum voucher debit amount</strong></p></td>
<td><p>The highest debit voucher amount in the journal.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Minimum voucher credit amount</strong></p></td>
<td><p>The lowest credit voucher amount in the journal.</p></td>
</tr>
<tr class="even">
<td><p><strong>Minimum voucher debit amount</strong></p></td>
<td><p>The lowest debit voucher amount in the journal.</p></td>
</tr>
</tbody>
</table>


## See also

[Journal names (form)](https://technet.microsoft.com/en-us/library/aa617509\(v=ax.60\))

[Journal names setup (form)](https://technet.microsoft.com/en-us/library/aa552517\(v=ax.60\))

  


