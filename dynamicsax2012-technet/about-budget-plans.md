---
title: About budget plans
TOCTitle: About budget plans
ms:assetid: 1582e791-e5ab-4369-b016-4fd723946b36
ms:mtpsurl: https://technet.microsoft.com/library/JJ677326(v=AX.60)
ms:contentKeyID: 49384100
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- Allocating budget plan lines
- Associated budget plans
- Budget plan header
- Budget plan lines
- Budget plan line details
- Viewing information about budget plans
- Developing budget plans
- Parent budget plans
- Generating budget plans
- Forecast positions and budget plans
- Worksheets and justifications
audience: Application User
ms.search.region: Global
---

# About budget plans 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Budget plans are documents that are used to develop estimates for amounts and units in budget plan scenarios for the responsibility centers in the budget organization. After you set up and activate a budget planning process, you can create budget plans that have multiple scenarios. You can then automatically route the budget plans, together with worksheets, justifications, and attachments, through your organization for review and approval.

You can develop a budget plan at a higher level in the organization and allocate the budget estimates to lower levels of the organization. Alternatively, you can associate multiple budget plans from lower levels of the organization with a parent budget plan at a higher level in the organization.

## Viewing information about budget plans

On a **Budget plan** list page, such as **All budget plans** or **Budget plans prepared by me**, you can select a budget plan and view information about it in the preview pane. You can also view the following information in the FactBoxes:

  - **Budget plan preparer** – The user who prepared the budget plan.

  - **Estimates by amount** – The scenarios and amount totals for the budget plan.

  - **Estimates by units** – The scenarios and unit totals for the budget plan.

  - **Associated budget plans** – The document numbers and stages for the associated plans.

  - **Budget plan documents** – The file names, template types, and stages for the worksheets, justifications, and additional files that are attached to the budget plan.

On the **Action Pane**, you can select **Budget plan hierarchy** to view information about the budget plan and any associated budget plans. You can move the pointer over a budget plan to view information about the budget plan in the preview pane and the FactBoxes. You can also double-click a budget plan to open it.

For information about how to create budget plans, see [Key tasks: Create and process budget plans](key-tasks-create-and-process-budget-plans.md). For information about the **Budget plan** form, see [Budget plan (form)](https://technet.microsoft.com/library/jj677376\(v=ax.60\)).

## Developing budget plans

Budget plans can be developed either from the top down or from the bottom up. For example, you manage a department that has three organization units. In a top-down approach, you create a parent budget plan that has a budget plan scenario that includes target budget amounts for each organization unit. The target amounts are generated from last year’s actual expenditures in the general ledger. You then create an associated budget plan for each organization unit. For each associated plan, you select the manager of the organization unit as the budget plan preparer. Each manager can create allocations in a department-request scenario or in another scenario by specifying a percentage increase or decrease in the target amounts. After the new target amounts are allocated to the scenarios, the managers submit their budget plans to a workflow that routes the plans back to you for review and approval.

In a bottom-up approach, you ask each manager to prepare a budget plan for his or her organization unit. The managers then submit the budget plans to a workflow that routes the plans to you for review and approval. The budget plans contain worst-case and best-case scenarios. You create one parent budget plan and associate the budget plans from the various organization units with the parent budget plan. You can then manually or automatically allocate the amounts in the scenarios from the associated budget plans to scenarios in the parent budget plan. In this manner, you can view the aggregated amounts for all associated budget plans in your organization.

## Parent budget plans and associated budget plans

When you set up the stage rules for a budget planning process, you specify the stage or stages in a budget planning workflow in which associated budget plans can be created.

When you use parent budget plans and associated budget plans, you can create allocations that aggregate or distribute budget estimates between the parent budget plans and the associated budget plans. You can also use automated workflow tasks to control allocations between parent plans and associated plans, and to control when and how associated budget plans are activated and routed for review and approval.

After the budget estimates have been aggregated or distributed, worksheets can be analyzed and updated, and then published back to the budget plans.

## Budget plan header

The budget plan header contains information that you entered or selected when you created the budget plan. For example, when you create a budget plan, you select the budget planning process and enter the budget plan name. Some fields in the budget plan header, such as the document number, are assigned automatically. Other fields in the header, such as the budget plan stage, document status, and workflow status, are updated automatically during workflow processing.

## Budget plan lines and line details

Before you can add lines and line details to a budget plan, you must select a scenario in the **Filter by scenario** field. Based on scenario constraints, you can view or modify budget plan lines. Based on stage rules, you can modify or add lines.

Budget plan lines can be entered manually, allocated from other scenarios, or automatically generated from other plans and other modules, such as from fixed assets or forecast positions. When you add a line to a budget plan scenario and enter dimension values and amounts or units, the line is displayed only in the instance of the scenario for the current budget plan.

Budget plan line details can include information about projects and proposed projects, fixed assets and proposed assets, and forecast positions. In addition, there are options for line details to indicate if the budget plan line is recurring or if it is a new request.

## Allocating budget plan lines

In budget planning, the amounts or quantities in budget plan lines are allocated between source and destination scenarios. The source scenario and the destination scenario can differ or be the same scenario. For example, you have a budget plan scenario for Department A that includes budget amounts from the previous year. You can allocate those budget amounts to the same scenario with a 10 percent increase or to a different scenario. The scenarios can be in the same budget plan or they can be in different budget plans.

The source and destination scenarios for allocations must have the same unit of measure. For example if the source scenario uses a **Quantity** unit of measure, the destination must also use a **Quantity** unit of measure.

If the source and destination scenarios use different currencies, the currencies are converted to the accounting currency for the ledger that is associated with the budget planning process. The currency conversions are based on the exchange rates that are set up for Budgeting.

If the destination scenario has budget plan lines that were previously allocated, all the budget plan lines are deleted during the allocation. If the destination scenario has budget plan lines that were entered manually by a user, those lines are retained during the allocation.

## Worksheets and justifications

You can use budget plan worksheet templates to exchange information between Microsoft Dynamics AX and Microsoft Excel. You can also view budget plan lines for more than one scenario. You can use budget plan justification templates to automatically export information from Microsoft Dynamics AX to Microsoft Word. You can also route the justification for feedback by using the Word features for comments and tracking changes. Budget plan templates are created by template authors or the designers of the budget planning processes. The templates are used to create Excel worksheets and Word justification documents when the budget plans are routed for reviews and approvals.

For example, a budget manager creates a budget plan that has a department-request scenario and a previous-year scenario. The budget plan lines for the previous-year scenario are generated from the actual expenditures for the previous year. The budget plan lines for the department-request scenario are allocated from the previous-year scenario by applying a factor of 3 percent less than the actual expenditures for last year. The budget manager submits the budget plan to workflow and the budget plan is routed to a department manager for review. The department manager imports the data from the department-request scenario and the previous-year scenario into an Excel worksheet. The worksheet is created from a template that was designed to include the budget plan lines. The department manager can see the budget plan lines for the previous year and the department-request scenarios, and then adjust the amounts in the budget lines for the department-request scenario. Then the manager publishes the data back to the department-request scenario and submits the budget plan to workflow, where it is routed to the next stage for review or approval. The worksheet that the manager created from the template is automatically attached when the budget plan is submitted to workflow.

## Forecast positions and budget plans

In Human resources, you can create forecast positions and enter the budget details for each position. When you use budget planning, you can use the budget details for the forecast positions in the following ways for your budget plans:

  - Generate a budget plan or a budget plan scenario from forecast positions. You select the forecast position information by using a query in the **Generate budget plan from forecast positions** form.

  - Add information about one forecast position to a budget plan line. You select the forecast position on the **Line details** FastTab of the **Budget plan** form.

  - Add information about all forecast positions or for one department’s forecast positions to a budget plan line. You select all forecast positions or one department’s forecast positions in the **Select forecast positions** form that you open from the **Budget plan lines** FastTab of the **Budget plan** form.

  - Add information about the full-time equivalent (FTE) count for all forecast positions or for one department’s forecast positions to an FTE budget plan scenario. You select all forecast positions or one department’s forecast positions in the **Select forecast positions** form that you open from the **Budget plan lines** FastTab of the **Budget plan** form. The FTE budget plan scenario must have a **Quantity** unit of measure, and you must select an FTE main account when you select the FTE budget plan scenario. The main account that you use to create the budget plan line for the FTE count can be the main account for salary expenses.

For more information, see [Key tasks: Forecast positions](https://technet.microsoft.com/library/jj729760\(v=ax.60\)) and “Add forecast positions to budget plan lines” in [Key tasks: Create and process budget plans](key-tasks-create-and-process-budget-plans.md).

## Generating budget plans

You can create a new budget plan or replace or update an existing budget plan scenario by using data from the general ledger, another budget plan, fixed assets, and forecast positions. You can select the following options to generate budget plans:

  - **Generate budget plan from general ledger** – Transfer historical and current data from the general ledger to a budget plan.

  - **Generate budget plan from budget plan** – Transfer budget plan data from a budget plan that uses one budget planning process to a budget plan that has the same ledger but uses another budget planning process.

  - **Generate budget plan from fixed assets** – Transfer fixed asset budgets to a budget plan.

  - **Generate budget plan from forecast positions** – Transfer forecast position data from Human resources to a budget plan.

For more information, see [Generate budget plans from source information](generate-budget-plans-from-source-information.md).

## See also

[Budget planning overview](budget-planning-overview.md)

[About budget planning configuration and setup](about-budget-planning-configuration-and-setup.md)

[Key tasks: Create and process budget plans](key-tasks-create-and-process-budget-plans.md)

[Budget plan (form)](https://technet.microsoft.com/library/jj677376\(v=ax.60\))

  


