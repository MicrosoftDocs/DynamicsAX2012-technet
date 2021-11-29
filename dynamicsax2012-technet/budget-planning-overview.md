---
title: Budget planning overview
TOCTitle: Budget planning overview
ms:assetid: 1ba682ec-6ab9-4929-9b03-f4eb1c6cec20
ms:mtpsurl: https://technet.microsoft.com/library/JJ677328(v=AX.60)
ms:contentKeyID: 49384102
author: Khairunj
ms.date: 11/19/2014
mtps_version: v=AX.60
f1_keywords:
- budgets
- budget
- budget plan
- budget planning
- plan budget
audience: Application User
ms.search.region: Global
---

# Budget planning overview 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic introduces budget planning and contains information to help you configure budget planning and set up budget planning processes.

## About budget planning

Budget planning is the process of preparing the budgets that are implemented by an organization. Private sector and public sector organizations can configure budget planning, and then set up budget planning processes to meet their organization’s policies, procedures, and requirements for budget preparation. You can use budget planning to perform the following tasks:

  - Associate budget planning processes with budget cycles, ledgers, and organization hierarchies.

  - Analyze and update budget plans by using multiple scenarios. You can automatically route the budget plans, together with worksheets, justifications, and attachments, for review and approval.

  - Consolidate multiple budget plans from a lower level of the organization into a single parent budget plan at a higher level in the organization. You can also develop a single budget plan at a higher level of the organization and allocate the budget to lower levels of the organization.

When you use budget planning, budget planning rules are added to advanced rules and account structures, and budget planning tasks and elements are added to Budgeting workflows. The **Budget planning** and **Security** purposes are also added to organization hierarchies.

Budget planning is integrated with other modules, so you can bring in information from previous budgets, actual expenditures, fixed assets, and human resources. Budget planning is also integrated with Microsoft Excel and Microsoft Word, so that you can use these tools to work with the budget planning data. For example, a budget manager can import a department’s budget request into an Excel worksheet from a budget plan scenario. The data can be analyzed, updated, and charted in the worksheet, and then published back to the budget plan lines.

## Budget planning requirements

The **Budget** configuration key for basic budgeting and the **Budget planning configuration key** must be enabled. The **Budget control** configuration key is optional but is typically enabled. For more information, see [Configuration keys](https://technet.microsoft.com/library/hh227464\(v=ax.60\)) and “Budgeting configuration keys” in [Setup overview: basic budgeting and budget control](setup-overview-basic-budgeting-and-budget-control.md).

Before you configure budget planning and set up budget planning processes, you must set up basic budgeting. You must also set up budget control if you’re using budget control. When you set up basic budgeting, include the financial dimensions, number sequences, budget cycles, and currency exchange rates for budget planning. For overview information, see [Setup overview: basic budgeting and budget control](setup-overview-basic-budgeting-and-budget-control.md). For a list of topics about basic budgeting, see [Setting up basic budgeting](setting-up-basic-budgeting.md).

The following table describes the information that you must compile before you configure budget planning and set up budget planning processes.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Information to compile</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>The financial dimensions that are required for budget planning, but that are not available in the chart of accounts.</p></td>
<td><p>For more information, see <a href="https://technet.microsoft.com/library/jj677446(v=ax.60)">Budget planning rules (form)</a> and <a href="create-advanced-account-structures-and-rules-for-budget-planning.md">Create advanced account structures and rules for budget planning</a>.</p></td>
</tr>
<tr class="even">
<td><p>The departments, business units, and cost centers in the organization hierarchy.</p></td>
<td><p>The budget manager must be assigned to a role that has permission to create and maintain organization hierarchies.</p>
<p>For information about how to assign the <strong>Budget planning</strong> purpose to an organization hierarchy, see <a href="create-or-modify-an-organization-hierarchy.md">Create or modify an organization hierarchy</a>.</p>
<div class="alert">

> [!NOTE]
> <P>Only one organization hierarchy can be assigned to a budget planning process.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>The users who are outside the budget planning organization hierarchy or not associated with an organization unit in the hierarchy, but who must work with budget plans.</p></td>
<td><p>Users who are outside the budgeting planning organization hierarchy can be assigned to a budget planning user group. This user group can then be associated with the budget plan that the users work with. For more information, see <a href="https://technet.microsoft.com/library/aa576701(v=ax.60)">User groups (form)</a>, <a href="manage-user-groups.md">Manage user groups</a>, and <a href="key-tasks-create-and-process-budget-plans.md">Key tasks: Create and process budget plans</a>.</p></td>
</tr>
<tr class="even">
<td><p>The allocation, stage transition, review, and approval requirements for the Budgeting workflows.</p></td>
<td><p>For more information, see <a href="about-budget-planning-configuration-and-setup.md">About budget planning configuration and setup</a> and <a href="set-up-budgeting-workflows.md">Set up Budgeting workflows</a>.</p></td>
</tr>
<tr class="odd">
<td><p>The budget planning stages and workflows for the budget planning processes.</p></td>
<td><p>For more information, see <a href="about-budget-planning-configuration-and-setup.md">About budget planning configuration and setup</a> and <a href="key-tasks-configure-budget-planning-and-set-up-budget-planning-processes.md">Key tasks: Configure budget planning and set up budget planning processes</a>.</p></td>
</tr>
<tr class="even">
<td><p>The access that users must have to view, modify, and add budget plan data.</p></td>
<td><p>For more information, see <a href="about-budget-planning-configuration-and-setup.md">About budget planning configuration and setup</a> and <a href="key-tasks-configure-budget-planning-and-set-up-budget-planning-processes.md">Key tasks: Configure budget planning and set up budget planning processes</a>.</p>
<p>For information about how to assign the <strong>Security</strong> purpose to an organization hierarchy, see <a href="organization-hierarchies.md">Organization hierarchies</a>, <a href="configure-budget-planning-security.md">Configure budget planning security</a>, and <a href="configuring-budget-planning-for-microsoft-dynamics-ax-2012-r2.md">Configuring Budget Planning for Microsoft Dynamics AX 2012 R2</a>.</p></td>
</tr>
<tr class="odd">
<td><p>The templates for Office Add-ins for Microsoft Dynamics AX for the data that you want to see in the worksheets and justifications.</p></td>
<td><p>A template author must create the Excel and Word templates that structure the data for the worksheets and justifications. The fields for the templates are available through the Budget planning web service. For more information, see <a href="create-budget-plan-templates-manually.md">Create budget plan templates manually</a> and <a href="create-budget-plan-worksheet-templates-by-using-a-wizard.md">Create budget plan worksheet templates by using a wizard</a>.</p></td>
</tr>
<tr class="even">
<td><p>The folder locations for attachments, templates, worksheets, and justifications.</p></td>
<td><p>For more information, see <a href="about-budget-planning-configuration-and-setup.md">About budget planning configuration and setup</a> and <a href="key-tasks-configure-budget-planning-and-set-up-budget-planning-processes.md">Key tasks: Configure budget planning and set up budget planning processes</a>.</p></td>
</tr>
<tr class="odd">
<td><p>If you use Enterprise Portal for Microsoft Dynamics AX, the security and permissions for network folders and files.</p></td>
<td><p>The appropriate user accounts must have access to the documents on the network. For more information, see <a href="create-service-accounts.md">Create service accounts</a>.</p></td>
</tr>
<tr class="even">
<td><p>The types of data in the budget plan scenarios, such as monetary or quantity.</p></td>
<td><p>For more information, see <a href="about-budget-planning-configuration-and-setup.md">About budget planning configuration and setup</a> and <a href="key-tasks-configure-budget-planning-and-set-up-budget-planning-processes.md">Key tasks: Configure budget planning and set up budget planning processes</a>.</p></td>
</tr>
<tr class="odd">
<td><p>The data in the budget planning scenarios that must be entered manually or allocated.</p></td>
<td><p>For more information, see <a href="about-budget-planning-configuration-and-setup.md">About budget planning configuration and setup</a> and <a href="about-budget-plans.md">About budget plans</a>.</p></td>
</tr>
<tr class="even">
<td><p>The budget planning data that must be generated from sources such as previous budgets, actual expenditures, fixed assets, and forecast positions.</p></td>
<td><p>For more information, see <a href="generate-budget-plans-from-source-information.md">Generate budget plans from source information</a>.</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>We recommend that you use Management Reporter for Microsoft Dynamics ERP to create, maintain, deploy, and view financial reports that include budget planning data. Management Reporter lets you design financial reports based on ledger accounts and financial dimensions, drill down to transaction-level detail, and use web-based report viewing. For more information about how to print financial reports by using Management Reporter, see <A href="https://go.microsoft.com/fwlink/?linkid=324762">Management Reporter for Microsoft Dynamics ERP</A>.</P>
> <P>You can use Management Reporter to report on budget planning data only if you have rollup 4 or a later version of Management Reporter 2012 installed.</P>



## See also

[Setup overview: basic budgeting and budget control](setup-overview-basic-budgeting-and-budget-control.md)

[Set up Budgeting workflows](set-up-budgeting-workflows.md)

[About budget planning configuration and setup](about-budget-planning-configuration-and-setup.md)

[About budget plans](about-budget-plans.md)

[Create budget plan templates manually](create-budget-plan-templates-manually.md)

[Key tasks: Configure budget planning and set up budget planning processes](key-tasks-configure-budget-planning-and-set-up-budget-planning-processes.md)

[Configure budget planning security](configure-budget-planning-security.md)

[Generate budget plans from source information](generate-budget-plans-from-source-information.md)

[Key tasks: Create and process budget plans](key-tasks-create-and-process-budget-plans.md)

  


