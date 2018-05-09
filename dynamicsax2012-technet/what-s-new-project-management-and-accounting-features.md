---
title: "What's new: Project management and accounting features"
TOCTitle: Project management and accounting features
ms:assetid: 7f974cb1-fe38-4a96-a931-568cc0676ce3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527160(v=AX.60)
ms:contentKeyID: 59623290
ms.date: 11/14/2014
mtps_version: v=AX.60
---

# What's new: Project management and accounting features 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

We have changed and added functionality in the [Project management and accounting](project-management-and-accounting.md) area for Microsoft Dynamics AX 2012. For more information, see the tables that apply to your version of the product.

## What’s new in AX 2012

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Display the status of project budgets in purchasing forms</p></td>
<td><p>You can now display the status of a project budget in purchase requisition forms, purchase order forms, and vendor invoice forms. Therefore, you can easily monitor the remaining available budget for projects. This change also supports budget control and the evaluation of proposed purchases during management review or workflow approval.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="https://technet.microsoft.com/en-us/library/hh209453(v=ax.60)">Purchase requisitions (form)</a></p></li>
<li><p><a href="https://technet.microsoft.com/en-us/library/aa557983(v=ax.60)">Purchase order (form)</a></p></li>
<li><p><a href="https://technet.microsoft.com/en-us/library/hh209644(v=ax.60)">Vendor invoice (form)</a></p></li>
<li><p><a href="create-a-purchase-order.md">Create a purchase order</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Changes to the Project accounting cube</p></td>
<td><p>Several nonessential fields have been removed from the Project cube perspective. However, the fields that are related to measures and attributes remain. Therefore, the cube is easier to work with and maintain, and is less likely to be negatively affected by schema changes.</p>
<p>For more information, see <a href="project-accounting-cube-projcube-for-microsoft-dynamics-ax-2012-and-microsoft-dynamics-ax-2012-feature-pack.md">Project accounting cube (ProjCube) for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack</a>.</p></td>
</tr>
<tr class="odd">
<td><p>ID numbers for project contracts can now be assigned automatically</p></td>
<td><p>Legal entities can now have ID numbers for project contracts assigned automatically through a number sequence when a new project contract is created in the <strong>Project contracts</strong> form.</p>
<p>For more information, see <a href="automatically-generate-project-ids.md">Automatically generate project IDs</a>.</p></td>
</tr>
<tr class="even">
<td><p>Associate any sales order, purchase order, or service-related document with a project</p></td>
<td><p>You can assign a project ID to any sales order, purchase order, service agreement, service order, or service subscription. Previously, these types of documents could be associated with a project ID only if they were created in Project management and accounting.</p></td>
</tr>
<tr class="odd">
<td><p>Enter and track detailed information about grants for projects</p></td>
<td><p>You can easily enter and track grants, and define relationships to new or existing projects and project contracts. Grant information is stored in a centralized location. Therefore, you can quickly and easily find the information that you require for reporting and informational purposes.</p>
<p>For more information, see <a href="create-or-modify-a-grant.md">Create or modify a grant</a> and <a href="about-project-contract-funding.md">About project contract funding</a>.</p></td>
</tr>
<tr class="even">
<td><p>Evaluate vendor invoices against project budgets</p></td>
<td><p>Vendor invoices can now be evaluated against project budgets.</p>
<p>For more information, see <a href="about-invoicing.md">About invoicing</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Enhancements to the budget functionality in projects</p></td>
<td><p>Project budget capabilities have been enhanced as follows:</p>
<ul>
<li><p>Project budgeting can now be performed at the activity level. For more information, see <a href="about-monitoring-the-progress-of-a-project.md">About monitoring the progress of a project</a>.</p></li>
<li><p>An original project budget can be created to define a budget at various levels in the project hierarchy. For more information, see <a href="create-and-submit-an-original-project-budget.md">Create and submit an original project budget</a>.</p></li>
<li><p>An original budget can be submitted for review and approval. For more information, see <a href="create-and-submit-an-original-project-budget.md">Create and submit an original project budget</a>.</p></li>
<li><p>An original project budget and a budget revision can be allocated over a period. For more information, see <a href="allocate-a-project-budget-or-budget-revision-across-periods.md">Allocate a project budget or budget revision across periods</a>.</p></li>
<li><p>Project budget revisions can be created to revise a budget at various levels in the project hierarchy.</p></li>
<li><p>Revisions to a budget can be submitted for review and approval. For more information, see <a href="revise-and-submit-a-project-budget.md">Revise and submit a project budget</a>.</p></li>
<li><p>Approval of a proposed budget revision causes an immediate change to the overall project budget. For more information, see <a href="review-a-submitted-project-budget-or-budget-revision.md">Review a submitted project budget or budget revision</a>.</p></li>
<li><p>A history, or audit trail, of proposed, accepted, and rejected budget revisions is available for review. For more information, see <a href="review-the-workflow-status-and-history-for-a-project-budget.md">Review the workflow status and history for a project budget</a>.</p></li>
<li><p>The <strong>Project budget balances</strong> form includes a detailed presentation of the project budget. For more information, see <a href="https://technet.microsoft.com/en-us/library/hh209310(v=ax.60)">Project budget balances (form)</a>.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Enhancements to project integration with Microsoft Project Server</p></td>
<td><p>Project managers can already schedule and manage project activities and resources by using Project Server. In addition, project managers can synchronize activity, costs, and revenue with Microsoft Dynamics AX to support additional analysis of data.</p>
<p>Enhancements support the synchronization of resource assignments and the project hierarchy with Microsoft Project Server 2010.</p>
<p>In addition, custom code enables Microsoft Dynamics AX custom fields to be integrated with Project Server at the table level.</p>
<p>For more information, see <a href="about-microsoft-dynamics-ax-integration-with-microsoft-project-server.md">About Microsoft Dynamics AX integration with Microsoft Project Server</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Upgrades for item charges on lines for purchase orders, sales orders, and invoices</p></td>
<td><p>Item charges on lines for purchase orders, sales orders, and invoices are now recognized in Project management and accounting. The ledger account and the posting type for the charge are derived from the primary line amount. In addition, any taxes for item charges are reflected in an expense account. The item charges and related taxes are also recorded in the project commitments and budget.</p>
<p>For more information, see <a href="about-posting-setup-for-project-transactions.md">About posting setup for project transactions</a>.</p></td>
</tr>
<tr class="even">
<td><p>Enhancements to project timesheets</p></td>
<td><p>The forms and pages that are used for timesheet-related tasks now provide a more user-friendly experience that builds on existing support for project timesheets. Approvals at the level of the timesheet line now use support from the workflow framework for lines to achieve consistency with other tasks. The way that comments and the starting and ending dates for a period are used has also changed. In addition, timesheet support in Enterprise Portal for Microsoft Dynamics AX lets you manage favorites, and to quickly create a timesheet based on either a previous timesheet or favorites.</p>
<p>For more information, see <a href="create-and-maintain-timesheets.md">Create and maintain timesheets</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Enhancements to project budgeting</p></td>
<td><p>Significant improvements to project budgeting simplify the financial management of projects. By using the new budget control method, you can perform the following tasks:</p>
<ul>
<li><p>Allocate project budget amounts to multiple fiscal periods and fiscal years.</p></li>
<li><p>Revise budgets.</p></li>
<li><p>Control whether the budget is verified. In addition, you can control whether transactions that exceed the budget balance are allowed after the user receives a warning, or whether these transactions are blocked.</p></li>
<li><p>Extend committed costs to purchase requisitions.</p></li>
<li><p>Apply budget control to all project transactions. These transactions include revenue transactions, purchase requisitions, and purchase orders.</p></li>
</ul>
<p>For more information, see <a href="about-project-budgets.md">About project budgets</a> and <a href="about-project-budgets-and-forecasts.md">About project budgets and forecasts</a>.</p></td>
</tr>
<tr class="even">
<td><p>Carry forward project budget amounts at year end</p></td>
<td><p>If you are working with a project that lasts multiple years, at the end of the year, you can carry forward any remaining budget to future years and make the required changes to the associated general ledger accounts.</p>
<p>For more information, see <a href="carry-forward-project-budgets-at-year-end.md">Carry forward project budgets at year-end</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Support for multiple funding sources</p></td>
<td><p>In earlier versions of Microsoft Dynamics AX, you could invoice only one customer per project or contract project. Now, the funding for a single project or project contract can be shared by any number of internal and external parties. You can choose whether any of these parties are subject to funding limits. In addition, by configuring a funding scheme, you can set up funding limits for one or more customers per category, category group, or transaction type, or for all transaction types.</p>
<p>For more information, see <a href="about-project-contract-funding.md">About project contract funding</a>.</p></td>
</tr>
<tr class="even">
<td><p>Collaboration workspaces</p></td>
<td><p>You can now create collaboration workspaces where teams can quickly organize and share information about projects, marketing campaigns, and opportunities. Because collaboration workspaces are built on features in Microsoft SharePoint Services and MicrosoftOffice SharePoint Server, they include familiar elements, such as document libraries, announcement lists, calendar items, tasks, and discussion boards. You can add collaboration workspaces to existing projects, campaigns, and opportunities. In addition, you can configure Microsoft Dynamics AX options so that new collaboration workspaces are automatically created for projects, campaigns, and opportunities.</p>
<p>For more information, see <a href="select-preferences-for-collaboration-workspaces.md">Select preferences for collaboration workspaces</a> and <a href="create-or-link-to-a-collaboration-workspace-project.md">Create or link to a collaboration workspace (Project)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Create and manage projects in Enterprise Portal</p></td>
<td><p>Project managers can create and maintain projects in the web-based Enterprise Portal. Previously, time and expense entry was the only project-related feature that was available. Web-based support makes it easier for project managers to work remotely, and frees them from having to deal with software installations, upgrades, and patches.</p>
<p>For more information, see <a href="using-the-project-management-site.md">Using the Project management site</a>.</p></td>
</tr>
<tr class="even">
<td><p>Enter and approve worker timesheets in Enterprise Portal</p></td>
<td><p>Enterprise Portal includes a timesheet page where workers can enter the hours that they worked each day on one or more projects. In addition, project managers can review and approve worker timesheets in Enterprise Portal.</p>
<p>For more information, see <a href="working-with-timesheets.md">Working with timesheets</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Enter a beginning balance for a project</p></td>
<td><p>You can now enter a beginning balance for a new or existing project. By specifying a beginning balance, you can transfer projects to Microsoft Dynamics AX without affecting the general ledger. For example, you have been tracking a project in another program, but recording project costs and revenues in Microsoft Dynamics AX. In this case, you can transfer the project to Microsoft Dynamics AX, specify a beginning balance, and then track the project information in only one place.</p>
<p>For more information, see <a href="about-project-beginning-balances.md">About project beginning balances</a>.</p></td>
</tr>
<tr class="even">
<td><p>Track project revenue from a free text invoice</p></td>
<td><p>Revenue that is billed by using a free text invoice can now be tracked to a project.</p>
<p>For more information, see <a href="about-transaction-types.md">About transaction types</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Enhancements to adjustments</p></td>
<td><p>Adjustment capabilities have been enhanced as follows:</p>
<ul>
<li><p>Transactions that have been invoiced and estimated can be adjusted. Previously, only transactions that were not invoiced or calculated in an estimate could be adjusted.</p></li>
<li><p>The adjustment date can be used as the project date for transactions, instead of the original transaction date.</p></li>
<li><p>The relationship between an original transaction, its reversal, and a new replacement transaction can be traced. The information that is traced can include the user who made each adjustment.</p></li>
<li><p>If an item transaction that is created from a purchase order is adjusted to a new project before the vendor is paid, you can use the new Adjustment cash flow trace feature to report “Expected” and “Paid” from the new project.</p></li>
</ul>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="about-adjusting-transactions-in-projects.md">About adjusting transactions in projects</a></p></li>
<li><p><a href="configure-the-adjustment-trace-display.md">Configure the adjustment trace display</a></p></li>
<li><p><a href="project-management-and-accounting-reports.md">Project management and accounting reports</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Support for progress billing, estimates, and revenue recognition when you migrate data from other Enterprise Resource Planning (ERP) systems</p></td>
<td><p>When you migrate data from one ERP system to another, one challenge is to bring existing data into the estimation system, so that revenue can continue to be recognized for Fixed-price projects that have already started. Because revenue recognition is based on a completed percentage, the data must be migrated so that both the percentage of work that is already completed (actual cost) and the amount of work that remains on the project (estimated cost to complete) are reflected in the correct accounts.</p>
<p>Because some Fixed-price projects can span multiple years, the actual cost to date can also be derived from several years of transactions. Therefore, the key challenge in an ERP migration is to post a lump sum transaction in the beginning balance journal and connect it correctly to the estimate system.</p>
<p>To address these data migration issues, the new beginning balance and progress billing features integrate with the existing estimation system to support revenue recognition for Fixed-price projects.</p>
<p>For more information, see <a href="about-migrating-project-data-from-other-erp-systems.md">About migrating project data from other ERP systems</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Miscellaneous updates for Project management and accounting features</p></td>
<td><p>A series of minor feature changes have been implemented for Project management and accounting:</p>
<ul>
<li><p>The <strong>Worker ID</strong>, formerly <strong>Employee ID</strong>, field is no longer required for hourly transactions in Project management and accounting. Therefore, route operations can be assigned to work center groups, not just to individual work centers.</p></li>
<li><p>Several references to period tables in Project management and accounting have been replaced with fiscal calendar objects, relations, and methods.</p>
<p>For more information, see <a href="about-fiscal-calendars-fiscal-years-and-periods.md">About fiscal calendars, fiscal years, and periods</a>.</p></li>
<li><p>You can copy a project ID to a purchase order when the purchase order is made from an item requirement has been restored. This functionality is required, so that users can view a full list of the purchase orders that are related to a project.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Funding sources for project ledger posting</p></td>
<td><p>If you use multiple funding sources together with project contracts, you can configure ledger posting based on funding source by project, project group, category, category group, or all these options. For each posting type, you can associate projects and funding sources with specific accounts.</p>
<p>For more information, see <a href="set-up-a-ledger-posting-account-for-projects.md">Set up a ledger posting account for projects</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Designate a project cost price as an effective labor rate</p></td>
<td><p>AX 2012 R2 introduces support for specifying a worker's hourly cost price on projects as an effective labor rate. The effective labor rate defines the hourly cost if the worker works all the hours in a work week. The cost price of the effective labor rate for a period is calculated by using the following formula:</p>
<p>Effective labor rate price per hour * (Number of hours in the work week according to the worker's calendar / Number of hours registered in the week)</p>
<p>The <strong>Project setup</strong> form now includes a <strong>Use effective labor rate</strong> check box. If this check box is selected, you can mark a worker's hourly price in the <strong>Cost price - hour</strong> form as an effective labor rate.</p>
<p>For more information, see <a href="https://technet.microsoft.com/en-us/library/hh209540(v=ax.60)">Project setup (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Select a value model for estimate eliminations</p></td>
<td><p>For investment projects, in the <strong>Estimate</strong> form, you can now select the value model that is applied when the value from an estimate project is eliminated to a fixed asset.</p>
<p>For more information, see <a href="about-maintaining-estimates.md">About maintaining estimates</a> and <a href="https://technet.microsoft.com/en-us/library/aa590971(v=ax.60)">Estimate (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Enhancements to project invoice proposals and printing project documents</p></td>
<td><p>View all invoice proposals on a new list page for project invoice proposals. Distribute project funding amounts to multiple funding sources. Set up invoice forecasting on a bi-weekly basis. Set up printing for all types of projects, project contracts, project quotations, invoice proposals, and project invoices. Print comments on project documents that you send to customers.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="create-and-post-invoice-proposals.md">Create and post invoice proposals</a></p></li>
<li><p><a href="examples-project-contract-funding.md">Examples: Project contract funding</a></p></li>
<li><p><a href="about-project-forecasts.md">About project forecasts</a></p></li>
<li><p><a href="set-up-print-management-for-a-module.md">Set up print management for a module</a></p></li>
<li><p><a href="add-details-or-comments-to-a-timesheet.md">Add details or comments to a timesheet</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Improved support for project estimates and revenue recognition</p></td>
<td><p>In earlier versions of Microsoft Dynamics AX, a project manager who wanted an estimate project to be created to support a Fixed-price project or an Investment project had to remember to select the <strong>New estimate project</strong> check box in the <strong>Create project</strong> form. Otherwise, use of the estimate system to recognize revenue was not fully supported.</p>
<p>In AX 2012 R2, an estimate project is created automatically when the project manager creates a Fixed-price project or Investment project. As part of this change, cost templates and period codes no longer have to be assigned to each project individually, but can be assigned to project groups instead. This change supports the more common practice of using the same cost template and estimate period for most or all Fixed-price projects and Investment projects. This change also reflects the fact that other accrual and revenue recognition options are set up in project groups.</p>
<p>For more information, see <a href="create-an-estimate-project.md">Create an estimate project</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Intercompany resource scheduling and UX improvements</p></td>
<td><p>Major enhancements have been made to the resource scheduling feature in the Project Management and Accounting Add-in (Project III).</p>
<p>A new intercompany resource scheduling feature makes it easy for a worker in one legal entity to be assigned to a project in a related legal entity.</p>
<p>Support for staffing a project and viewing the status of project staffing is improved. Therefore, project managers can now more easily perform several tasks:</p>
<ul>
<li><p>Discover the scheduling status of a project.</p></li>
<li><p>Find the best resources for projects and activities.</p></li>
<li><p>Assign resources to projects and activities. Resources can also be automatically assigned to projects.</p></li>
</ul>
<p>Project managers can also easily view a list of resources that are assigned to a project, release resources from all assignments in a project, and view the assignment details for resources that are assigned to a project.</p>
<p>Soft-booking support has been updated, so that a worker’s soft-booked hours do not count against the worker’s overall availability.</p>
<p>When a project is closed, all of a worker’s bookings that are made for the project are released automatically.</p>
<p>Resources that are assigned to a project no longer have to be manually added to a validation group for the project. This validation, which lets a worker enter timesheet lines for the project, is set up automatically when a worker is assigned to a project.</p>
<p>For more information, see the white paper <a href="http://www.microsoft.com/en-us/download/details.aspx?id=36845">Microsoft Dynamics AX 2012 R2 White Paper: Resource Scheduling for Projects</a>.</p></td>
</tr>
<tr class="even">
<td><p>Expanded support for project budget checks when document lines are saved</p></td>
<td><p>In the <strong>Project management and accounting parameters</strong> form, the <strong>Check budget on document line save</strong> option previously applied only to financial budget documents, such as purchase requisitions and purchase orders, not to journals that are related to project budget. In AX 2012 R2, budget checks are now performed when changes are made to hour journals, expense journals, fee journals, and item journals. Budget checks are triggered when changes are made to any of the following fields:</p>
<ul>
<li><p>Project ID</p></li>
<li><p>Activity number</p></li>
<li><p>Category</p></li>
<li><p>Date of transaction</p></li>
<li><p>Cost price</p></li>
<li><p>Sales price</p></li>
<li><p>Sales currency</p></li>
</ul>
<p>For more information, see <a href="configure-project-budget-control.md">Configure project budget control</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Consumption of project items on product receipt, even if there is no item requirement</p></td>
<td><p>In AX 2012, if an item was added to the purchase order for a project but was not preceded by an item requirement, the item could not be consumed and invoiced to the project contract's funding source until the related vendor invoice was posted. In AX 2012 R2, project items can be immediately consumed and invoiced to the project’s contract funding source, before the vendor invoice for the purchase order is posted, even if an item requirement does not precede the purchase order.</p>
<p>For more information, see <a href="consume-item-requirements-in-a-project.md">Consume item requirements in a project</a>.</p></td>
</tr>
<tr class="even">
<td><p>Reservation of funds in a project contract</p></td>
<td><p>The funding limits in the project contract can now be used to track revenue that has not yet been posted as commitments. This functionality allows for more realistic limit checks, because the commitments are considered while the remaining available funds in a limit are computed. This tracking of commitments on a limit is available to all the source documents that have project functionality.</p>
<p>For more information, see <a href="examples-project-contract-funding.md">Examples: Project contract funding</a> and <a href="set-up-funding-limits-for-funding-sources-in-a-project-contract.md">Set up funding limits for funding sources in a project contract</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in cumulative update 6 for Microsoft Dynamics AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Reverse an hour transaction for a project</p></td>
<td><p>You can set up a reversing entry for hours that are posted to a project, and you can also specify the date on which the reversing entry is automatically posted. Previously, you could post a reversing entry only on the date on which you created the reversing entry.</p>
<p>For more information, see <a href="https://technet.microsoft.com/en-us/library/aa571787(v=ax.60)">Journal lines for hours (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Generate project budget revenue amounts from budget cost amounts for a project</p></td>
<td><p>After you enter cost amounts in a project budget, you can automatically generate the related revenue amounts in the project budget. One revenue line is added for each cost line.</p>
<p>For more information, see <a href="create-and-submit-an-original-project-budget.md">Create and submit an original project budget</a>.</p></td>
</tr>
<tr class="odd">
<td><p>New Integration Solution for Microsoft Dynamics AX projects and Microsoft Dynamics CRM</p></td>
<td><p>The Integration Solution for Microsoft Dynamics AX projects and Microsoft Dynamics CRM is built on Connector for Microsoft Dynamics. This solution enables the integration and synchronization of project quotations and projects between Microsoft Dynamics AX and Microsoft Dynamics CRM.</p>
<p>For more information, see <a href="about-synchronizing-project-information-between-microsoft-dynamics-ax-and-microsoft-dynamics-crm.md">About synchronizing project information between Microsoft Dynamics AX and Microsoft Dynamics CRM</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in cumulative update 7 for Microsoft Dynamics AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Use Microsoft Project to create or update a Microsoft Dynamics AX project plan, and integrate with an Office 365 SharePoint project site.</p></td>
<td><p>You can use Microsoft Project and AX 2012 to manage a project that was created in either program, and changes can be synchronized between the two programs. This integration lets you assign workers from AX 2012 to tasks in Microsoft Project, and to associate tasks in Microsoft Project with project categories in AX 2012.</p>
<p>This integration with Microsoft Project also lets you use features of Office 365 SharePoint project sites. You can now perform the following tasks:</p>
<ul>
<li><p>Create and modify a AX 2012 project in an Office 365 SharePoint project site.</p></li>
<li><p>Publish a project from Microsoft Project to an Office 365 SharePoint project site.</p></li>
<li><p>Store a linked MPP file in an on-premises SharePoint site without having to generate a task list.</p></li>
<li><p>Use collaboration workspace functionality for AX 2012 projects together with Microsoft SharePoint 2013 Products, even SharePoint online.</p></li>
</ul>
<p>For more information, see <a href="create-or-update-a-project-by-using-microsoft-project.md">Create or update a project by using Microsoft Project</a>.</p></td>
</tr>
<tr class="even">
<td><p>Use Microsoft Project to create or update the work breakdown structure (WBS) for a Microsoft Dynamics AX project quotation</p></td>
<td><p>You can now use the Microsoft Project client to create and update the WBS of a project quotation from AX 2012. You can also save the WBS for the quotation, in a Microsoft Project MPP file, in a SharePoint site.</p>
<p>For more information, see <a href="create-or-update-a-project-by-using-microsoft-project.md">Create or update a project by using Microsoft Project</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Create a WBS template for Microsoft Dynamics AX by using Microsoft Project</p></td>
<td><p>You can create a WBS template in Microsoft Project that can be used in AX 2012. This template can be made available to selected companies in AX 2012, and can be used for both quotations and projects. In addition, because the template is based on a linked MPP file, information types that are used in Microsoft Project but not in AX 2012, such as types of resources that are required (material, work, and so on), are retained and maintained in Microsoft Project.</p>
<p>For more information, see <a href="create-or-update-a-project-by-using-microsoft-project.md">Create or update a project by using Microsoft Project</a>.</p></td>
</tr>
<tr class="even">
<td><p>Expanded support for working with project teams, defining project role types, and managing projects</p></td>
<td><p>Project managers can now perform the following tasks:</p>
<ul>
<li><p>Define project role types, and define the role competencies that are required for a project.</p></li>
<li><p>Create a project team by reserving workers for specific roles.</p></li>
<li><p>Assign both workers that have been added to a project team and other workers to project activities.</p></li>
<li><p>Identify the number of workers that is required for an activity.</p></li>
<li><p>View a list of workers who meet the requirements of project roles in the following order: skills match, previous project roles, and availability.</p></li>
<li><p>View a graphical representation of available workers who can satisfy the resource requirements for the project team.</p></li>
<li><p>Authorize project team members to report time and expense in a project.</p></li>
</ul>
<p>For more information, see <a href="about-resource-management-for-projects.md">About resource management for projects</a> and <a href="identify-and-assign-qualified-workers-to-projects.md">Identify and assign qualified workers to projects</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Expanded support for managing worker assignments and capacity in projects</p></td>
<td><p>Updates in cumulative update 7 provide worker resource managers and project managers with several additional capabilities:</p>
<ul>
<li><p>Use a graphical representation of worker availability to see how many days, weeks, or months workers are available in a specific time range. The information that is displayed includes the worker’s available capacity in hours. From this graphical representation, you can also access a list of projects that the worker can be assigned to. In addition, you can view a graphical representation of the activities that workers are already assigned to.</p></li>
<li><p>Filter the display of workers in the graphical representation, based on the workers’ skill sets, cost price, name, and legal entity.</p></li>
<li><p>Reserve workers in bulk from project teams.</p></li>
<li><p>View projects that have requirements that match the competencies of a particular worker, and then assign the worker to one or more of those projects.</p></li>
<li><p>Assign resources to projects for weeks or months at a time, not just day by day.</p></li>
<li><p>See at a glance which workers are currently overbooked.</p></li>
<li><p>Contact workers by email, IM, or telephone, directly from a Gantt chart display.</p></li>
<li><p>View a list of workers that have a work calendar and work for a particular legal entity.</p></li>
<li><p>Select several workers at the same time, and assign them to a project for a specific period, such as a week or month.</p></li>
<li><p>Access a view of workers that are hired by other legal entities but lent to the legal entity that is managing the project.</p></li>
</ul>
<p>For more information, see <a href="about-resource-management-for-projects.md">About resource management for projects</a>.</p></td>
</tr>
<tr class="even">
<td><p>Enable audit trails on timesheet entry and reporting</p></td>
<td><p>You can enable parameters to track any changes or updates that are made to timesheet entries. You can also offer an option or require workers to provide a reason for any changes that are made to a timesheet. For example, if a worker enters the wrong date for a project and then has to correct the mistake, you can require that the worker note the reason for the change.</p>
<p>You can also block workers from entering any future time except an upcoming absence.</p></td>
</tr>
<tr class="odd">
<td><p>Improved management of project tasks in a WBS</p></td>
<td><p>The WBS has been redesigned to let you plan the schedule, skills, resources, costs, and revenue for tasks in a project in one form. You can view and automatically correct discrepancies in task schedules as you enter task information. You can also specify whether the start of a task depends on the completion of previous tasks.</p>
<p>For more information, see <a href="create-a-work-breakdown-structure-of-tasks-for-a-project.md">Create a work breakdown structure of tasks for a project</a>.</p></td>
</tr>
<tr class="even">
<td><p>Improvements for creating WBS templates for project tasks</p></td>
<td><p>There are new methods for creating a WBS template. You can copy some or all tasks from another template, and also from a WBS for a specific project.</p>
<p>For more information, see <a href="create-a-work-breakdown-structure-template-for-projects.md">Create a work breakdown structure template for projects</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Improved budget control for projects</p></td>
<td><p>You can automatically enter revenue budget amounts that are related to project cost amounts. You can also enforce budget limits for costs by project category.</p>
<p>For more information, see <a href="create-and-submit-an-original-project-budget.md">Create and submit an original project budget</a>.</p></td>
</tr>
<tr class="even">
<td><p>Intercompany pro forma invoices for project costs</p></td>
<td><p>You can create an intercompany pro forma invoice for items and services that are sent from one legal entity to another legal entity in your organization. You can specify the value and currency to use for the transferred costs.</p>
<p>For more information, see <a href="create-an-intercompany-project-invoice.md">Create an intercompany project invoice</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Billing rules for project milestones</p></td>
<td><p>You can create an on-account billing rule for projects. You can then automatically create customer invoices that are based on the project milestones that you specify. When work on the project reaches a specified milestone, you can set the status of the milestone as complete and then generate an on-account invoice for the milestone. For more information, see <a href="create-billing-rules.md">Create billing rules</a>.</p></td>
</tr>
<tr class="even">
<td><p>Modify project transactions in an invoice proposal.</p></td>
<td><p>In AX 2012, a preliminary invoice is known as an <em>invoice proposal</em>. After you create an invoice proposal for project transactions, you can modify the sales price for the project transactions in the invoice proposal. You can also create and add a fee transaction to the invoice proposal. For more information, see <a href="about-billing-rules.md">About billing rules</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Access additional views of project budget balances.</p></td>
<td><p>In the <strong>Project budget balances</strong> form, you can view summaries of project budget balances according to the following criteria:</p>
<ul>
<li><p><strong>Transaction type</strong></p></li>
<li><p><strong>Category group</strong></p></li>
<li><p><strong>Cost template</strong></p></li>
<li><p><strong>Category</strong></p></li>
</ul>
<p>For more information, see <a href="https://technet.microsoft.com/en-us/library/hh209310(v=ax.60)">Project budget balances (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Enhancements to tools for scheduling worker resources</p></td>
<td><p>AX 2012 R3 builds on the system for managing worker resource assignments that was introduced in cumulative update 7 for Microsoft Dynamics AX 2012 R2. Project managers now have additional options in AX 2012 R3:</p>
<ul>
<li><p>You can view text descriptions of worker availability in resource scheduling grids, such as <strong>Partially available</strong> and <strong>Booked</strong>. These text descriptions are used in addition to the colors that were introduced in cumulative update 7 for Microsoft Dynamics AX 2012 R2 to identify worker availability.</p></li>
<li><p>You can schedule workers on an activity for a specific number of hours.</p></li>
<li><p>You can convert selected soft-booked hours to hard-booked hours directly from the project team.</p></li>
<li><p>The concept of reserving workers has been renamed booking workers.</p></li>
</ul>
<p>For more information, see <a href="https://technet.microsoft.com/en-us/library/dn532267(v=ax.60)">View booking details (form)</a> and <a href="key-tasks-create-a-schedule-based-on-a-project-in-ax-2012-r3-or-ax-2012-r2-cu7.md">Key tasks: Create a schedule based on a project in AX 2012 R3 or AX 2012 R2 CU7</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Enhanced support for integrating projects between Microsoft Dynamics AX and Microsoft Project</p></td>
<td><p>AX 2012 R3 builds on the support for integration with projects in Microsoft Project that was introduced in cumulative update 7 for Microsoft Dynamics AX 2012 R2. Project managers now have additional options in AX 2012 R3:</p>
<ul>
<li><p>You can use Microsoft Project to open a project in Microsoft Dynamics AX.</p></li>
<li><p>You can create and update projects that are maintained in the Microsoft Dynamics AX system by using only Microsoft Project and the Microsoft Dynamics AX Add-in for Microsoft Project. In cumulative update 7 for Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX also had to be installed on your computer.</p></li>
<li><p>You can create a project contract for a project in Microsoft Dynamics AX when you first integrate a project that was created in Microsoft Project.</p></li>
</ul>
<p>For more information, see <a href="create-or-update-a-project-by-using-microsoft-project.md">Create or update a project by using Microsoft Project</a>.</p></td>
</tr>
</tbody>
</table>


## What's new in cumulative update 8 for Microsoft Dynamics AX 2012 R3

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Enhanced performance when calculating and posting fixed price revenue recognition</p></td>
<td><p>In this release of Microsoft Dynamics AX, the revenue recognition performance is enhanced to enable you to:</p>
<ul>
<li><p>Set up recurring revenue recognition for fixed price projects</p></li>
<li><p>Recognize revenue on a straight line basis for fixed-price projects.</p></li>
<li><p>Calculate and post the percent complete revenue recognition on a fixed-price project more quickly.</p></li>
</ul></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

