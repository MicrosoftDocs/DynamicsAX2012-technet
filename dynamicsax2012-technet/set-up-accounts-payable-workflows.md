---
title: Set up Accounts payable workflows
TOCTitle: Set up Accounts payable workflows
ms:assetid: 5fbf73a4-d3ec-433a-943d-c7529fd5d782
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg242526(v=AX.60)
ms:contentKeyID: 36057598
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- workflows
- workflow
- approval
- approve
- accounts
- AP
- payable
- journal
- journals
audience: Application User
ms.search.region: Global
---

# Set up Accounts payable workflows 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Some organizations require that journals be approved by a user other than the person who entered the journal. To set up an approval process, you can create a workflow. You can also set up other processes, such as the review of vendor invoices.

A workflow represents a business process. It defines how a document flows through the system and indicates who must complete a task or approve a document. There are several benefits of using the workflow system in your organization:

  - **Consistent processes** — You can define the approval process for specific documents, such as purchase requisitions and expense reports. Using the workflow system helps to ensure that documents are processed and approved in a consistent and efficient manner.

  - **Process visibility** — You can track the status, history, and performance metrics of a specific workflow instance. This helps you determine whether changes should be made to the workflow to improve efficiency.

  - **Centralized work list** — Users can view a centralized work list to view the workflow tasks and approvals assigned to them. This work list is available from the Role Center pages in the Microsoft Dynamics AX client and Enterprise Portal.

## Journal workflows

Based on journal names, you can require manual approval, workflow approval, or no approval. Use this information to set up one or more workflow configurations for each journal type. Then select a configuration for each journal name, and activate workflow for that journal. If workflow approval is set up for a journal, additional controls are displayed at the top of the **Journal** form. These include a yellow information bar, and either a **Submit** button or an **Actions** menu. For more information, see [Submit a document](submit-a-document.md) and [Workflow actions](workflow-actions.md).

Some buttons in the **Journal** and **Journal voucher** forms are not available when a journal has been submitted for workflow journal approval. When the journal is approved, the options on the **Post** menu are available, and the other controls and fields in the form are not. If a user edits an approved journal, the workflow status is reset, the options on the **Post** menu are not available, and the other controls and fields are available. When the changes have been made, the journal must be resubmitted for approval.

The following options are available for payment journals that have a workflow status of **Approved**:

  - Edit the journal. When changes are completed, you must resubmit the journal for approval.

  - View the journal.

  - Process payments. Only the payment processing options are available.

You can use workflow approvals for the following journals and journal types in Accounts payable.

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
<td><p><strong>Invoice register</strong></p></td>
<td><p><strong>Invoice register</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Invoice approval journal</strong></p></td>
<td><p><strong>Approval</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Invoice journal</strong></p></td>
<td><p><strong>Vendor invoice recording</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Payment journal</strong></p></td>
<td><p><strong>Vendor disbursement</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Draw promissory note journal</strong></p></td>
<td><p><strong>Vendor draw promissory note</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Redraw promissory note journal</strong></p></td>
<td><p><strong>Vendor redraw promissory note</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Remittance journal</strong></p></td>
<td><p><strong>Vendor bank remittance</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Settle promissory note journal</strong></p></td>
<td><p><strong>Vendor settle promissory note</strong></p></td>
</tr>
</tbody>
</table>


For an overview of workflow in Microsoft Dynamics AX, see [Overview of the workflow system](overview-of-the-workflow-system.md) and [Workflow concepts](workflow-concepts.md). For information about how to set up journal approvals, see [Set up financial journal approvals](set-up-financial-journal-approvals.md).

## The types of workflows you can create

The following table lists the types of workflows that you can create in Accounts payable.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Type</p></th>
<th><p>Purpose</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Vendor invoice register journal workflow</strong></p></td>
<td><p>Create approval workflows for invoice register journals.</p></td>
</tr>
<tr class="even">
<td><p><strong>Vendor invoice approval journal workflow</strong></p></td>
<td><p>Create approval workflows for invoice approval journals.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Purchase agreement approval</strong></p></td>
<td><p>Create approval workflows for purchase agreements.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Vendor invoice</strong></p></td>
<td><p>Create workflows for vendor invoice headers. You can view the invoices in the <strong>Vendor invoice</strong> form.</p>
<p>To use workflows together with vendor invoice policies, make sure that the <strong>Post invoice with discrepancies</strong> field is set to <strong>Allow with warning</strong> in the <strong>Accounts payable parameters</strong> form.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Vendor invoice line</strong></p></td>
<td><p>Create workflows for vendor invoice lines. You can view the invoices in the <strong>Vendor invoice</strong> form.</p>
<p>To use workflows together with vendor invoice policies, make sure that the <strong>Post invoice with discrepancies</strong> field is set to <strong>Allow with warning</strong> in the <strong>Accounts payable parameters</strong> form.</p></td>
</tr>
<tr class="even">
<td><p><strong>Vendor invoice journal workflow</strong></p></td>
<td><p>Create approval workflows for invoice recording journals.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Vendor disbursement journal workflow</strong></p></td>
<td><p>Create approval workflows for vendor disbursement journals.</p></td>
</tr>
<tr class="even">
<td><p><strong>Vendor draw promissory note journal workflow</strong></p></td>
<td><p>Create approval workflows for vendor draw promissory note journals.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Vendor redraw promissory note journal workflow</strong></p></td>
<td><p>Create approval workflows for vendor redraw promissory note journals.</p></td>
</tr>
<tr class="even">
<td><p><strong>Vendor bank remittance journal workflow</strong></p></td>
<td><p>Create approval workflows for vendor bank remittance journals.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Vendor settle promissory note journal workflow</strong></p></td>
<td><p>Create approval workflows for vendor settle promissory note journals.</p></td>
</tr>
</tbody>
</table>


## Automated tasks and manual tasks for vendor invoices

You can use the following workflow tasks to perform an action on a vendor invoice.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Type</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Post vendor invoices</strong></p></td>
<td><p>Automated</p></td>
<td><p>Post vendor invoices automatically. This task can be used together with other tasks. This task should be the last task element in the workflow configuration. If a review or approval process is used, that process should occur before this automated task. For an example of how the <strong>Post vendor invoices</strong> automatic task is used, see <a href="workflow-with-a-conditional-decision.md">Workflow with a conditional decision</a>.</p>
<p>This automated task does not work with vendor invoices that are in an approval journal. Post approval journals manually.</p></td>
</tr>
<tr class="even">
<td><p><strong>Evaluate policy rules for invoices</strong></p></td>
<td><p>Automated</p></td>
<td><p>Evaluate policy violations on vendor invoices. For information about how to use workflow and policies together, see <a href="key-tasks-vendor-invoice-policies.md">Key tasks: Vendor invoice policies</a>.</p>
<p>If a vendor invoice violates one or more policy rules at the header level, this task reports the violations in the <strong>Policy violations</strong> form for that invoice. For an example of how the <strong>Evaluate policy rules for invoices</strong> automatic task is used, see <a href="workflow-with-a-conditional-decision.md">Workflow with a conditional decision</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Review vendor invoice</strong></p></td>
<td><p>Manual</p></td>
<td><p>Assign this task to a user who can perform a review of vendor invoice lines that are in the vendor invoice. You define the steps for the review in the description section when you create the workflow.</p>
<p>The difference between a review manual task and an approval workflow element is that, if the review manual task is assigned to multiple users, the workflow can continue after any one of those users completes the task. If you assign an approval workflow element to multiple users, all those users must approve the document before the workflow can continue. For more information, see <a href="workflow-with-multiple-users-in-a-task.md">Workflow with multiple users in a task</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Review vendor invoice matching</strong></p></td>
<td><p>Manual</p></td>
<td><p>Assign this task to a user if the user must review the vendor invoice to determine whether it has invoice matching discrepancies.</p>
<p>The difference between a review manual task and an approval workflow element is that, if the review manual task is assigned to multiple users, the workflow can continue after any one of those users completes the task. If you assign an approval workflow element to multiple users, all those users must approve the document before the workflow can continue. For more information, see <a href="workflow-with-multiple-users-in-a-task.md">Workflow with multiple users in a task</a>.</p></td>
</tr>
</tbody>
</table>


## Automated tasks and manual tasks for vendor invoice lines

You can use the following workflow tasks to perform an action on a vendor invoice line.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Type</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Evaluate policy rules for invoice lines</strong></p></td>
<td><p>Automated</p></td>
<td><p>Evaluate policy violations on vendor invoice lines. This automated task differs from the <strong>Evaluate policy rules for invoices</strong> task, because it evaluates only policies that use a rule type that is based on the <strong>Vendor invoice lines</strong> query name. For information about how to use workflow and policies together, see <a href="key-tasks-vendor-invoice-policies.md">Key tasks: Vendor invoice policies</a>.</p>
<p>If a vendor invoice violates one or more policy rules at the line level, this task reports the violations in the <strong>Policy violations</strong> form for that invoice. For an example of how the <strong>Evaluate policy rules for invoice lines</strong> automatic task is used, see <a href="workflow-with-a-conditional-decision.md">Workflow with a conditional decision</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Review vendor invoice line</strong></p></td>
<td><p>Manual</p></td>
<td><p>Assign this task to a user who can perform a review of vendor invoice lines that are in the vendor invoice. You define the steps for the review in the description section when you create the workflow.</p>
<p>The difference between a review manual task and an approval workflow element is that, if the review manual task is assigned to multiple users, the workflow can continue after any one of those users completes the task. If you assign an approval workflow element to multiple users, all those users must approve the document before the workflow can continue. For more information, see <a href="workflow-with-multiple-users-in-a-task.md">Workflow with multiple users in a task</a>.</p></td>
</tr>
</tbody>
</table>


## Create a workflow

To create a workflow, follow these steps.

1.  Click **Accounts payable** \> **Setup** \> **Accounts payable workflows**.

2.  On the **Action Pane**, click **New**.

3.  Select the type of workflow to create, and then click **Create workflow**. The workflow editor is displayed. Design the workflow by dragging workflow elements onto the canvas.

4.  Configure each element of the workflow. For more information, see [Configure workflow elements](configure-workflow-elements.md).

5.  Repeat steps 2 through 4 to create additional workflows for Accounts payable.

6.  If you are setting up journal workflows, set up journal approvals for specific journals by using the **Journal names** form. For more information, see [Set up financial journal approvals](set-up-financial-journal-approvals.md).

## Calculated fields and expressions

The following calculated fields and expressions are used with Accounts payable workflow journal approvals. For each workflow, you can set up conditions that include these calculated fields and expressions.

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
<td><p><strong>Invoice amount</strong></p></td>
<td><p>The total invoice amount for the vendor invoice.</p>
<p>This field is available for <strong>Vendor invoice</strong> and <strong>Vendor invoice line</strong> workflows.</p></td>
</tr>
<tr class="even">
<td><p><strong>Journal credit total</strong></p></td>
<td>The total credit amount for the whole journal.
<p>This field is available for journal workflows.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Journal debit total</strong></p></td>
<td>The total debit amount for the whole journal.
<p>This field is available for journal workflows.</p></td>
</tr>
<tr class="even">
<td><p><strong>Maximum voucher credit amount</strong></p></td>
<td>The highest credit voucher amount in the journal.
<p>This field is available for journal workflows.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Maximum voucher debit amount</strong></p></td>
<td>The highest debit voucher amount in the journal.
<p>This field is available for journal workflows.</p></td>
</tr>
<tr class="even">
<td><p><strong>Minimum voucher credit amount</strong></p></td>
<td>The lowest credit voucher amount in the journal.
<p>This field is available for journal workflows.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Minimum voucher debit amount</strong></p></td>
<td>The lowest debit voucher amount in the journal.
<p>This field is available for journal workflows.</p></td>
</tr>
</tbody>
</table>


## Types of participants

You can assign a workflow element to the following groups of participants.

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
<td><p><strong>Security role participants</strong></p></td>
<td><p>Assign the workflow element to a Microsoft Dynamics AX security role.</p></td>
</tr>
<tr class="even">
<td><p><strong>User group participants</strong></p></td>
<td><p>Assign the workflow element to a Microsoft Dynamics AX user group.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Vendor invoice expenditure participants</strong></p></td>
<td><p>Use this group to assign the workflow element to expenditure participants. This option is available for the elements that are associated with <strong>Vendor invoice</strong> and <strong>Vendor invoice line</strong> workflows.</p></td>
</tr>
</tbody>
</table>


## See also

[Journal names (form)](https://technet.microsoft.com/en-us/library/aa617509\(v=ax.60\))

[Key tasks: Vendor invoice policies](key-tasks-vendor-invoice-policies.md)

  


