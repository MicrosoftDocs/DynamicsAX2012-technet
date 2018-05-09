---
title: "What's new: Budgeting features"
TOCTitle: Budgeting features
ms:assetid: 09b2d1e5-92a0-4d32-bc24-c01b47d523b6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn507116(v=AX.60)
ms:contentKeyID: 59623206
ms.date: 03/25/2015
mtps_version: v=AX.60
---

# What's new: Budgeting features 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

We have changed and added functionality in the [Budgeting](budgeting.md) area for Microsoft Dynamics AX 2012. For more information, see the tables that apply to your version of the product.

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
<td><p>Budget control is integrated with general journal entry.</p></td>
<td><p>If you are using budget control, you can validate spending, based on approved limits. You can specify that each purchase or planned purchase must be validated during processing to guarantee that the purchase does not exceed the budget funds that are available. You can use budget control for journals of the daily, allocation, and project expense account types. The vendor invoice recording journal and the vendor invoice approval journal can also be included in budget control. If you are using budget control for expense accounts, authorized users can override the available budget by transferring budget funds from other accounts. Those users can also reject purchases.</p>
<p>For more information, see <a href="about-budget-control.md">About budget control</a> and the white paper <a href="http://download.microsoft.com/download/4/e/3/4e36b655-568e-4d4a-b161-152b28baaf30/implementing_the_budget_control_framework_for_microsoft_dynamics_ax_2012_applications_ax_2012.pdf">Implementing the Budget Control Framework for Microsoft Dynamics AX 2012</a>.</p></td>
</tr>
<tr class="even">
<td><p>Enhanced budgeting</p></td>
<td><p>You can customize how budget entries are transferred from other modules. You can also use new check boxes in the <strong>Budgeting parameters</strong> form to specify whether budget register entries that are created from a cross-module transfer have a draft or completed status when they are first created. Additionally, it is now easier to identify newly transferred budget register entries in the <strong>Budget register entry</strong> form, because these entries have a budget type that resembles their origin. For example, budget register entries that are created from a fixed asset budget transfer have a budget type of <strong>Fixed assets</strong>.</p>
<p>For more information, see the white paper <a href="http://download.microsoft.com/download/4/e/3/4e36b655-568e-4d4a-b161-152b28baaf30/implementing_budgeting_for_microsoft_dynamics_ax_2012_applications_ax+2012.pdf">Implementing Budgeting for Microsoft Dynamics AX 2012</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Make sure that purchases do not exceed approved budgets.</p></td>
<td><p>Budget control lets you validate spending, based on approved limits. You can specify that each purchase or planned purchase must be validated during processing to guarantee that the purchase does not exceed the budget funds that are available. Budget verifications can be performed automatically, either when the purchase order lines are entered or when the purchase order is confirmed.</p>
<p>For more information, see <a href="scenario-use-budget-control-on-a-purchase-order.md">Scenario: Use budget control on a purchase order</a>.</p></td>
</tr>
<tr class="even">
<td><p>New reports for viewing and filtering budget information</p></td>
<td><p>The <strong>Budget details</strong> report shows all budget register entries by budget type. Total are shown by type. You can filter the report by budget model, date range, dimension, and status.</p>
<p>The <strong>Budget funds available</strong> report shows the sum of each budget category for the selected dimensions and time period. You can filter the report by budget model, date range, and dimension focus.</p>
<p>The <strong>Actual versus budget</strong> report compares budget amounts with actual balances. You can filter the report by budget model, dimension, date range, and dimension focus.</p>
<p>For more information, see <a href="budget-details-report-budgetdetails.md">Budget details report (BudgetDetails)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Transition from ledger budgets to budget register entries.</p></td>
<td><p>Ledger budgets have been replaced with budget register entries. You can use budget register entries to enter budget amounts for dimensions that are defined for budgeting. You can categorize budget register entries by budget type, such as revision, transfer, and original budget. Therefore, you can more quickly understand how a budget changed. Ledger budget records are automatically converted to budget register entries.</p>
<p>For more information, see <a href="create-budget-register-entries.md">Create budget register entries</a>.</p></td>
</tr>
<tr class="even">
<td><p>Budget control is integrated with accounts payable.</p></td>
<td><p>If you are using budget control, each purchase or planned purchase is validated during processing to guarantee that the purchase does not exceed the budget funds that are available. When a purchase is made by using a vendor invoice, any budget reservations are relieved for the budget of the distribution accounts on the purchase order. The vendor invoice distribution accounts and amounts are validated to determine whether budget funds are available. If the budget check is successful, budget tracking records are created that have a category of <strong>Actual expenditures</strong>. The whole cost of the vendor invoice line is evaluated. Any taxes or charges are included in the evaluation. The date on the vendor invoice line is associated with the appropriate fiscal period and budget interval to determine the budget period for validation.</p>
<p>For more information, see <a href="about-budget-control.md">About budget control</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Budgeting workflows</p></td>
<td><p>When you set up a review workflow, you can associate the workflow with a budget code to require that budget register entries use a review process. When a specified budget code is used on a budget register entry, a review process is required. You can define conditional statements for the review process to determine whether budget register entries are manually or automatically reviewed and approved. If you are using budget control, you can set up workflows so that a budget manager can approve budget register entries. Each budget account entry on a budget register entry can have its own review process. You can also set up rules that are independent of any review processes. For example, you can set up budget transfer rules to allow the transfer of budget funds among only a subset of departments. If budget transfer rules are violated, budget register entries can be assigned to a specific user for approval.</p>
<p>For more information, see <a href="set-up-budgeting-workflows.md">Set up Budgeting workflows</a>.</p></td>
</tr>
<tr class="even">
<td><p>Budgeting and budget control</p></td>
<td><p>You can set up budgets and configure budget control, based on the ledger for a legal entity. The ledger provides the chart of accounts, accounting and reporting currencies, and fiscal calendar. You can specify which dimensions from the chart of accounts are available for budgeting and budget control. You can configure budget intervals, budget cycle time spans, budget thresholds, budget managers, budget groups, and the calculation that is used to check for available budget funds. The available budget funds can be verified when source document line items and accounting journals are entered.</p>
<p>For more information, see <a href="about-budget-control.md">About budget control</a> and the white paper <a href="http://go.microsoft.com/fwlink/?linkid=213130%26clcid=0x409">Implementing the Budget Control Framework for Microsoft Dynamics AX 2012 Applications</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Use posting definitions for budget register entries.</p></td>
<td><p>You can create posting definitions for budget register entries and then use those posting definitions to create ledger entries when budget register entries are posted. This feature helps make posting faster and more efficient, because you can post to multiple accounts without making additional manual account entries.</p>
<p>For more information, see <a href="about-posting-definitions.md">About posting definitions</a>.</p></td>
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
<td><p>Create and approve budget plans.</p></td>
<td><p>You can use budget planning in AX 2012 R2 to establish a base budget, prepare and evaluate budget plans, and approve or revise budget plans. You can also generate an approved budget that can be used together with budget control. Budget planning is configurable, and supports a flexible chart of accounts and dimensions, custom-defined process configurations, and workflows. Additionally, budget planning lets you use Microsoft Excel to estimate costs to create scenarios, and provides standard reports and an analysis cube.</p>
<p>For more information, see <a href="budget-planning-overview.md">Budget planning overview</a> and the following white papers:</p>
<ul>
<li><p><a href="http://go.microsoft.com/fwlink/?linkid=272634%26clcid=0x409">Configure budget planning for Microsoft AX 2012 R2</a></p></li>
<li><p><a href="http://go.microsoft.com/fwlink/?linkid=272873%26clcid=0x409">Configure budget planning templates for Microsoft AX 2012 R2</a></p></li>
<li><p><a href="http://go.microsoft.com/fwlink/?linkid=272948%26clcid=0x409">Strategies for Using the Budget Planning Analysis Data Cube for Microsoft AX 2012 R2</a></p></li>
</ul></td>
</tr>
</tbody>
</table>


## What’s new in cumulative update 6 for Microsoft Dynamics AX 2012

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
<td><p><strong>Budget plan scenarios</strong> report</p></td>
<td><p>This report displays details about ledger accounts for up to five budget planning scenarios. The information is grouped and subtotaled by one, two, or three summary options.</p>
<p>For more information, see <a href="budget-plan-scenarios-report-budgetplanscenariosreport.md">Budget plan scenarios report (BudgetPlanScenariosReport)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Budgets plans can access main accounts that have a main account type of <strong>Total</strong>, or financial dimensions for which the <strong>Calculate total from multiple dimension values</strong> check box is selected.</p></td>
<td><p>When budget plans are generated and budget plan lines are entered, the following main accounts and financial dimensions can be accessed:</p>
<ul>
<li><p>Main accounts that have a main account type of <strong>Total</strong></p></li>
<li><p>Financial dimensions for which the <strong>Calculate total from multiple dimension values</strong> check box is selected.</p></li>
</ul>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="about-creating-a-budget-from-transaction-accounts-and-total-accounts.md">About creating a budget from transaction accounts and total accounts</a></p></li>
<li><p><a href="https://technet.microsoft.com/en-us/library/hh242667(v=ax.60)">Financial dimension values (form)</a></p></li>
<li><p><a href="https://technet.microsoft.com/en-us/library/hh209695(v=ax.60)">Main accounts - chart of accounts (form)</a></p></li>
<li><p><a href="key-tasks-create-and-process-budget-plans.md">Key tasks: Create and process budget plans</a></p></li>
<li><p><a href="generate-budget-plans-from-source-information.md">Generate budget plans from source information</a></p></li>
</ul></td>
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
<td><p>You can create a budget plan worksheet template for Excel by using a wizard in Microsoft Dynamics AX.</p></td>
<td><p>Each budget plan worksheet template is specific to a legal entity and an account structure.</p>
<p>For more information, see <a href="create-budget-plan-worksheet-templates-by-using-a-wizard.md">Create budget plan worksheet templates by using a wizard</a>.</p></td>
</tr>
<tr class="even">
<td><p>The budget allocation process is easier, because you can use ledger allocation rules for budgets.</p></td>
<td><p>The budget allocation process is easier, because you can use ledger allocation rules for budgets. When you run allocation for budget plan lines from the <strong>Budget plan</strong> form, you can select to use ledger allocation rules. You can also use ledger allocation rules when you use an allocation schedule. Additionally, you can now allocate budget amounts by using the basis method.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="about-allocation-rules.md">About allocation rules</a></p></li>
<li><p><a href="create-an-allocation-rule.md">Create an allocation rule</a></p></li>
<li><p><a href="set-up-budget-allocation-terms.md">Set up budget allocation terms</a></p></li>
<li><p><a href="about-budget-planning-configuration-and-setup.md">About budget planning configuration and setup</a></p></li>
<li><p><a href="key-tasks-create-and-process-budget-plans.md">Key tasks: Create and process budget plans</a></p></li>
<li><p><a href="key-tasks-configure-budget-planning-and-set-up-budget-planning-processes.md">Key tasks: Configure budget planning and set up budget planning processes</a></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Budget planning workflows can be set up so that they can’t be accidentally deleted or reset.</p></td>
<td><p>The <strong>Do not allow budget plans to be deleted</strong> and <strong>Do not allow budget plans to be reset</strong> options are added to the <strong>Budget planning workflows</strong> area in the <strong>Budget planning configuration</strong> form.</p>
<p>For more information, see <a href="https://technet.microsoft.com/en-us/library/jj677418(v=ax.60)">Budget planning configuration (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Budget planning workflows can be set up so that they require a parent budget plan.</p></td>
<td><p>The <strong>Require parent budget plan</strong> option is added to the <strong>Budget planning workflows</strong> area in the <strong>Budget planning configuration</strong> form.</p>
<p>For more information, see <a href="https://technet.microsoft.com/en-us/library/jj677418(v=ax.60)">Budget planning configuration (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>You can specify whether budget planning user groups (XDS policies) are used for budget planning. You can also specify the number of associated budget plan lines to include when budget plans are exported to Excel.</p></td>
<td><p>A new <strong>Parameters</strong> area is added to the <strong>Budget planning configuration</strong> form.</p>
<p>For more information, see <a href="about-budget-planning-configuration-and-setup.md">About budget planning configuration and setup</a> and <a href="https://technet.microsoft.com/en-us/library/jj677418(v=ax.60)">Budget planning configuration (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>You can view worksheet and justification documents from the <strong>Budget plan</strong> page in Enterprise Portal for Microsoft Dynamics AX.</p></td>
<td><p>The <strong>Worksheet</strong> and <strong>Justification</strong> buttons are added to the <strong>Budget plan</strong> page. The <strong>Export to Excel</strong> button is removed from the <strong>Budget plan</strong> form in Microsoft Dynamics AX, and from the <strong>Budget plan</strong> page in Enterprise Portal.</p>
<p>For more information, see <a href="https://technet.microsoft.com/en-us/library/jj677376(v=ax.60)">Budget plan (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>The process of creating a budget plan from an existing budget plan is enhanced.</p></td>
<td><p>You can aggregate the budget plan lines from the source budget lines to fiscal years, fiscal periods, or days in the destination budget plan. You can specify whether to copy the date of the target budget plan line date from the source budget plan. Finally, you can assign new financial dimensions for a budget plan that is based on an existing budget plan. The <strong>Aggregate total by</strong>, <strong>Historical</strong>, and <strong>New financial dimensions.</strong> options are added to the <strong>Generate budget plan from budget plan</strong> form.</p>
<p>For more information, see <a href="generate-budget-plans-from-source-information.md">Generate budget plans from source information</a> and <a href="https://technet.microsoft.com/en-us/library/jj677377(v=ax.60)">Generate budget plan from budget plan (form)</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3 Cumulative Update 8 with hotfix KB3047235

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
<td><p>Regulatory features updated</p></td>
<td><p>The <strong>Budget parameters</strong> form now includes check boxes for the public sector regulatory documents <strong>General budget reservations</strong> and <strong>Commitments (France)</strong>.</p>
<p>For more information, see <a href="about-general-budget-reservations-public-sector.md">About general budget reservations (Public sector)</a>.</p></td>
</tr>
<tr class="even">
<td><p>(Public sector) General budget reservation source document added for planned purchasing</p></td>
<td><p>General budget reservations are documents often used by public sector entities to set aside or reserve budgeted funds so that they are not available for other purposes. Typically these reservations are made before any vendors have been selected for the purchase.</p>
<p>For more information, see the following public sector topics:</p>
<ul>
<li><p><a href="about-general-budget-reservations-public-sector.md">About general budget reservations (Public sector)</a></p></li>
<li><p><a href="set-up-general-budget-reservation-rules-and-reservation-types-public-sector.md">Set up general budget reservation rules and reservation types (Public sector)</a></p></li>
<li><p><a href="add-modify-or-delete-a-general-budget-reservation-type-public-sector.md">Add, modify, or delete a general budget reservation type (Public sector)</a></p></li>
<li><p><a href="create-a-general-budget-reservation-public-sector.md">Create a general budget reservation (Public sector)</a></p></li>
<li><p><a href="view-modify-delete-or-cancel-a-general-budget-reservation-public-sector.md">View, modify, delete, or cancel a general budget reservation (Public sector)</a></p></li>
<li><p><a href="relieve-a-general-budget-reservation-public-sector.md">Relieve a general budget reservation (Public sector)</a></p></li>
<li><p><a href="finalize-a-general-budget-reservation-public-sector.md">Finalize a general budget reservation (Public sector)</a></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>(Public sector) General budget reservation workflow</p></td>
<td><p>For public sector, you can create a specific workflow for approving general budget reservations, and add a general budget reservation task to a purchase requisition workflow. For more information, see the following topics:</p>
<ul>
<li><p><a href="set-up-general-budget-reservation-workflows-public-sector.md">Set up general budget reservation workflows (Public sector)</a></p></li>
<li><p><a href="submit-a-general-budget-reservation-to-workflow-public-sector.md">Submit a general budget reservation to workflow (Public sector)</a></p></li>
<li><p><a href="create-a-purchase-order.md">Create a purchase order</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>(Public sector) Project accounting</p></td>
<td><p>For the public sector, if you use project accounting, you can include references to your project in general budget reservations. This can affect budgeting, committed costs, and funding-source reservations and consumption. For more information, see <a href="use-project-accounting-with-general-budget-reservations-public-sector.md">Use project accounting with general budget reservations (Public sector)</a>.</p></td>
</tr>
</tbody>
</table>


## More about budget control in AX 2012

In Microsoft Dynamics AX 2009, budgeting was primarily informational. AX 2012 provides budgeting and budget control solutions for public and private sector organizations. Budget register entries have replaced ledger budget tables, and are available in workflows that can be used for routing and review.

Budget control is a process that monitors a budget, and that can provide feedback about the availability of funds when budget register entries, accounting journals, and source documents such as purchase orders and invoices are entered. Although budgeting and budget control are important to any organization that wants to control spending, they are of particular interest to public sector organizations, because the budgets of these organizations are often enacted into law and cannot easily be exceeded or revised.

## Overview of budget control

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required</p></td>
<td><p>Optional. You might not use these features, depending on how you run your business.</p></td>
</tr>
<tr class="even">
<td><p>Feature areas affected</p></td>
<td><p>Enterprise Portal (Budget manager\analyst Role Center)</p>
<p>Budgeting</p>
<p>Public Sector</p></td>
</tr>
<tr class="odd">
<td><p>Stakeholders</p></td>
<td><p>Business decision makers</p>
<p>Technical decision makers</p>
<p>Implementation team members</p>
<p>Independent software vendors (ISVs)/developers</p>
<p>Partners</p></td>
</tr>
</tbody>
</table>


## New functionality in budget control

Budget register entries are now used to create budgets and provide an audit trail of budget-related activities. Budget register entries can be categorized by transaction type, such as amendment, transfer, and original budget. Therefore, you can quickly understand how a budget has changed. Workflows can guarantee that budget register entries undergo review. Existing AX 2009 ledger budget records are converted to budget register entries in AX 2012.

Budget control is based on the ledger for a legal entity. Users can define budget control to monitor budgets and provide feedback about the availability of funds. Users can also define the calculation that determines the budget funds that are available, and can specify dimensions and dimension values separately from a main account for budget control.

## Special considerations for budget control

There are three system configurations for budgeting and budget control:

  - Basic configuration provides budget register entries and workflows.

  - Advanced configuration adds budget control.

  - Public sector configuration adds apportionment and preliminary budget register entries.

## Comparison with budget control in AX 2009

Budgeting and budget control has changed considerably since AX 2009. AX 2012 includes changes to the following areas:

  - Budget manager/analyst Role Center

  - Financial dimensions for budgeting and budget control

  - Budget rate type and exchange rates

  - Budget models

  - Budget cycles

  - Budget control configuration

  - Budget control on source documents and accounting journals

  - Budget register entries

  - Workflow for budget register entries

  - Budget transfer rules

  - Budget transfers, allocations, and recurrences

  - Budget reports and inquiries

  - Web services interface for budget register entries

## Budget manager/analyst Role Center

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Perform typical tasks, and view frequently used forms and reports from a single location.</p></td>
<td><p>Not available</p></td>
<td><p>Budget managers can access the frequently used forms, FactBoxes, charts, reports, activities, and work items that they require to complete daily tasks and make informed decisions.</p></td>
<td><p>Key forms and information are consolidated into a single location.</p></td>
</tr>
</tbody>
</table>


## Financial dimensions for budgeting and budget control

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Select financial dimensions in the chart of accounts for budgeting.</p></td>
<td><p>Only a limited number of financial dimensions was provided.</p></td>
<td><p>Users can include or exclude specific dimensions, and even main accounts, for budgeting.</p></td>
<td><p>Budgeting and account number entry are easier.</p></td>
</tr>
<tr class="even">
<td><p>Select dimensions from the account structure in the chart of accounts for budget control.</p></td>
<td><p>The budget was always available at a main account level, and you had the option to add dimensions.</p></td>
<td><p>Users can specify dimension values to hold budget amounts, regardless of the specific usage of those dimension values in main accounts.</p></td>
<td><p>You have flexibility when you select specific dimensions, and even main accounts, for budget control.</p></td>
</tr>
</tbody>
</table>


## Budget rate type and exchange rates

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create a budget rate type, and associate exchange rates.</p></td>
<td><p>Not available</p></td>
<td><p>Users can define currency pairs and associate exchange rates with the default budget rate type for the ledger.</p></td>
<td><p>It is easier to create and maintain exchange rates that are used specifically for budgets.</p></td>
</tr>
</tbody>
</table>


## Budget models

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Identify a budget by associating it with a budget model.</p></td>
<td><p>Budget models were used to identify budgets.</p></td>
<td><p>Budget models can be used to identify budgets.</p></td>
<td><p>It is easier to categorize budget register entries, identify budgets, and assign budget cycles.</p></td>
</tr>
<tr class="even">
<td><p>Use budget models to structure ledger budgets and develop budget forecasts.</p></td>
<td><p>Budget models were used for simulations and forecasts.</p></td>
<td><p>Budget models can be used for simulations and budget forecasts.</p></td>
<td><p>You can run simulations and compare budget forecasts.</p></td>
</tr>
<tr class="odd">
<td><p>Build complex budget models by using submodels for planning and reporting.</p></td>
<td><p>Budget models and submodels were used to aggregate budget amounts.</p></td>
<td><p>Submodels can represent departments or various other organizational entities.</p></td>
<td><p>Budget planning is flexible. You also have flexibility when you produce reports that have consolidated balances.</p></td>
</tr>
</tbody>
</table>


## Budget cycles

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create a budget cycle time span that has one or more budget cycles that can be used across legal entities.</p></td>
<td><p>Not available</p></td>
<td><p>Users can map the budget cycle time span to a fiscal year or specify the number of accounting periods that each budget cycle represents.</p></td>
<td><p>Budget control can be implemented for part of a fiscal year, or over one or more fiscal years.</p></td>
</tr>
</tbody>
</table>


## Budget control configuration

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Define parameters and dimensions for budget control.</p></td>
<td><p>Not available</p></td>
<td><p>Dimensions and default parameters for budget control are defined in one location.</p></td>
<td><p>Budget control options are centralized.</p></td>
</tr>
<tr class="even">
<td><p>Select the default over-budget permissions for user groups.</p></td>
<td><p>Not available</p></td>
<td><p>Users can assign options for user groups to allow or prevent over-budget processing of source documents and accounting journals.</p></td>
<td><p>The way that over-budget processing is handled for specific user groups is flexible.</p></td>
</tr>
<tr class="odd">
<td><p>Define the calculation for the budget funds that are available.</p></td>
<td><p>Not available</p></td>
<td><p>Users can determine the amounts that are added and subtracted for the calculation that determines the available budgets funds.</p></td>
<td><p>It is easier to customize the calculation for available budget funds.</p></td>
</tr>
<tr class="even">
<td><p>Determine the source documents and accounting journals for budget control.</p></td>
<td><p>Not available</p></td>
<td><p>Budget checking can be used for source documents and account journals at the header level or the level of the line item entry.</p></td>
<td><p>The processing of specified source documents and accounting journals is controlled.</p></td>
</tr>
<tr class="odd">
<td><p>Assign budget models to budget cycles and budget cycle time spans.</p></td>
<td><p>Not available</p></td>
<td><p>Users can implement one or more budget models and budget cycles. Therefore, for example, a capital expenditure budget model and an operating budget model can be used for budget control.</p></td>
<td><p>You have flexibility when you implement budgets.</p></td>
</tr>
<tr class="even">
<td><p>Define budget control rules.</p></td>
<td><p>Not available</p></td>
<td><p>Users can define rules for specific dimensions, over-budget permissions, and parameters.</p></td>
<td><p>You have flexibility when you define dimension values and parameters for budget control.</p></td>
</tr>
<tr class="odd">
<td><p>Select main accounts for budget control.</p></td>
<td><p>Not available</p></td>
<td><p>When a main account is not selected as a budget control dimension, users can select specific main accounts to use when budget control rules are applied.</p></td>
<td><p>It is easier to implement budget control for dimensions and main accounts.</p></td>
</tr>
<tr class="even">
<td><p>Define budget groups.</p></td>
<td><p>Not available</p></td>
<td><p>Users can set up budget checking for pooled dimensions and accounts.</p></td>
<td><p>You have flexibility when you implement budget control for dimensions and dimension values.</p></td>
</tr>
<tr class="odd">
<td><p>Modify, activate, restore, and turn on the budget control configuration.</p></td>
<td><p>Not available</p></td>
<td><p>Users can control the active budget control configuration and modify a draft version.</p></td>
<td><p>It is easier to implement and administer budget control.</p></td>
</tr>
</tbody>
</table>


## Budget control on source documents and accounting journals

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Run budget checks when line items are entered, or postpone the budget check until an action, such as an approval, is taken on the source document.</p></td>
<td><p>Not available</p></td>
<td><p>Source documents include purchase requisitions, purchase orders, vendor invoices, travel requisitions, and expense reports.</p></td>
<td><p>Over-budget processing is controlled or prevented.</p></td>
</tr>
<tr class="even">
<td><p>Run budget checks when each general journal line is entered, or postpone the budget check until the journal is posted.</p></td>
<td><p>Not available</p></td>
<td><p>Accounting journals include daily journals, allocation journals, project expense journals, and fixed asset journals.</p></td>
<td><p>Over-budget processing is controlled or prevented.</p></td>
</tr>
</tbody>
</table>


## Budget register entries

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Use budget register entries to create and manage budgets.</p></td>
<td><p>Ledger budget tables provided static storage for budget records.</p></td>
<td><p>Users can define one or more codes for the following budget transaction types: original budget, transfer, amendment, encumbrance, pre-encumbrance, carry-forward, project, fixed assets, demand forecast, supply forecast, apportionment (Public sector), and preliminary budget (Public sector).</p></td>
<td><p>Users can track, categorize, and audit budget register entries.</p></td>
</tr>
<tr class="even">
<td><p>Use subledger budget transaction types when budget forecasts are transferred to the general ledger.</p></td>
<td><p>Users could not track the transfer of budgets from subledgers to the general ledger.</p></td>
<td><p>Users can transfer forecasts for projects, fixed assets, demand forecasts (inventory sales), and supply forecasts (inventory purchasing).</p></td>
<td><p>It is easier to transfer forecasts ledgers.</p></td>
</tr>
<tr class="odd">
<td><p>For the public sector, use preliminary budgets and apportionment budgets.</p></td>
<td><p>Not available</p></td>
<td><p>Users can define codes for apportionment and preliminary budget register entries.</p></td>
<td><p>Public sector organizations can use preliminary budgets for budget control and can allocate part of an approved budget.</p></td>
</tr>
<tr class="even">
<td><p>Create posting definitions for budget register entries.</p></td>
<td><p>Not available</p></td>
<td><p>When budget register entries are processed, posting definitions can create ledger entries for multiple accounts.</p></td>
<td><p>Budget register entries can be automatically posted to a ledger.</p></td>
</tr>
</tbody>
</table>


## Workflow for budget register entries

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set up budget transaction workflows.</p></td>
<td><p>Not available</p></td>
<td><p>Budget register entries that are associated with a workflow are automatically routed for review.</p></td>
<td><p>It is easier to route and review budget register entries.</p></td>
</tr>
</tbody>
</table>


## Budget transfer rules

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Define budget transfer rules.</p></td>
<td><p>Not available</p></td>
<td><p>Budget transfer rules determine when budget transfers between dimensions can occur.</p></td>
<td><p>Budget transfers are controlled.</p></td>
</tr>
</tbody>
</table>


## Budget transfers, allocations, and recurrences

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Transfer budget amounts.</p></td>
<td><p>Not available</p></td>
<td><p>When budget control is turned on, users can transfer budget amounts while they enter other budget register entries. Alternatively, users can transfer budget amounts from source documents and accounting journals.</p></td>
<td><p>You have flexibility when you transfer budget amounts.</p></td>
</tr>
<tr class="even">
<td><p>Allocate budget funds by dimension or period.</p></td>
<td><p>Users could allocate funds by period or dimension only during budget entry.</p></td>
<td><p>Users can spread a budget amount across dimension values or fiscal periods by using a single transaction.</p></td>
<td><p>It is easier to create budget allocation transactions.</p></td>
</tr>
<tr class="odd">
<td><p>Enter a recurrence pattern for budget register entries.</p></td>
<td><p>Users could create recurring budget expenses.</p></td>
<td><p>Users can create recurring budget register entries.</p></td>
<td><p>It is easier to create recurring budget register entries.</p></td>
</tr>
</tbody>
</table>


## Budget reports and inquiries

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Use reports and inquiries to view budget register entries, budget control statistics, and budget funds.</p></td>
<td><p>The <strong>Actual versus budget</strong> report was available.</p></td>
<td><p>Users can set parameters to sort and categorize budget data in the following reports and inquires:</p>
<ul>
<li><p><strong>Budget funds available</strong> report</p></li>
<li><p><strong>Actual versus budget</strong> report and inquiry</p></li>
<li><p><strong>Budget details</strong> report</p></li>
<li><p><strong>Budget control statistics</strong> inquiry</p></li>
</ul></td>
<td><p>Users can view, analyze, track, and audit available budget amounts, actual versus budgeted expenditures, budget register entries, and budget control statistics.</p></td>
</tr>
</tbody>
</table>


## Web services interface for budget register entries

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create, retrieve, and update budget register entries from third-party applications.</p></td>
<td><p>Not available</p></td>
<td><p>Users can generate and import the XML file for budget register entries.</p></td>
<td><p>Budget register entries that were created by using external budget formulation tools can be used.</p></td>
</tr>
</tbody>
</table>


## More information

For more information about budgeting and budget control, see the white papers [Implementing the Budget Control Framework for Microsoft Dynamics AX 2012 Applications](http://go.microsoft.com/fwlink/?linkid=213130%26clcid=0x409) and [Implementing Budgeting for Microsoft Dynamics AX 2012 Applications](http://go.microsoft.com/fwlink/?linkid=213129%26clcid=0x409).

## More about budget planning in AX 2012 R2

AX 2012 R2 adds budget planning to the **Budgeting** module that was introduced in AX 2012.

Budget planning is the process of preparing the budgets that will be adopted by an organization. Private sector and public sector organizations can configure budget planning, and set up their own budget planning processes that are secure, flexible, and easy to use. By using budget planning, you can perform the following tasks:

  - Associate budget planning processes with budget cycles, ledgers, and organization hierarchies.

  - Analyze and update budget plans by using multiple scenarios. You can then automatically route the budget plans together with worksheets, justifications, and attachments for reviews and approvals.

  - Consolidate multiple budget plans at one level of the organization into a single parent budget plan at a higher level in the organization. You can also develop a single budget plan at a high level in the organization and allocate the budget to lower levels of the organization.

## Overview of budget planning

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required</p></td>
<td><p>Optional. You might not use these features, depending on how you run your business.</p></td>
</tr>
<tr class="even">
<td><p>Feature areas affected</p></td>
<td><p>Human resources</p>
<p>General ledger</p>
<p>Fixed assets</p>
<p>Enterprise Portal</p>
<p>Office Add-ins for Microsoft Dynamics AX</p>
<p>Public sector</p></td>
</tr>
<tr class="odd">
<td><p>Stakeholders</p></td>
<td><p>Business decision makers</p>
<p>Technical decision makers</p>
<p>Implementation team members</p>
<p>ISVs/developers</p>
<p>Partners</p></td>
</tr>
</tbody>
</table>


## New functionality in budget planning

Budget planning builds on key features that are introduced in AX 2012, such as the role-based and data security models, the financial dimension framework, account structures, and account rules. Budget planning adds budget planning advanced rules and additional tasks and elements to workflow. You can configure workflows to review and approve budget plans, and to integrate the stages in your budget planning processes with the business requirements of your budget planning organization.

Budget planning is integrated with other AX 2012 R2 modules, so that you can bring in information from previous budgets, actual expenditures, fixed assets, and human resources. Budget planning is also integrated with Excel and Microsoft Word, so that you can use these tools to work with your budgeting data. For example, a budget manager can import a department’s budget request to an Excel worksheet from a budget plan scenario. The data can be analyzed, updated, charted, and then published back to the budget plan lines, where the data can be routed for approval.

## Special considerations for budget planning

The budget manager must be assigned to a role that has permission to create and maintain organization hierarchies. The budget manager should either create an organization hierarchy that has a **Budget planning** purpose or assign the **Budget planning** purpose to an existing organization hierarchy.

Workflows route the budget plans through the organization, based on the workers in the budgeting organization hierarchy. Users who work with budget planning must be associated with workers whose positions report to an organization unit in the budget planning organization hierarchy. If users outside the budget planning organization hierarchy have to review budget plans, these users must be assigned to a budget planning user group that can be associated with the budget plan that they have to review.

Office Add-ins must be configured and enabled, and a template author must build the Excel and Word templates. The templates are used to structure the data for the worksheets and justifications by using the fields that are available through the Budget planning web service. For Enterprise Portal, network locations that have the appropriate security must be available for the templates, attachments, worksheets, and justifications.

## Comparison with budget planning in AX 2009

This feature was not available in AX 2009. AX 2012 R2 includes the following major changes:

  - Financial dimensions for budget planning

  - Budget planning and Office Add-ins

  - Budget planning configuration

  - Budget planning workflow configuration

  - Proposed projects and proposed fixed assets

  - Budget planning processes

  - Generating budget plans from source data

  - Budget plan data entry

  - Budget planning reports

  - Budget planning data cubes

  - Budget planning web service

## Financial dimensions for budget planning

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Select financial dimensions from the chart of accounts for budgeting and budget planning.</p></td>
<td><p>Not available</p></td>
<td><p>Include or exclude specific dimensions, and even main accounts, for budgeting and budget planning.</p></td>
<td><p>Budget planning and account number entry are easier.</p></td>
</tr>
<tr class="even">
<td><p>Use budget planning advanced rules to select financial dimensions outside the chart of accounts for budget planning.</p></td>
<td><p>Not available</p></td>
<td><p>Specify advanced rules and advanced rule structures to support and validate financial dimensions that are not part of the general ledger account structure.</p></td>
<td><p>You have flexibility when you select financial dimensions for budget planning.</p></td>
</tr>
</tbody>
</table>


## Budget planning and Office Add-ins

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create templates for Excel worksheets and Word justifications.</p></td>
<td><p>Not available</p></td>
<td><p>Create templates for worksheets and justifications by using the fields from the Budget planning web service.</p></td>
<td><p>You can control the data that you see in worksheets and justifications for different budget planning stages and scenarios.</p></td>
</tr>
<tr class="even">
<td><p>View and update budget plan data by using Excel.</p></td>
<td><p>Not available</p></td>
<td><p>Use the add-in for Excel to view, analyze, chart, and update budget planning data.</p></td>
<td><p>You can use familiar productivity tools to work with budget planning data.</p></td>
</tr>
<tr class="odd">
<td><p>View budget plan data by using Word.</p></td>
<td><p>Not available</p></td>
<td><p>Use the add-in for Word to view budget planning data.</p></td>
<td><p>You can use familiar productivity tools to work with budget planning data.</p></td>
</tr>
</tbody>
</table>


## Budget planning configuration

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create budget planning scenarios to define categories of data.</p></td>
<td><p>Not available</p></td>
<td><p>Develop and refine scenarios to support monetary and other units of measure. These units of measure include quantity.</p></td>
<td><p>You have control over the analysis, review, update, and approval of budget planning estimates.</p></td>
</tr>
<tr class="even">
<td><p>Create budget planning stages to define the steps that a budget plan must follow.</p></td>
<td><p>Not available</p></td>
<td><p>Create the stages for the budget planning process.</p></td>
<td><p>You can customize the budget planning process to match your organization hierarchy and business requirements.</p></td>
</tr>
<tr class="odd">
<td><p>Create budget planning workflows to model review processes that meet your business requirements.</p></td>
<td><p>Not available</p></td>
<td><p>Define the order of the stages in the budget planning process, and associate the stages with a workflow configuration ID.</p></td>
<td><p>This feature provides flexibility when you define when budget planning activities occur.</p></td>
</tr>
<tr class="even">
<td><p>Define scenario constraints to control when budget plan scenarios can be viewed and updated.</p></td>
<td><p>Not available</p></td>
<td><p>Determine who can view and change the budget plan estimates at the different stages in the budget planning process.</p></td>
<td><p>This feature provides flexibility and security when you view and update budget planning estimates.</p></td>
</tr>
<tr class="odd">
<td><p>Define the schedules and budget planning stages for allocations that can be made automatically during workflow processing.</p></td>
<td><p>Not available</p></td>
<td><p>Use schedules and stages to automatically allocate estimates between budget planning scenarios.</p></td>
<td><p>Budget planning allocations are automated.</p></td>
</tr>
<tr class="even">
<td><p>Create budget plan priorities to support the development of budget plans by priority or objective.</p></td>
<td><p>Not available</p></td>
<td><p>Create priorities to define categories for evaluating budget plans.</p></td>
<td><p>You can group and evaluate budget plans by priority.</p></td>
</tr>
<tr class="odd">
<td><p>Identify server and network folder locations for budget plan attachments.</p></td>
<td><p>Not available</p></td>
<td><p>Specify folder locations for budget plan attachments.</p></td>
<td><p>The location of budget plan attachments is centralized.</p></td>
</tr>
<tr class="even">
<td><p>Provide Office Add-ins support for the worksheets and justifications.</p></td>
<td><p>Not available</p></td>
<td><p>Select the template files to use for the worksheets and associated justifications.</p></td>
<td><p>You can provide multiple templates for budget planning processes.</p></td>
</tr>
</tbody>
</table>


## Budget planning workflow configuration

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set up budget planning workflows for reviews and approvals.</p></td>
<td><p>Not available</p></td>
<td><p>Automatically route budget plans to the workers in the budget planning organization for reviews and approvals.</p></td>
<td><p>Budget plans can be routed and reviewed efficiently and securely.</p></td>
</tr>
<tr class="even">
<td><p>Set up budget planning workflows for business requirements.</p></td>
<td><p>Not available</p></td>
<td><p>Use stage transitions to automatically route budget plans through the planning stages that you defined.</p></td>
<td><p>Budget planning processes can be customized to match your organization hierarchy and business requirements.</p></td>
</tr>
<tr class="odd">
<td><p>Set up budget planning workflows to automatically create or activate associated budget plans.</p></td>
<td><p>Not available</p></td>
<td><p>Parent budget plans can automatically allocate budget to associated budget plans. Alternatively, associated budget plans can automatically roll up budget estimates to a parent budget plan.</p></td>
<td><p>You have flexibility for various approaches to budget planning.</p></td>
</tr>
<tr class="even">
<td><p>Set up budget planning workflows to automatically perform allocations.</p></td>
<td><p>Not available</p></td>
<td><p>Use allocation schedules and stage allocations to automatically update allocations for budget planning scenarios.</p></td>
<td><p>Budget planning allocations are flexible and efficient.</p></td>
</tr>
</tbody>
</table>


## Proposed projects and proposed fixed assets

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create proposed projects for budget planning.</p></td>
<td><p>Not available</p></td>
<td><p>You can use a list of proposed projects for budget planning.</p></td>
<td><p>A budget plan line can include a proposed project.</p></td>
</tr>
<tr class="even">
<td><p>Create proposed fixed assets for budget planning.</p></td>
<td><p>Not available</p></td>
<td><p>You can use a list of proposed assets for budget planning.</p></td>
<td><p>A budget plan line can include a proposed asset.</p></td>
</tr>
</tbody>
</table>


## Budget planning processes

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create budget planning processes that are based on budget cycles, ledgers, and organizations.</p></td>
<td><p>Not available</p></td>
<td><p>Select the budget cycle, ledger, and organization for each budget planning process.</p></td>
<td><p>Budget planning is integrated with existing budgeting, financial, and organizational features.</p></td>
</tr>
<tr class="even">
<td><p>Set up automatic translations for budget planning process names and descriptions.</p></td>
<td><p>Not available</p></td>
<td><p>Translate the names and descriptions that are used in budget planning processes.</p></td>
<td><p>In multi-country organizations, the usability of budget planning processes is improved.</p></td>
</tr>
<tr class="odd">
<td><p>Select the justification template and the attachments folder for each budget planning process.</p></td>
<td><p>Not available</p></td>
<td><p>Justification templates can define the narrative requirements that are associated with the submission of budget plans. The attachments folder provides the location for attachments and templates that are associated with the budget planning process.</p></td>
<td><p>You can control, from a centralized location, how budget planning justifications and attachments are used and stored.</p></td>
</tr>
<tr class="even">
<td><p>Select the organization hierarchy, and associate its responsibility centers with budget planning workflows.</p></td>
<td><p>Not available</p></td>
<td><p>Select the budget planning workflow and the budgeting workflow configuration ID for each responsibility center in the organization hierarchy.</p></td>
<td><p>You can customize the budget planning process to match your organization hierarchy and business requirements.</p></td>
</tr>
<tr class="odd">
<td><p>For each stage of a budget planning workflow, define the type of access that users have to budget plans.</p></td>
<td><p>Not available</p></td>
<td><p>For each budget planning stage, define the following activities:</p>
<ul>
<li><p>Associate budget plans with parent budget plans.</p></li>
<li><p>Add budget plan lines.</p></li>
<li><p>Modify budget plan lines.</p></li>
<li><p>Use worksheet and justification templates files.</p></li>
</ul></td>
<td><p>You can control what users can view and modify at each stage of a budget planning workflow.</p></td>
</tr>
<tr class="even">
<td><p>In a list of all the priorities, select the priorities that can be applied to the budget plans for a specific budget planning process.</p></td>
<td><p>Not available</p></td>
<td><p>Responsibility centers can work with and evaluate a prioritized list of budget plans.</p></td>
<td><p>You can budget by priority or objective.</p></td>
</tr>
<tr class="odd">
<td><p>Control the activation and completion of the budget planning process.</p></td>
<td><p>Not available</p></td>
<td><p>Activate, deactivate, and complete budget planning processes.</p></td>
<td><p>You can control, from a centralized location, the administration of budget planning processes.</p></td>
</tr>
</tbody>
</table>


## Generating budget plans from source data

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Generate budget plans from the general ledger.</p></td>
<td><p>Not available</p></td>
<td><p>Transfer historical and current data from the general ledger to a budget plan scenario.</p></td>
<td><p>Budget planning is integrated with General ledger.</p></td>
</tr>
<tr class="even">
<td><p>Generate budget plans from forecast positions.</p></td>
<td><p>Not available</p></td>
<td><p>Transfer forecast position data to a budget plan scenario.</p></td>
<td><p>Budget planning is integrated with Human resources.</p></td>
</tr>
<tr class="odd">
<td><p>Generate budget plans from fixed assets.</p></td>
<td><p>Not available</p></td>
<td><p>Transfer fixed asset budgets to a budget plan scenario.</p></td>
<td><p>Budget planning is integrated with Fixed assets.</p></td>
</tr>
<tr class="even">
<td><p>Generate budget plans from other budget plans.</p></td>
<td><p>Not available</p></td>
<td><p>Transfer budget plan data from one budget planning process to a budget plan in another process.</p></td>
<td><p>It is easier to create new budget plans from existing or prior budget plans.</p></td>
</tr>
</tbody>
</table>


## Budget plan data entry

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create budget plans.</p></td>
<td><p>Not available</p></td>
<td><p>When you can create budget plans, you can specify the following information:</p>
<ul>
<li><p>Budget planning processes</p></li>
<li><p>Responsibility centers</p></li>
<li><p>Parent budget plans</p></li>
<li><p>Budget planning user groups</p></li>
<li><p>Budget plan priority and rank</p></li>
<li><p>Worksheets, justifications, and attachments</p></li>
</ul></td>
<td><p>Creating budget plans is efficient and flexible.</p></td>
</tr>
<tr class="even">
<td><p>Work with budget plan lines.</p></td>
<td><p>Not available</p></td>
<td><p>You can work with budget plan lines based on the following information:</p>
<ul>
<li><p>Scenarios</p></li>
<li><p>Forecast positions</p></li>
<li><p>Account structures and dimension values</p></li>
<li><p>Quantities and unit prices</p></li>
<li><p>Currencies and amounts</p></li>
<li><p>Allocations by dimension or period</p></li>
</ul></td>
<td><p>Working with budget plan lines is effective and easy.</p></td>
</tr>
<tr class="odd">
<td><p>Work with budget plan line details.</p></td>
<td><p>Not available</p></td>
<td><p>You can work with budget plan lines details based on the following information:</p>
<ul>
<li><p>Projects or proposed projects</p></li>
<li><p>Assets or proposed assets</p></li>
<li><p>Positions</p></li>
</ul></td>
<td><p>Budget plan line details can be easily integrated with other modules.</p></td>
</tr>
<tr class="even">
<td><p>Use FactBoxes to view information about the budget plan and budget plan lines.</p></td>
<td><p>Not available</p></td>
<td><p>Users can view the following FactBoxes:</p>
<ul>
<li><p>Budget plan preparer</p></li>
<li><p>Estimates by amount</p></li>
<li><p>Estimates by unit</p></li>
<li><p>Associated budget plans</p></li>
<li><p>Line estimates by scenario</p></li>
<li><p>Budget plan documents</p></li>
</ul></td>
<td><p>You can quickly find and preview budget plan data.</p></td>
</tr>
<tr class="odd">
<td><p>Generate budget register entries from budget plans.</p></td>
<td><p>Not available</p></td>
<td><p>Generate budget register entries from budget plan scenarios.</p></td>
<td><p>It is easier to create a draft budget from the approved budget plan.</p></td>
</tr>
<tr class="even">
<td><p>Work with budget plans from Enterprise Portal.</p></td>
<td><p>Not available</p></td>
<td><p>Enterprise Portal users can create, review, update, and approve budget plans.</p></td>
<td><p>Budget planning can be performed by users who do not have full access to AX 2012.</p></td>
</tr>
</tbody>
</table>


## Budget planning reports

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Use reports to view forecast positions, amounts, account totals, and budget register entries by budget plan.</p></td>
<td><p>Not available</p></td>
<td><p>Users can set parameters to sort and categorize budget planning data for the following reports:</p>
<ul>
<li><p>Forecast positions by budget plan</p></li>
<li><p>Budget plan list</p></li>
<li><p>Budget plan account totals</p></li>
<li><p>Budget plan audit</p></li>
</ul></td>
<td><p>Users can view, analyze, track, and audit forecast positions, amounts, account totals, and budget register entries by budget plan.</p></td>
</tr>
</tbody>
</table>


## Budget planning data cubes

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>View and analyze detailed budget planning information.</p></td>
<td><p>Not available</p></td>
<td><p>Specific measures, calculated measures, and all budget plan attributes are available in the budget planning cubes.</p></td>
<td><p>Budget planning analysis is quicker and more detailed.</p></td>
</tr>
</tbody>
</table>


## Budget planning web service

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create, retrieve, and update budget planning data from external applications.</p></td>
<td><p>Not available</p></td>
<td><p>When budget planning is configured, you can create templates for worksheets and justifications by using the budget planning fields.</p></td>
<td><p>External productivity and budget formulation tools can be used to work with budget plan data.</p></td>
</tr>
</tbody>
</table>


## More information

For more detailed information about budget planning, see the following white papers:

  - [Configuring budget planning for Microsoft Dynamics AX 2012 R2](http://go.microsoft.com/fwlink/?linkid=272634%26clcid=0x409)

  - [Configuring Budget Plan Templates for Microsoft Dynamics AX 2012 R2](http://go.microsoft.com/fwlink/?linkid=272873%26clcid=0x409)

  - [Strategies for using the Budget planning analysis data cube in Microsoft Dynamics AX 2012 R2](http://go.microsoft.com/fwlink/?linkid=272948%26clcid=0x409)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

