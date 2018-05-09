---
title: Set up Accounts receivable workflows
TOCTitle: Set up Accounts receivable workflows
ms:assetid: d48a1492-47d1-4c69-a736-8e4dcf8529cc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213694(v=AX.60)
ms:contentKeyID: 36059521
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- workflows
- workflow
- approval
- approve
- free text
- journal
- journals
- free-text
---

# Set up Accounts receivable workflows 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Some organizations require that journals or free text invoices be approved by a user other than the person who entered the journal or invoice. To set up an approval process, you can create a workflow.

A workflow represents a business process. It defines how a document flows through the system and indicates who must complete a task or approve a document. There are several benefits of using the workflow system in your organization:

  - **Consistent processes** — You can define the approval process for specific documents, such as purchase requisitions and expense reports. Using the workflow system helps to ensure that documents are processed and approved in a consistent and efficient manner.

  - **Process visibility** — You can track the status, history, and performance metrics of a specific workflow instance. This helps you determine whether changes should be made to the workflow to improve efficiency.

  - **Centralized work list** — Users can view a centralized work list to view the workflow tasks and approvals assigned to them. This work list is available from the Role Center pages in the Microsoft Dynamics AX client and Enterprise Portal.

## Journal workflows

Based on journal names, you can require manual approval, workflow approval, or no approval. Use this information to set up one or more workflow configurations for each journal type, and then select a configuration for each journal name and activate workflow for that journal. If workflow approval is set up for a journal, additional controls are displayed at the top of the **Journal** form. These include a yellow information bar and a **Submit** button or an **Actions** menu. For more information, see [Submit a document](submit-a-document.md) and [Workflow actions](workflow-actions.md).

Some buttons in the **Journal** and **Journal voucher** forms are not available when a journal has been submitted for workflow journal approval. When the journal is approved, the options for the **Post** button are available, and the other controls and fields in the form are not. If a user edits an approved journal, the workflow status is reset, the options for the **Post** button are not available, and the other controls and fields are available. When the changes have been made, the journal must be resubmitted for approval.

The following options are available for payment journals that have a workflow status of **Approved**:

  - Edit the journal. When changes are complete, you must resubmit the journal for approval.

  - View the journal.

  - Process payments. Only the payment processing options are available.

You can use workflow approvals for the following journals and journal types in Accounts receivable.

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
<td><p><strong>Payment journal</strong></p></td>
<td><p><strong>Customer payment</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Draw bill of exchange journal</strong></p></td>
<td><p><strong>Customer draw bill of exchange</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Protest bill of exchange journal</strong></p></td>
<td><p><strong>Customer protest bill of exchange</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Redraw bill of exchange journal</strong></p></td>
<td><p><strong>Customer redraw bill of exchange</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Remittance journal</strong></p></td>
<td><p><strong>Customer bank remittance</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Settle bill of exchange journal</strong></p></td>
<td><p><strong>Customer settle bill of exchange</strong></p></td>
</tr>
</tbody>
</table>


For an overview of workflow in Microsoft Dynamics AX, see [Overview of the workflow system](overview-of-the-workflow-system.md) and [Workflow concepts](workflow-concepts.md). For information about how to set up journal approvals, see [Set up financial journal approvals](set-up-financial-journal-approvals.md).

## The types of workflows you can create

The following table lists the types of workflows that you can create in Accounts receivable.

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
<td><p><strong>Customer payment workflow</strong></p></td>
<td><p>Create approval workflows for customer payment journals.</p></td>
</tr>
<tr class="even">
<td><p><strong>Customer draw bill of exchange workflow</strong></p></td>
<td><p>Create approval workflows for customer draw bill of exchange journals.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Customer protest bill of exchange workflow</strong></p></td>
<td><p>Create approval workflows for customer protest bill of exchange journals.</p></td>
</tr>
<tr class="even">
<td><p><strong>Customer redraw bill of exchange workflow</strong></p></td>
<td><p>Create approval workflows for customer redraw bill of exchange journals.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Customer bank remittance workflow</strong></p></td>
<td><p>Create approval workflows for customer bank remittance journals.</p></td>
</tr>
<tr class="even">
<td><p><strong>Customer settle bill of exchange workflow</strong></p></td>
<td><p>Create approval workflows for customer settle bill of exchange journals.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Customer free text invoice workflow</strong></p></td>
<td><p>Create approval workflows for free text invoices.</p></td>
</tr>
<tr class="even">
<td><p><strong>Customer recurring invoice workflow</strong></p></td>
<td><p>Create approval workflows for recurring customer invoices.</p></td>
</tr>
</tbody>
</table>


## To create a workflow

Within each workflow, only the first approval node in the workflow will be used. To create a workflow, follow these steps.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable workflows**.

2.  On the **Action Pane**, click **New**.

3.  Select the type of workflow that you want to create, and then click **Create workflow**. The workflow editor is displayed. Design the workflow by dragging workflow elements onto the canvas.

4.  Configure each element of the workflow. For more information, see [Configure workflow elements](configure-workflow-elements.md).

5.  Repeat steps 2 through 4 to create additional workflows for Accounts receivable.

6.  If you are setting up journal workflows, set up journal approvals for specific journals using the **Journal names** form. For more information, see [Set up financial journal approvals](set-up-financial-journal-approvals.md).

## Calculated fields and expressions for workflow journal approvals

The following calculated fields and expressions are used with Accounts receivable workflow journal approvals. For each workflow, you can set up conditions that include these calculated fields and expressions.

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
<td><p><strong>Invoice total</strong></p></td>
<td><p>The total of all of the line amounts in the <strong>Free text invoice</strong> form.</p></td>
</tr>
<tr class="even">
<td><p><strong>Journal credit total</strong></p></td>
<td><p>The total credit amount for the whole journal.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Journal debit total</strong></p></td>
<td><p>The total debit amount for the whole journal.</p></td>
</tr>
<tr class="even">
<td><p><strong>Maximum voucher credit amount</strong></p></td>
<td><p>The highest credit voucher amount in the journal.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Maximum voucher debit amount</strong></p></td>
<td><p>The highest debit voucher amount in the journal.</p></td>
</tr>
<tr class="even">
<td><p><strong>Minimum voucher credit amount</strong></p></td>
<td><p>The lowest credit voucher amount in the journal.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Minimum voucher debit amount</strong></p></td>
<td><p>The lowest debit voucher amount in the journal.</p></td>
</tr>
</tbody>
</table>


## See also

[Journal names (form)](https://technet.microsoft.com/en-us/library/aa617509\(v=ax.60\))

[About free text invoice workflows](about-free-text-invoice-workflows.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

