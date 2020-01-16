---
title: Set up Budgeting workflows
TOCTitle: Set up Budgeting workflows
ms:assetid: 062e69fc-cd63-4c59-a249-b41bef7f6d26
ms:mtpsurl: https://technet.microsoft.com/library/Hh242112(v=AX.60)
ms:contentKeyID: 36055960
author: Khairunj
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- budget transaction workflows
- workflows for budget transactions
audience: Application User
ms.search.region: Global
---

# Set up Budgeting workflows 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Some organizations require that Budgeting documents, such as budget register entries and general budget reservations, be approved by a user other than the person who entered them. To set up an approval process, you can create a Budgeting workflow. You can also set up other processes to update budget balances without user intervention or to have a user review the information in a Budgeting document.

This topic has been updated to include information about features that were added or changed in the following hotfix for Microsoft Dynamics AX 2012 R3 Cumulative Update 8: KB3047235

A workflow represents a business process. It defines how a document flows through the system and indicates who must complete a task or approve a document. There are several benefits of using the workflow system in your organization:

  - **Consistent processes** — You can define the approval process for specific documents, such as purchase requisitions and expense reports. Using the workflow system helps to ensure that documents are processed and approved in a consistent and efficient manner.

  - **Process visibility** — You can track the status, history, and performance metrics of a specific workflow instance. This helps you determine whether changes should be made to the workflow to improve efficiency.

  - **Centralized work list** — Users can view a centralized work list to view the workflow tasks and approvals assigned to them. This work list is available from the Role Center pages in the Microsoft Dynamics AX client and Enterprise Portal.

## Budgeting workflows

Use this information to set up and enable workflow configurations for Budgeting documents. Based on the document type, you can require manual approval, workflow approval, or no approval.

If you set up a workflow for budget account entries, the workflow must be contained in another workflow for budget register entries. If all the budget account entries in a budget register entry can be approved as group, you can use a **Budget register entry workflow**. If the budget account entry lines require different workflow approvals, you must use a **Budget account entry workflow** to create different workflow configurations. For example, you might use one **Budget account entry workflow** configuration to review and approve a high amount, and another **Budget account entry workflow** configuration to review and approve a low amount.

You can associate budget register entry workflows with any of the budget codes that have been set up to identify the budget types. After you assign a workflow to a budget code, all budget register entries that use that budget code require workflow approval before you can update budget balances. For more information, see [Define budget codes](define-budget-codes.md).

After you create a workflow configuration for a Budgeting document, additional controls are displayed at the top of the form when the document is saved. These controls include a yellow information bar and a **Submit** button or an **Actions** menu. For more information, see [Submit a document](submit-a-document.md) and [Workflow actions](workflow-actions.md).


> [!NOTE]
> <P>Some buttons in the <STRONG>Budget register entry</STRONG> form are not available after a budget register entry has been submitted for workflow approval. When the budget register entry or budget account entry is approved, the options in the <STRONG>Update</STRONG> and <STRONG>Transfer</STRONG> menus are available. Other controls and fields in the form might not be available. If you modify a budget register entry that has been approved, the budget register entry must be resubmitted to workflow. You cannot modify a budget register entry after you update budget balances.</P>



For an overview of workflow in Microsoft Dynamics AX, see [Overview of the workflow system](overview-of-the-workflow-system.md) and [Workflow concepts](workflow-concepts.md).

You can use workflow approvals for the following Budgeting document types.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Budgeting menu item</p></th>
<th><p>Document type</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Budget plans</strong></p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed.</P>


</div></td>
<td><p>Budget plan</p></td>
</tr>
<tr class="even">
<td><p><strong>Budget register entry</strong></p></td>
<td><p>Budget register entry</p></td>
</tr>
<tr class="odd">
<td><p><strong>Budget account entries</strong></p></td>
<td><p>Budget account entry</p></td>
</tr>
<tr class="even">
<td><p><strong>Commitments</strong></p>
<p>This control is available only if the following conditions are met:</p>
<ul>
<li><p>The <strong>Public Sector</strong> configuration key is selected.</p></li>
<li><p>The <strong>French regulatory</strong> configuration subkey is selected.</p></li>
<li><p>In Microsoft Dynamics AX 2012 R3 Cumulative Update 8, the <strong>Commitments (France)</strong> regulatory document type is selected in the <strong>Budget parameters</strong> form, when the following hotfix is installed: KB3047235</p></li>
<li><p>In cumulative update 7 for Microsoft Dynamics AX 2012, the <strong>Use French public sector accounting rules</strong> check box is selected in the <strong>Budget parameters</strong> form.</p></li>
</ul>
<p>In versions of Microsoft Dynamics AX 2012 prior to cumulative update 7, only the <strong>Public Sector</strong> configuration key must be selected, but the primary address of the legal entity must be in France.</p></td>
<td><p>Commitment</p></td>
</tr>
<tr class="odd">
<td><strong>General budget reservations</strong> 
<div class="alert">

> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>


</div></td>
<td><p>General budget reservation</p></td>
</tr>
</tbody>
</table>


## New or changed for Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 R3, and the General Budget Reservation hotfix KB3047235

You must set up Budgeting workflows for budget plans before you set up a budget planning process. The budget plan workflow configuration that you set up is used to submit budget plans, and their worksheets and justifications, for review and approval in each stage of a budget planning process. The budget planning process defines the order of the budget planning stages and associates the process with a budget organization hierarchy. When you configure the workflow, you can assign users to a workflow task based on the budget organization, security role, or user group.

When you configure a budget planning process, you associate a Budgeting workflow ID with each budget planning workflow. After the budget plan is submitted to the workflow, and a user finishes an assignment, the budget plan moves to the next budget planning stage by using the stage transition element in the Budgeting workflow configuration.

## The types of workflows you can create

The following table lists the types of workflows that you can create in Budgeting.

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
<td><p><strong>Budget plan workflows</strong></p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed.</P>


</div></td>
<td><p>Create review and approval workflows for budget plans. Budget plan workflows must contain a stage transition element for each transition that moves a budget plan to the next budget planning stage. For example, a workflow for a budget planning process that has three stages requires two stage transition elements to connect the three approval elements that are associated with the three budget planning stages. For more information, see “Workflows” in <a href="about-budget-planning-configuration-and-setup.md">About budget planning configuration and setup</a>.</p>
<ul>
<li><p><strong>Approve budget plan</strong> – Create an approval element for budget plans.</p></li>
<li><p><strong>Activate associated budget plan</strong> – Create an automated task to activate the budget plan that is associated with a parent budget plan.</p></li>
<li><p><strong>Stage transition budget plan</strong> – Create an automated task to perform a stage transition for a budget plan.</p></li>
<li><p><strong>Budget planning stage allocation</strong> – Create an automated task to perform a budget planning stage allocation that uses the allocation schedule for a budget plan scenario estimate.</p></li>
<li><p><strong>Flow controls</strong> – Create standard workflow elements to branch decisions and activities.</p></li>
<li><p><strong>Review associated budget plan(s) that are completed</strong> – Create a task for a user to review the completed budget plans that are associated with a parent budget plan.</p></li>
<li><p><strong>Review budget plan</strong> – Create a task for a user to review budget plans.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Budget account entry workflow</strong></p></td>
<td><p>Create review and approval workflows for budget account entries. Use the <strong>Budget account entry workflow</strong> element to include budget account entry workflows in a budget register entry workflow.</p>
<p>This workflow type contains standard workflow elements and elements that you can use for budget account entries:</p>
<ul>
<li><p><strong>Approve budget account entry</strong> – Create an approval element for budget account entries.</p></li>
<li><p><strong>Flow controls</strong> – Create standard workflow elements to branch decisions and activities.</p></li>
<li><p><strong>Review budget account entry</strong> – Create a task for a user to review the accuracy of a budget account entry.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Budget register entry workflow</strong></p></td>
<td><p>Create review and approval workflows for budget register entries.</p>
<p>This workflow type contains standard workflow elements and elements you can use for budget register entry workflows:</p>
<ul>
<li><p><strong>Approve budget register entry</strong> – Create an approval element for budget register entries.</p></li>
<li><p><strong>Update budget balances budget register</strong> – Create an automated task to update budget balances.</p></li>
<li><p><strong>Flow controls</strong> – Create standard workflow elements to branch decisions and activities.</p></li>
<li><p><strong>Budget account entry workflow</strong> – Include a <strong>Budget account entry workflow</strong> type.</p></li>
<li><p><strong>Review budget register entry</strong> – Create a task for a user to review the accuracy of a budget register entry.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Commitments approval</strong></p>
<p>This control is available only if the following conditions are met:</p>
<ul>
<li><p>The <strong>Public Sector</strong> configuration key is selected.</p></li>
<li><p>The <strong>French regulatory</strong> configuration subkey is selected.</p></li>
<li><p>In Microsoft Dynamics AX 2012 R3 Cumulative Update 8, the <strong>Commitments (France)</strong> regulatory document type is selected in the <strong>Budget parameters</strong> form, when the following hotfix is installed: KB3047235</p></li>
<li><p>In cumulative update 7 for Microsoft Dynamics AX 2012, the <strong>Use French public sector accounting rules</strong> check box is selected in the <strong>Budget parameters</strong> form.</p></li>
</ul>
<p>In versions of Microsoft Dynamics AX 2012 prior to cumulative update 7, only the <strong>Public Sector</strong> configuration key must be selected, but the primary address of the legal entity must be in France.</p></td>
<td><p>Create approval workflows for commitments. After you set up and activate a commitment workflow, all commitments must use it.</p>
<p>This workflow type contains standard workflow elements and elements that you can use for commitment approval workflows:</p>
<ul>
<li><p><strong>Commitment approval</strong> – Create an approval element for commitments.</p></li>
<li><p><strong>Flow controls</strong> – Create standard workflow elements to branch decisions and activities.</p></li>
<li><p><strong>Commitment task</strong> – Create a task for a user to review the accuracy of a commitment.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>General budget reservations</strong> 
<div class="alert">

> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>


</div></td>
<td><p>Create approval workflows for general budget reservations. After you set up this workflow, you must assign it to a reservation type in order to use it. All general budget reservations of the same type use the same workflow.</p>
<p>This workflow type contains standard workflow elements and elements that you can use for general budget reservation approval workflows:</p>
<ul>
<li><p><strong>Commitment approval</strong> – Create an approval element for general budget reservations.</p></li>
<li><p><strong>Flow controls</strong> – Create standard workflow elements to branch decisions and activities.</p></li>
<li><p><strong>Commitment task</strong> – Create a task for a user to review the accuracy of a general budget reservation.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Create a workflow

To create a workflow, follow these steps.

1.  Click **Budgeting** \> **Setup** \> **Budgeting workflows**.

2.  On the **Action Pane**, click **New**.

3.  Select the type of workflow to create.

4.  Click **Create workflow**. The workflow editor is displayed. Design the workflow by dragging workflow elements onto the canvas.

5.  Configure each element of the workflow. For more information, see [Configure workflow elements](configure-workflow-elements.md).

6.  Repeat steps 2 through 5 to create additional workflows for Budgeting.

## Calculated fields and expressions

The following calculated fields and expressions are used with Budgeting workflow approvals. For each workflow, you can set up conditions that include the calculated fields and expressions.

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
<td><p><strong>Budget check results</strong></p></td>
<td><p>The budget control results. The possible results are <strong>Budget check passed</strong>, <strong>Budget check passed but with warnings</strong>, <strong>Budget check failed</strong>, and <strong>Budget check not performed</strong>.</p>
<p>This field is available for <strong>Budget account entry workflow</strong> and <strong>Budget register entry workflow</strong> configurations.</p></td>
</tr>
<tr class="even">
<td><p><strong>Transfer rule violated</strong></p></td>
<td><p>Evaluate a violation of the budget transfer rule. The possible values are <strong>Yes</strong> or <strong>No</strong>. If a budget transfer rule is violated, and the value is set to <strong>Yes</strong>, the workflow can be assigned to a user who can approve budget transfers when budget transfer rules are violated.</p>
<p>This field is available for <strong>Budget account entry workflow</strong> and <strong>Budget register entry workflow</strong> configurations.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Transaction currency amount</strong></p></td>
<td><p>The transaction amount, in the accounting currency.</p>
<p>This field is available for <strong>Budget account entry workflow</strong> and <strong>Budget register entry workflow</strong> configurations.</p>
<div class="alert">

> [!NOTE]
> <P>When <STRONG>Transaction currency amount</STRONG> is used for transfers, you must include a second condition to ignore any negative amounts. For example:</P>
> <UL>
> <LI>
> <P>Where <STRONG>Budget account entries</STRONG>.<STRONG>Transaction currency amount</STRONG> is less than <STRONG>100,000</STRONG></P>
> <LI>
> <P>And <STRONG>Budget account entries</STRONG>.<STRONG>Transaction currency amount</STRONG> is greater than <STRONG>0</STRONG></P></LI></UL>


</div></td>
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
<td><p><strong>Budget manager participants</strong></p></td>
<td><p>Assign the workflow element to a user who is defined as the budget manager in the budget control configuration. The budget manager can approve budget register entries. Additional budget managers for financial dimension values can be defined by using budget control rules. For more information, see <a href="https://technet.microsoft.com/library/hh242209(v=ax.60)">Budget control configuration (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Budget organization participants</strong></p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed.</P>


</div></td>
<td><p>Assign the workflow element to a budget organization participant. Budget organization participants are available only for budgeting planning workflows.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Security role participants</strong></p></td>
<td><p>Assign the workflow element to a Microsoft Dynamics AX security role.</p></td>
</tr>
<tr class="even">
<td><p><strong>User group participants</strong></p></td>
<td><p>Assign the workflow element to a Microsoft Dynamics AX user group.</p></td>
</tr>
</tbody>
</table>


## See also

[Get started with the workflow system](get-started-with-the-workflow-system.md)

[Configure the workflow system](configure-the-workflow-system.md)

[Design and configure workflows for Microsoft Dynamics AX](design-and-configure-workflows-for-microsoft-dynamics-ax.md)

[Monitor the status of workflows](monitor-the-status-of-workflows.md)

[Using workflows](using-workflows.md)

[Set up general budget reservation workflows (Public sector)](set-up-general-budget-reservation-workflows-public-sector.md)

  


