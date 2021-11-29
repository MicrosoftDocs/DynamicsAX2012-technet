---
title: Set up vendor invoice workflows
TOCTitle: Set up vendor invoice workflows
ms:assetid: 627fb0f8-ca65-477b-ad9e-585b727e5dc3
ms:mtpsurl: https://technet.microsoft.com/library/Dn277352(v=AX.60)
ms:contentKeyID: 54658649
author: Khairunj
ms.date: 08/22/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up vendor invoice workflows 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up one or more workflow configurations for vendor invoices and vendor invoice lines. For example, you might set up workflow for vendor invoices that aren’t for a purchase order, or to automatically run invoice matching on invoices that are for a purchase order. If workflow approval is set up for vendor invoices, additional controls are displayed at the top of the **Vendor invoice** form. These include a yellow information bar, and either a **Submit** button or an **Actions** menu. For more information, see [Submit a document](submit-a-document.md) and [Workflow actions](workflow-actions.md).

Some buttons in the **Vendor invoice** form are not available when an invoice has been submitted for workflow journal approval. When the invoice is approved, the options in the **Post** group on the **Action Pane** are available, and the other controls and fields in the form are not. If a user changes an approved invoice, the workflow status is reset, the options in the **Post** group are not available, and the other controls and fields are available. The user must resubmit the changed invoice for approval.

The following illustration shows how to set up vendor invoice workflows. The numbers correspond to the procedures later in this topic.

![Flowchart for setting up vendor invoice workflows](images/Dn277352.SetUpVendorInvoiceWorkflows(AX.60).gif "Flowchart for setting up vendor invoice workflows")

## Example

The following illustration shows an example of a vendor invoice workflow that includes the following workflow elements:

  - An automated task, **Evaluate policy rules for invoices**

  - A manual task, **Review vendor invoice matching**

  - A conditional decision, **Is the total amount under 10,000?**

  - An approval task, **Approve vendor invoice**

  - An automated task, **Post vendor invoices**

![Workflow with a conditional decision](images/JJ618308.Workflow_WithConditionalDecision(AX.60).gif "Workflow with a conditional decision")

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
<td><p><a href="set-up-accounts-payable-invoice-matching.md">Set up Accounts payable invoice matching</a></p>
<p><a href="key-tasks-vendor-invoice-policies.md">Key tasks: Vendor invoice policies</a></p></td>
</tr>
<tr class="even">
<td><p>Accounts payable parameters</p></td>
<td><p>To use workflows together with vendor invoice policies, make sure that the <strong>Post invoice with discrepancies</strong> field is set to <strong>Allow with warning</strong> in the <strong>Accounts payable parameters</strong> form.</p></td>
</tr>
</tbody>
</table>


## 1\. Optional: Set up expenditure reviewers for vendor invoices

You can set up expenditure reviewer configurations to route expenditures for review based on the user who is assigned to a project role or the financial dimension where the expenditure is being charged. The workflow process uses the specified project role or financial dimension owner to determine whom to route the expenditure to.

You don’t have to set up an expenditure reviewer configuration. You can assign a specific user or user group as a reviewer when you define the workflow. However, if you have a complex organization, you can improve the efficiency of the approval process by specifying expenditure reviewers. Also, you won’t have to change the workflow reviewer assignments every time that a reviewer changes job roles.

To set up expenditure reviewers for vendor invoices, follow these steps:

1.  Click **Accounts payable** \> **Setup** \> **Policies** \> **Vendor invoice expenditure reviewers**.

2.  On the **Action Pane**, click **New**.

3.  Enter a name for the expenditure reviewer definition.

4.  On the **Project distributions** FastTab, select the check box for the project role that is responsible for reviewing vendor invoices that are assigned to a project. You can select **Project manager**, **Project controller**, or **Project sales manager**. Expenditures will be routed to the user who is assigned to that role. You can also route the expenditure to the financial dimension owner by selecting the appropriate financial dimension check box.

5.  On the **Organization distributions** FastTab, select the check box for the financial dimensions that you want to use to route vendor invoices that are not assigned to a project. Vendor invoices will be routed to the user who owns the financial dimension.

## 2\. If required: Set up the roles for project distributions

Complete this procedure if you set up an expenditure reviewer and selected any of the options in the **Project authority** field group in the **Vendor invoice expenditure reviewers** form.

You can assign people to the roles for project distributions.

To set up the roles for project distributions, follow these steps:

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**.

2.  Select a project, and then click **Edit** on the **Action Pane**.

3.  In the **Projects** form, use the fields in the **Responsible** field group to assign workers to the roles that are required for your business practices. Use the information in the following table to decide which roles to assign workers to.
    
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
    <td><p><strong>Sales manager</strong></p></td>
    <td><p>This role corresponds to the <strong>Project sales manager</strong> role that is specified for the expenditure review participant.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Project manager</strong></p></td>
    <td><p>This role corresponds to the <strong>Project manager</strong> role that is specified for the expenditure review participant.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Project controller</strong></p></td>
    <td><p>This role corresponds to the <strong>Project controller</strong> role that is specified for the expenditure review participant.</p></td>
    </tr>
    </tbody>
    </table>


## 3\. If required: Set up the owners for financial dimensions

Complete this procedure if you set up an expenditure reviewer and selected any of the options in either of the **Financial dimensions** field groups in the **Vendor invoice expenditure reviewers** form.

You can assign people to be owners of a financial dimension. This lets you set up workflow approvals by financial dimensions, for example, by department or cost center. You can also require that approvals for a vendor invoice be sent to the owners of all the distributions for a line item. For example, if you enter a vendor invoice for rent expense and distribute the line item to three different departments, the workflow approval step will go to the owners of all three departments.

To set up the owners for financial dimensions, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Financial dimensions** \> **Financial dimensions**.

2.  Select a financial dimension, and then click **Financial dimension values**.

3.  Select a dimension.

4.  On the **General** FastTab, in the **Owner** field, select the user ID of the person who is the owner of this dimension.

5.  Repeat steps 2 and 3 for the remaining financial dimensions.

## 4\. Create a workflow for vendor invoices

You can create multiple workflows for vendor invoices.

To create a workflow for vendor invoices, follow these steps:

1.  Click **Accounts payable** \> **Setup** \> **Accounts payable workflows**.

2.  On the **Action Pane**, click **New**.

3.  Select the type of workflow to create, and then click **Create workflow**.
    
    Select from the following options:
    
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
    <td><p><strong>Vendor invoice</strong></p></td>
    <td><p>Create workflows for vendor invoice headers. You can view the invoices in the <strong>Vendor invoice</strong> form.</p>
    <p>To use workflows together with vendor invoice policies, make sure that the <strong>Post invoice with discrepancies</strong> field is set to <strong>Allow with warning</strong> in the <strong>Accounts payable parameters</strong> form.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Vendor invoice line</strong></p></td>
    <td><p>Create workflows for vendor invoice lines. You can’t run a vendor invoice line workflow by itself. You must add it to a vendor invoice workflow. You can view the invoices in the <strong>Vendor invoice</strong> form.</p>
    <p>To use workflows together with vendor invoice policies, make sure that the <strong>Post invoice with discrepancies</strong> field is set to <strong>Allow with warning</strong> in the <strong>Accounts payable parameters</strong> form.</p></td>
    </tr>
    </tbody>
    </table>


4.  Configure each element of the workflow. For more information, see [Configure workflow elements](configure-workflow-elements.md).

5.  Repeat steps 2 through 4 to create additional workflows for vendor invoices.

## 5\. Optional: Configure automated and manual tasks for vendor invoice workflows

Complete this procedure if your business practices require any of the following:

  - A person to review a vendor invoice

  - A person to review the results of invoice matching

  - An automated process to evaluate policy rules for invoices

  - An automated process to post the invoices

You can use a combination of automated and manual tasks in the same workflow.

Each of the following workflow tasks can perform an action on a vendor invoice. Use the information in the following table to decide which workflow tasks to use.

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
<td><p>Post vendor invoices automatically. This task can be used with other tasks, but should be the last task element in the workflow configuration. If a review or approval process is used, that process should occur before this automated task. For an example of how the <strong>Post vendor invoices</strong> automatic task is used, see <a href="workflow-with-a-conditional-decision.md">Workflow with a conditional decision</a>.</p>
<p>This automated task does not work with vendor invoices that are from an approval journal. Post approval journals manually.</p></td>
</tr>
<tr class="even">
<td><p><strong>Evaluate policy rules for invoices</strong></p></td>
<td><p>Automated</p></td>
<td><p>Evaluate policy violations on vendor invoices. For information about how to use workflow and policies together, see <a href="key-tasks-vendor-invoice-policies.md">Key tasks: Vendor invoice policies</a>.</p>
<p>If one or more policy rules for an invoice is violated at the header level, the violations are displayed in the <strong>Policy violations</strong> form for that invoice. For an example of how the <strong>Evaluate policy rules for invoices</strong> automatic task is used, see <a href="workflow-with-a-conditional-decision.md">Workflow with a conditional decision</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Review vendor invoice</strong></p></td>
<td><p>Manual</p></td>
<td><p>Assign this task to a user who is authorized to review the vendor invoice lines that are in the vendor invoice. You define the steps for the review in the description section when you create the workflow.</p>
<p>The difference between a review manual task and an approval workflow element:</p>
<ul>
<li><p>If the review manual task is assigned to multiple users, the workflow can continue after any one of those users completes the task.</p></li>
<li><p>If you assign an approval workflow element to multiple users, all those users must approve the document before the workflow can continue.</p></li>
</ul>
<p>For more information, see <a href="workflow-with-multiple-users-in-a-task.md">Workflow with multiple users in a task</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Review vendor invoice matching</strong></p></td>
<td><p>Manual</p></td>
<td><p>Match product receipts automatically to vendor invoices by creating a batch task to run in a batch job.</p>
<ol>
<li><p>Click <strong>System administration</strong> &gt; <strong>Inquiries</strong> &gt; <strong>Batch jobs</strong> &gt; <strong>Batch jobs</strong>.</p></li>
<li><p>In the <strong>Batch job</strong> form, click the <strong>View tasks</strong> button.</p></li>
<li><p>In the <strong>Batch tasks</strong> form, in the <strong>Class name</strong> field, select <strong>VendInvoiceMatch.</strong></p></li>
</ol>
<p>This batch process will match product receipts to their corresponding invoices. The batch process applies to vendor invoices that were entered in a vendor portal or received through a service.  </p>
<p>For more information, see <a href="create-a-batch-job.md">Create a batch job</a>.</p></td>
</tr>
</tbody>
</table>


To configure automated and manual tasks for a vendor invoice workflow, follow these steps:

  - For automated tasks, see [Configure an automated task](configure-an-automated-task.md).

  - For manual tasks, see [Configure a manual task](configure-a-manual-task.md).

## 6\. Optional: Configure automated and manual tasks for vendor invoice line workflows

Complete this procedure if your business practices require any of the following things:

  - A person to review the results of invoice matching

  - An automated process to evaluate policy rules for a vendor invoice line

You can use a combination of automated and manual tasks in the same workflow.

Each of the following workflow tasks can perform an action on a vendor invoice line. Use the information in the following table to decide which workflow tasks to use.

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
<td><p>Evaluate policy violations on vendor invoice lines. This automated task differs from the <strong>Evaluate policy rules for invoices</strong> task because it evaluates only policies that use a rule type that is based on the <strong>Vendor invoice lines</strong> query name. For information about how to use workflow and policies together, see <a href="key-tasks-vendor-invoice-policies.md">Key tasks: Vendor invoice policies</a>.</p>
<p>If a vendor invoice violates one or more policy rules at the line level, this task reports the violations in the <strong>Policy violations</strong> form for that invoice. For an example of how the <strong>Evaluate policy rules for invoice lines</strong> automatic task is used, see <a href="workflow-with-a-conditional-decision.md">Workflow with a conditional decision</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Review vendor invoice line</strong></p></td>
<td><p>Manual</p></td>
<td><p>Assign this task to a user who can perform a review of vendor invoice lines that are in the vendor invoice. You define the steps for the review in the description section when you create the workflow.</p>
<p>The difference between a review manual task and an approval workflow element:</p>
<ul>
<li><p>If the review manual task is assigned to multiple users, the workflow can continue after any one of those users completes the task.</p></li>
<li><p>If you assign an approval workflow element to multiple users, all those users must approve the document before the workflow can continue.</p></li>
</ul>
<p>For more information, see <a href="workflow-with-multiple-users-in-a-task.md">Workflow with multiple users in a task</a>.</p></td>
</tr>
</tbody>
</table>


To configure automated and manual tasks for a vendor invoice line workflow, follow these steps:

  - For automated tasks, see [Configure an automated task](configure-an-automated-task.md).

  - For manual tasks, see [Configure a manual task](configure-a-manual-task.md).

## 7\. Optional: Create conditional decisions

Complete this procedure if your business processes require different workflow processes depending on the amount of the invoice or other amounts such as sales taxes or charges.

The **Invoice amount** field is used with vendor invoice and vendor invoice line workflows. For each workflow, you can set up conditions that include this field. For example, you can require that invoice amounts that are greater than 5,000 require one approver and that invoice amounts that are greater than 20,000 require two approvers.

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
<td><p>The total invoice amount for the vendor invoice.</p></td>
</tr>
</tbody>
</table>


To create conditions, see the following topic:

  - [Configure a conditional decision](configure-a-conditional-decision.md)

## 8\. Assign participants to workflow elements

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
<td><p>Assign the workflow element to a Microsoft Dynamics AX security role. You might use this option if a group of workers can approve invoices and it doesn’t matter which person approves a particular invoice.</p></td>
</tr>
<tr class="even">
<td><p>User group participants</p></td>
<td><p>Assign the workflow element to a Microsoft Dynamics AX user group. You might use this option if a group of workers can approve invoices and it doesn’t matter which person approves a particular invoice.</p></td>
</tr>
<tr class="odd">
<td><p>Vendor invoice expenditure participants</p></td>
<td><p>Assign the workflow element to expenditure participants. Expenditure participants can include users who are associated with specific projects or who are owners for specific financial dimensions, such as departments and cost centers. This option provides the most control and the most flexibility for vendor invoice and vendor invoice line workflows.</p></td>
</tr>
</tbody>
</table>


  - For instructions about how to assign participants to a workflow, see [Configure workflow elements](configure-workflow-elements.md).

## Related tasks

[Set up Accounts payable invoice matching](set-up-accounts-payable-invoice-matching.md)

[Key tasks: Vendor invoice policies](key-tasks-vendor-invoice-policies.md)

[Set up Accounts payable workflows](set-up-accounts-payable-workflows.md)

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
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To perform this task, you must be a member of the <strong>-SYSADMIN-</strong> security role.</p></td>
</tr>
</tbody>
</table>

  


