---
title: Organization hierarchies
TOCTitle: Organization hierarchies
ms:assetid: ed0999cf-d17e-4e60-aca4-1c130e1ea0a5
ms:mtpsurl: https://technet.microsoft.com/library/Dn223357(v=AX.60)
ms:contentKeyID: 54453516
author: tonyafehr
ms.date: 11/19/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Organization hierarchies 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

When you create an organization hierarchy in Microsoft Dynamics AX, you must assign a purpose to the hierarchy. The purpose that you assign to a hierarchy determines the types of organizations that can be included in the hierarchy. The purpose also defines the application scenarios that the hierarchy can be used in.

A hierarchy that is created for a purpose may not reflect the actual legal structure of the business. For example, the approval process for requisitions may involve multiple legal entities and positions that don’t report to each other. For instance, the CFO might be required to approve a requisition of a certain amount, even though the organization that submits the requisition does not report to the CFO.

Hierarchies can be used for the following purposes:

  - Centralized customer and vendor payments

  - Policies

  - Organization charts

  - Data access

  - Retail channel management

  - Budget planning

  - Project management

## Centralized customer and vendor payments

Organizations that include multiple legal entities can create and manage payments by using a single legal entity that handles all payments (known as centralized payments). When you centralize payments, the same transaction does not have to be entered in multiple legal entities, and the processes for cross-company payments are simpler. For example, it’s easier to make payment proposals and settlements, and modify open and closed transactions.

To use a hierarchy in this scenario, you must assign the **Centralized payments** purpose to the hierarchy. For more information, see:

  - [About centralized vendor payments](about-centralized-vendor-payments.md)

  - [Set up centralized vendor payments](set-up-centralized-vendor-payments.md)

  - [About centralized customer payments](about-centralized-customer-payments.md)

  - [Set up centralized customer payments](set-up-centralized-customer-payments.md)

## Policies

A policy is a collection of rules that controls a process for an organization. Policies help organizations manage internal processes and help improve cost control, fraud detection, operating efficiency, and performance. To use a hierarchy to set up policies, you must assign an appropriate purpose to the hierarchy. For more information about how to set up policies, see [Set up policy parameters](set-up-policy-parameters.md).

The following table lists the processes that you can control by using policies. It also includes the hierarchy purpose that corresponds to each process.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Process</p></th>
<th><p>Description</p></th>
<th><p>Hierarchy purpose</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Purchasing</p></td>
<td><p>Controls the requisition process for a group of requisitioners. You can use a purchasing policy to create a policy structure that is aligned with your organization's strategic purchasing needs.</p></td>
<td><p><strong>Procurement internal control</strong></p></td>
<td><p><a href="about-purchasing-policies.md">About purchasing policies</a></p>
<p><a href="key-tasks-create-purchasing-policies.md">Key tasks: Create purchasing policies</a></p></td>
</tr>
<tr class="even">
<td><p>Vendor invoicing</p></td>
<td><p>Enables you to evaluate vendor invoices for compliance with policy rules that you create.</p></td>
<td><p><strong>Vendor payment internal control</strong></p></td>
<td><p><a href="key-tasks-vendor-invoice-policies.md">Key tasks: Vendor invoice policies</a></p></td>
</tr>
<tr class="odd">
<td><p>Auditing</p></td>
<td><p>Helps you implement the compliance strategy for your organization.</p></td>
<td><p><strong>Audit internal control</strong></p></td>
<td><p><a href="key-tasks-audit-policies.md">Key tasks: Audit policies</a></p></td>
</tr>
<tr class="even">
<td><p>Expenses</p></td>
<td><p>Controls the process for expense reports.</p></td>
<td><p><strong>Expenditure internal control</strong></p></td>
<td><p><a href="about-travel-and-expense-policies.md">About travel and expense policies</a></p>
<p><a href="create-policies.md">Create policies</a></p></td>
</tr>
<tr class="odd">
<td><p>Signing limits</p></td>
<td><p>Controls the level of financial commitment that a worker is authorized to make on behalf of his or her employer. As a result of the worker's approval activity, the employer may enter into a contractual relationship with a third-party, such as a purchase order with a vendor.</p></td>
<td><p><strong>Signature authority internal control</strong></p></td>
<td><p><a href="about-signing-limit-setup.md">About signing limit setup</a></p>
<p><a href="key-tasks-manage-signing-limit-policies.md">Key tasks: Manage signing-limit policies</a></p></td>
</tr>
<tr class="even">
<td><p>Benefits eligibility</p></td>
<td><p>Define and exercise eligibility rules for each benefit that your organization offers to workers. You can use these rules to identify the specific benefits that a worker is eligible for.</p></td>
<td><p><strong>Benefit eligibility control</strong></p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed.</P>


</div></td>
<td><p><a href="key-tasks-benefit-eligibility-policies.md">Key tasks: Benefit eligibility policies</a></p></td>
</tr>
</tbody>
</table>


## Organization chart

An organization chart defines the relationships between departments, jobs, and positions. To use a hierarchy in this scenario, you must assign the **Organization chart** purpose to it. For more information, see [Key tasks: New worker positions](key-tasks-new-worker-positions.md).

## Data access

A user's access to data in Microsoft Dynamics AX can be granted based on the user's relationship to an organization. To use a hierarchy in this scenario, you must assign the **Security** purpose to it. You must also create data security policies to help secure the organizations in the hierarchy. Then, when you associate a user who is in a particular role with a hierarchy, the user's access to data changes automatically when the hierarchy changes. For more information, see [Overview of Security Policies for Table Records](https://technet.microsoft.com/library/hh272123\(v=ax.60\)) and [Organizations for the automatic role assignment rule (form) or Organizations for the user (form)](https://technet.microsoft.com/library/hh242784\(v=ax.60\)).

If **Based on security organizations** is the security model selected for budget planning, for example, you must assign the **Security** purpose to the budget planning organization hierarchy so budget plan preparers have access to the budget plans. For more information, see Budget planning in this topic, [Configure budget planning security](configure-budget-planning-security.md), [Configuring Budget Planning for Microsoft Dynamics AX 2012 R2](configuring-budget-planning-for-microsoft-dynamics-ax-2012-r2.md), and [Key tasks: Configure budget planning and set up budget planning processes](key-tasks-configure-budget-planning-and-set-up-budget-planning-processes.md).

## Retail channel management

The following table describes the retail scenarios where organization hierarchies can be used.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Description</p></th>
<th><p>Hierarchy purpose</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Manage retail assortments</p></td>
<td><p>Identify the products that are available in each retail channel, such as a brick and mortar store or an online store.</p></td>
<td><p><strong>Retail assortment</strong></p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed.</P>


</div></td>
<td><p><a href="about-setting-up-assortments.md">About setting up assortments</a></p></td>
</tr>
<tr class="even">
<td><p>Manage retail replenishment</p></td>
<td><p>Group stores to replenish inventory based on replenishment rules.</p></td>
<td><p><strong>Retail replenishment</strong></p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed.</P>


</div></td>
<td><p><a href="set-up-replenishment-hierarchies.md">Set up replenishment hierarchies</a></p>
<p><a href="set-up-replenishment-rules.md">Set up replenishment rules</a></p></td>
</tr>
<tr class="odd">
<td><p>Report data for stores</p></td>
<td><p>Group stores for reporting.</p></td>
<td><p><strong>Retail reporting</strong></p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed.</P>


</div></td>
<td><p><a href="about-retail-stores.md">About retail stores</a></p></td>
</tr>
<tr class="even">
<td><p>Post inventory, calculate statements, or post statements for a group of stores</p></td>
<td><p>Create a group of stores that can be assigned to a batch job. When you define a batch job to post inventory, calculate statements, or post statements, you can specify which hierarchy the job applies to. When stores are added to or removed from the hierarchy, you don’t have to modify the batch job.</p></td>
<td><p><strong>Retail POS posting</strong></p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed.</P>


</div></td>
<td><p><a href="about-working-with-store-inventory.md">About working with store inventory</a></p>
<p><a href="create-and-post-a-statement.md">Create and post a statement</a></p></td>
</tr>
</tbody>
</table>


## Budget planning

Budget planning is the process of preparing the budgets that are implemented by an organization. You can use budget planning to perform the following tasks:

  - Associate budget planning processes with budget cycles, ledgers, and organization hierarchies.

  - Analyze and update budget plans by using multiple scenarios. You can automatically route the budget plans, together with worksheets, justifications, and attachments, for review and approval.

  - Consolidate multiple budget plans from a lower level in the organization into a single parent budget plan at a higher level in the organization. You can also develop a single budget plan at a higher level in the organization and allocate the budget to lower levels in the organization.

The following table describes how organization hierarchies are used for budget planning.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Description</p></th>
<th><p>Hierarchy purpose</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Budget planning</p></td>
<td><p>When the <strong>Budget planning</strong> purpose is assigned to an organization hierarchy, a hierarchical relationship can exist between parent and associated budget plans. You can also define different budgeting workflows by organizational unit in a budget planning process.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed.</P>


</div></td>
<td><p><strong>Budget planning</strong></p></td>
<td><p><a href="budget-planning-overview.md">Budget planning overview</a></p>
<p><a href="key-tasks-configure-budget-planning-and-set-up-budget-planning-processes.md">Key tasks: Configure budget planning and set up budget planning processes</a></p>
<p><a href="https://go.microsoft.com/fwlink/?linkid=507697">Configuring Budget Planning for Microsoft Dynamics AX 2012 R3</a></p></td>
</tr>
<tr class="even">
<td><p>Security model: Based on security organizations</p></td>
<td><p>If <strong>Based on security organizations</strong> is the security model selected for budget planning, to use a hierarchy in this scenario, you must also assign the <strong>Security</strong> purpose to the budget planning organization hierarchy.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only in Microsoft Dynamics AX 2012 R3 Cumulative Update 8 and later.</P>


</div></td>
<td><p><strong>Security</strong></p></td>
<td><p>Data access in this topic</p>
<p><a href="configure-budget-planning-security.md">Configure budget planning security</a></p>
<p><a href="configuring-budget-planning-for-microsoft-dynamics-ax-2012-r2.md">Configuring Budget Planning for Microsoft Dynamics AX 2012 R2</a></p>
<p><a href="key-tasks-configure-budget-planning-and-set-up-budget-planning-processes.md">Key tasks: Configure budget planning and set up budget planning processes</a></p></td>
</tr>
</tbody>
</table>


## Project management

The **All projects** list page displays a list of pending project transactions and posted project transactions. You can view these transactions by organization, if you have set up a hierarchy for project management.

To use a hierarchy in this scenario, you must assign the **Project management** purpose to the hierarchy.


> [!NOTE]
> <P>This control is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed.</P>



For more information, see [View project transactions](view-project-transactions.md).

  


