---
title: About budget planning configuration and setup
TOCTitle: About budget planning configuration and setup
ms:assetid: 55f65750-dffd-4217-bba2-ab452aa2ed7f
ms:mtpsurl: https://technet.microsoft.com/library/JJ677339(v=AX.60)
ms:contentKeyID: 49384113
author: Khairunj
ms.author: daxcpft
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- budget plan
- Budget plan allocations
- Budget planning scenarios, stages, and workflows
- Budget planning folders and templates
- Budget planning priorities
- Budget plan workflows
- Budget planning stage rules and scenario constraints
- budget planning
- plan budget
audience: Application User
ms.search.region: Global
---

# About budget planning configuration and setup 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic contains information to help you configure budget planning and set up budget planning processes. After you configure budget planning, you can set up one or more budget planning processes. For more information about how to set up budget planning processes, see Setting up budget planning processes in this topic.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for cumulative update 7 or later for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3.</P>



## Configuring budget planning

Before you configure budget planning, review the budget planning requirements in [Budget planning overview](budget-planning-overview.md). Budget planning requirements that you must complete before you configure budget planning include setting up the budget organization hierarchy, creating budget plan templates, and setting up Budgeting workflows.

After you complete the budget planning requirements, you can configure budgeting planning by using the **Budget planning configuration** form. For more information, see “Configure budget planning” in [Key tasks: Configure budget planning and set up budget planning processes](key-tasks-configure-budget-planning-and-set-up-budget-planning-processes.md). For more information about the **Budget planning configuration** form, see [Budget planning configuration (form)](https://technet.microsoft.com/library/jj677418\(v=ax.60\)).

The following areas are covered in this section:

  - Budget planning parameters, scenarios, stages, and workflows

  - Workflows

  - Budget planning stage rules and scenario constraints

  - Allocations

  - Budget planning priorities

  - Folders and templates

## Budget planning parameters, scenarios, stages, and workflows

When you configure budget planning, you start by defining parameters, scenarios, stages, and workflows.

  - **Parameters** – Define the security rules to be applied to budget plans, and the level of detail to include for budget plans in Microsoft Excel.

  - **Budget plan scenarios** – Define categories of data for the budget plans. You define budget plan scenarios to support monetary and other unit of measure classes, such as quantity. Examples of monetary budget plan scenarios are Department previous year and Department requests. Previous year 911 calls and Full-time equivalent (FTE) count are examples of scenarios that use quantities. When you create a budget plan, you select a scenario for the budget plan lines. When you select another scenario, you enter another set of budget plan lines.

  - **Budget planning stages** – Define the steps that a budget plan follows from its inception to final approval. Budget planning stages are arranged in budget planning workflows. Examples of budget planning stages are Department review, Department submitted, Management review, and Management approval.

  - **Budget planning workflows** – Define the order of the budget planning stages and associate each budget planning workflow with a Budgeting workflow ID. Budget planning workflows consist of budget planning stages. Budgeting workflows are the automated processes that move budget plans through the budget planning stages. For more information, see “Workflows” in this topic.

The following table shows examples of two budget planning workflows, one for departments and the other for management. The department workflow has three stages: Submitting the budget plan scenarios, reviewing the scenarios, and approving the scenarios. The management workflow has one stage for review and another stage for final approval.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Budget planning workflow</p></th>
<th><p>Budget planning stage and budget plan scenarios</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Department budget planning workflow</p></td>
<td><p><strong>Department submitted stage</strong></p>
<p>Department previous year scenario<br />
Department request – best-case scenario<br />
Department request – worst-case scenario</p>
<p><strong>Department review stage</strong></p>
<p>Department request – best-case scenario<br />
Department request – worst-case scenario</p>
<p><strong>Department approved stage</strong></p>
<p>Department request – best-case scenario<br />
Department request – worst-case scenario</p></td>
</tr>
<tr class="even">
<td><p>Management budget planning workflow</p></td>
<td><p><strong>Management review stage</strong></p>
<p>All department requests – best-case scenario<br />
All department requests – worst-case scenario</p>
<p><strong>Management final approval stage</strong></p>
<p>All department requests scenario</p></td>
</tr>
</tbody>
</table>


A scenario can contain different data in different stages and workflows. For example, during a management review, you could add, remove, or modify budget plan lines in the best-case scenario.

In the final approval stage, the budget plan lines in the scenarios for the departments can be aggregated into one scenario for all departments.

Back to top

## Workflows

A budget planning workflow consists of an ordered set of stages that a budget plan moves through. Each budget planning workflow is associated with a Budgeting workflow that routes the budget plans, together with worksheets, justifications, and attachments, through the organization for reviews and approvals.

Before you set up a Budgeting workflow for budget planning, you should compile the following information:

  - The budget planning stages and the order of the stages in the budget planning workflows.

  - The responsibility centers that the budget plans are routed to in the budget organization hierarchy.

  - The users who develop, review, and approve the budget plans. Users who are involved in budget planning must be associated with the records for workers whose positions report to an organization unit in the organization hierarchy for budget planning. Alternatively, users who are outside the hierarchy must be added to a user group for budget planning.

  - The scope of the Budgeting workflows. Determine whether you will use one workflow for the organization hierarchy or for several responsibility centers, or if you will use a separate Budgeting workflow for each responsibility center.

  - The allocations for budget plan scenarios. Determine whether estimated, requested, and approved budget amounts will be allocated between scenarios, or if they will be aggregated or distributed between parent budget plans and the associated budget plans. Also determine whether budget amounts will be allocated automatically by using stage allocations and schedules.

  - The workflow constraints. Determine whether users will be able to reset or delete budget plans that use the workflow. These options are available starting with cumulative update 7 for Microsoft Dynamics AX 2012 R2.

Click **Budgeting** \> **Setup** \> **Budgeting workflows**. Then select the **Budget plan workflows** type in the workflow editor to create a Budgeting workflow. You associate a budget planning workflow with a Budgeting workflow ID in the **Workflows** area of the **Budget planning configuration** form.

For example, the budget planning workflow for the department operating budget has three stages: Department submitted, Department reviewed, and Department approved. You use the workflow editor to create a Budgeting workflow that has two stage transition elements to handle the transitions between the three stages. Then, by using a workflow ID such as **00049\_001**, you associate the budget planning workflow for the department operating budget with the Budgeting workflow that has the two stage transition elements.

## Workflow elements for budget plans

When you select **Budget plan workflows** as the workflow type, the following workflow elements are available:

  - **Approve budget plan** – Create an approval element for budget plans. This approval element has the following outcomes: **Approve**, **Reject**, **Request change**, **Delegate**, **Recall**, and **View history**.

  - **Activate associated budget plan** – Create an automated task to activate budget plans that are associated with a parent budget plan. For the associated plans that are activated, the workflow status is set to **Not submitted** and the document status is set to **Draft**. If no plans are associated with the parent budget plan, an associated budget plan is created, and the budget manager of the organization is the preparer. If there is no budget manager, the preparer of the parent budget plan is the preparer of the associated budget plan.

  - **Stage transition budget plan** – Create an automated task to perform a stage transition for a budget plan. The stage transition task changes the budget planning stage to the next stage in the budget planning workflow. Budget plan workflows must contain a stage transition element for each transition that moves a budget plan to the next budget planning stage. For example, a workflow for a budget planning process that has three stages requires two stage transition elements to connect the three elements that are associated with the three budget planning stages.

  - **Budget planning stage allocation** – Create an automated task to perform an allocation by using an allocation schedule during the specified workflow and stage for budget planning. The allocation schedule specifies the allocation method, source scenario, and destination scenario.

  - **Flow controls** – Create standard workflow elements for decisions and activities.

  - **Review associated budget plan(s) that are completed** – Create a task for users to review the completed budget plans that are associated with a parent budget plan. All associated budget plans must have a workflow status of **Approve** or **Reject** before the review can be completed for the parent budget plan.

  - **Review budget plan** – Create a task for a user to review the budget plans.

## Workflow participants for budget plans

The workflow participants for budget plans include the following budget organization participants:

  - Budget organization structure manager

  - Budget plan preparer

  - Budget organization manager

  - Parent budget plan preparer

  - Parent budget organization manager

For more information, see [Set up Budgeting workflows](set-up-budgeting-workflows.md).

Back to top

## Budget planning stage rules and scenario constraints

When you work with a budget plan, the stage rules and scenario constraints combine to determine your access to the budget plan scenarios and the budget plan lines for the scenarios. Constraints for budget planning scenarios are set up in the **Budget planning configuration** form, and they define when you can view or modify scenario data. Stage rules for budget planning are set up in the **Budget planning process** form, and they determine whether you can add or modify budget plan lines during each stage.

The following table shows how the stages rules and the scenario constraints affect access to view, modify, and add scenario data. For example, if the stage rules specify that lines can be modified but not added during a stage, a scenario constraint that has edit access would allow the budget plan lines to be modified. However, no new lines could be added.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Stage rule -<br />
Modify lines</p></th>
<th><p>Stage rule -<br />
Add lines</p></th>
<th><p>Scenario constraint</p></th>
<th><p>Scenario access level -<br />
View or Edit</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>View</p></td>
<td><p>View</p></td>
</tr>
<tr class="even">
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>None</p></td>
<td><p>None</p></td>
</tr>
<tr class="odd">
<td><p>No</p></td>
<td><p>No</p></td>
<td><p>Edit</p></td>
<td><p>View</p></td>
</tr>
<tr class="even">
<td><p>Yes</p></td>
<td><p>No</p></td>
<td><p>View</p></td>
<td><p>View</p></td>
</tr>
<tr class="odd">
<td><p>Yes</p></td>
<td><p>No</p></td>
<td><p>None</p></td>
<td><p>None</p></td>
</tr>
<tr class="even">
<td><p>Yes</p></td>
<td><p>No</p></td>
<td><p>Edit</p></td>
<td><p>Edit (modify lines only)</p></td>
</tr>
<tr class="odd">
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>View</p></td>
<td><p>View</p></td>
</tr>
<tr class="even">
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>None</p></td>
<td><p>None</p></td>
</tr>
<tr class="odd">
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>Edit</p></td>
<td><p>Edit (modify and add lines)</p></td>
</tr>
</tbody>
</table>


Back to top

## Allocations

In budget planning, the amounts or quantities in budget plan lines can be allocated between source scenarios and destination scenarios. Although the source scenario and destination scenario typically differ, they can be the same. You can perform allocations by using the following allocation methods:

  - **Allocate across periods** – The budget plan lines are allocated from the source budget plan scenario across periods in the destination scenario by using a period allocation key. Before you can allocate across periods, you must set up period allocation keys in the **Period allocation categories** form. For more information, see [Period allocation categories (form)](https://technet.microsoft.com/library/aa582352\(v=ax.60\)).

  - **Allocate to dimensions** – The budget plan lines are allocated from the source budget plan scenario across the financial dimensions in the destination scenario. Before you can allocate to dimensions, you must set up budget allocation terms in the **Budget allocation terms** form. For more information, see [Budget allocation terms (form)](https://technet.microsoft.com/library/hh209569\(v=ax.60\)).

  - **Aggregate** – The budget plan lines are aggregated from the source scenario in the associated budget plans to the destination scenario in the parent budget plan.

  - **Distribute** – The budget plan lines are distributed from the source budget plan scenario in the parent budget plan to the destination scenario in the associated budget plans.
    
    Before you can create the budget plans to aggregate or distribute budget plan lines, you must set up the budget planning process so that you can create associated budget plans. For more information, see “Set up budget planning processes” in [Key tasks: Configure budget planning and set up budget planning processes](key-tasks-configure-budget-planning-and-set-up-budget-planning-processes.md).

  - **Use ledger allocation rules** – Starting with cumulative update 7 for Microsoft Dynamics AX 2012 R2, you can use ledger allocation rules for budget plan lines. The budget plan lines are distributed from the source budget plan scenario to the destination budget plan scenario according to the ledger allocation rule that is selected. For more information about ledger allocation rules, see [About allocation rules](about-allocation-rules.md) and [Create an allocation rule](create-an-allocation-rule.md).

## Allocation schedules and stage allocations

You configure allocation schedules and stage allocations in the **Budget planning configuration** form. Allocation schedules and stage allocations are used to automatically allocate budget plan lines during workflow processing. Budget plan lines in the destination scenario can be created and modified without the intervention of the budget plan preparer or reviewer to create the lines.

When you set up an allocation schedule, you select an allocation method, source scenario, and destination scenario. When you set up a stage allocation, you associate the budget planning workflow and stage with the allocation schedule. The budget planning workflow must be associated with a Budgeting workflow that uses the **Budget planning stage allocation** automated workflow task. When the workflow reaches the specified stage, the allocation automatically occurs. This automated task can be used to create budget plan lines in a new scenario.

Back to top

## Budget planning priorities

You define budget plan priorities in the **Budget planning configuration** form. Budget plan priorities define categories and objectives for budget plans. Budget plan priorities can be used to organize, classify, and evaluate several budget plans. For example, you can create a budget planning priority for health and safety and then evaluate budget plans that are assigned to that priority. You can also assign a number to rank budget plans across all budget plans.

Back to top

## Folders and templates

You must define the folder locations for the attachments for the budget plans. You must also define the location for the budget plan templates that are used to create the worksheets and justification. Because there can be many attachments and templates, we recommend that you store the files in different locations.

Back to top

## Setting up budget planning processes

You set up budgeting planning processes in the **Budget planning process** form. For more information, see “Set up budget planning processes” in [Key tasks: Configure budget planning and set up budget planning processes](key-tasks-configure-budget-planning-and-set-up-budget-planning-processes.md). For more information about the **Budget planning process** form, see [Budget planning process (form)](https://technet.microsoft.com/library/jj677441\(v=ax.60\)).

After you configure budget planning, you can set up budget planning processes. For each budget planning process, you select a budget cycle and a ledger. Then you select the budget organization hierarchy, scenarios, stages, and workflows for the budget planning process.

After you select the budget organization hierarchy on the **Budget planning process administration** FastTab, you must assign a budget planning workflow to all the responsibility centers in the organization that appear in the grid. To assign or change the budget planning workflow for similar responsibility centers, click **Assign workflow**, and then select the organization type to target and the budget planning workflow to use. The Budgeting workflow ID that is associated with each budget planning workflow is added to the grid automatically.

When you define the stage rules and templates on the **Budget planning stage rules and templates** FastTab, you can define a different set of rules and templates for each budget planning stage. For example, the Management review stage could let users modify lines in a budget plan, but not add lines. The Department review stage could let users both add and modify lines.

Use the **Associate budget plans** check boxes on the **Budget planning stage rules and templates** FastTab to determine whether associated budget plans can be created during a budget planning stage. These settings also determine whether you can view parent budget plans that were created at a higher level in the organization hierarchy than the level where the associated budget plans were created.

The **Add lines** and **Modify lines** check box values, together with the scenario constraints, determine whether you can add or modify budget plan lines during a budget planning stage. For more information, see the Budget planning stage rules and scenario constraints section in this topic.

Back to top


> [!NOTE]
> <P>We recommend that you use Management Reporter for Microsoft Dynamics ERP to create, maintain, deploy, and view financial reports that include budget planning data. Management Reporter lets you design financial reports based on ledger accounts and financial dimensions, drill down to transaction-level detail, and use web-based report viewing. For more information about how to print financial reports by using Management Reporter, see <A href="https://go.microsoft.com/fwlink/?linkid=324762">Management Reporter for Microsoft Dynamics ERP</A>.You can use Management Reporter to report on budget planning data only if you have rollup 4 or later for Management Reporter 2012 installed.</P>



## See also

[Budget planning overview](budget-planning-overview.md)

[About budget plans](about-budget-plans.md)

[Key tasks: Configure budget planning and set up budget planning processes](key-tasks-configure-budget-planning-and-set-up-budget-planning-processes.md)

[Configure budget planning security](configure-budget-planning-security.md)

[Budget planning configuration (form)](https://technet.microsoft.com/library/jj677418\(v=ax.60\))

[Budget planning process (form)](https://technet.microsoft.com/library/jj677441\(v=ax.60\))

  


