---
title: 'Key tasks: Create and process budget plans (EP)'
TOCTitle: 'Key tasks: Create and process budget plans'
ms:assetid: 7a9043d3-8c3b-4457-8dbd-1759e278eb0f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677300(v=AX.60)
ms:contentKeyID: 49384071
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BudgetPlanAllocate
- BudgetPlanListPage
- BudgetPlanCreate
- BudgetPlanLineDetail
- BudgetPlanDetail
- BudgetPlanListPageAssignedToMe
- BudgetPlanListPagePreparedByMe
- BudgetPlanListPageAssignedToMyOrg
- BudgetPlanListPageActive
- Create budget plans
---

# Key tasks: Create and process budget plans (EP) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

A budget plan is a document that contains a header, budget plan lines, and line details. When you create a budget plan, it is automatically assigned a unique document number, and your name is displayed in the **Budget plan preparer** field. The budget planning process that you select and the responsibility center of the budget preparer determine the organization hierarchy and the budget planning workflow for the budget plan. After you have finished preparing a budget plan, you submit it to workflow. Then the budget plan, together with worksheets, justifications, and attachments, is automatically routed through your organization for review and approval.

## What do you want to do?

Create a budget plan

Create an associated budget plan

Add or modify budget plan lines and line details

Use worksheets and justifications in budget plans

Submit a budget plan to workflow

## Create a budget plan

Before you can create a budget plan, a budget planning process must be active. Each budget planning process is associated with a budget cycle, ledger, and budgeting organization. To be a budget plan preparer, you must be in a budget planning user group, or you must be a worker in a responsibility center that is in a budget organization hierarchy.

1.  Click **Budgeting** on the top link bar. On the **Action Pane**, in the **New** group, click **Budget plan**.

2.  Enter or select information in the following fields, and then click **Create**:
    
      - **Budget planning process** – Select an active budget planning process.
    
      - **Responsibility center** – Select the responsibility center for the budget plan. By default, your responsibility center is displayed.
    
      - **Parent budget plan** – Specify the parent budget plan, if there is a parent budget plan.
    
      - **Budget plan preparer** –Select the name of the user who prepares the budget plan. By default, your name is displayed.
    
      - **Budget planning user group** – For users outside who are outside the budget organization assigned to the budget planning process, select the user group whose members require access to the budget plan.
    
      - **Document number** – The unique identification number for the budget plan.
    
      - **Budget plan** – Enter a descriptive name for the budget plan.
    
      - **Budget plan priority** – Select the priority of the budget plan, if your organization evaluates budget plans by priority.

Back to top

## Create an associated budget plan

Before you can create an associated budget plan, the budget planning process that you select must be set up for associated budget plans. Additionally, the budget organization hierarchy must have at least two levels. The **Associate budget plans** check box for the current budget planning stage must be selected for the budget planning stage rules in the **Budget planning process** form.

1.  Click **Budgeting** on the top link bar. On the **Action Pane**, in the **New** group, click **Associate plan**.

2.  Enter or select information in the following fields, and then click **Create**:
    
      - **Budget planning process** – Specify the budget planning process for the parent plan.
    
      - **Responsibility center** – Select the responsibility center for the budget plan. By default, your responsibility center is displayed.
    
      - **Parent budget plan** – Specify the name of the parent budget plan.
    
      - **Budget plan preparer** – Select the name of the user who prepares the budget plan. By default, your name is displayed.
    
      - **Budget planning user group** – For users outside the budget organization that is assigned to the budget planning process, select the user group whose members require access to the budget plan.
    
      - **Document number** – The unique identification number for the budget plan.
    
      - **Budget plan** – Enter a descriptive name for the budget plan.
    
      - **Budget plan priority** – Select the priority of the budget plan, if your organization evaluates budget plans by priority.

Back to top

## Add or modify budget plan lines and line details

Before you can add or modify budget plan lines, the budget planning process that you select when you create the budget plan must be set up so that budget plan lines can be added and modified. The **Add lines** and **Modify lines** check boxes for the current budget planning stage must be selected for the budget planning stage rules in the **Budget planning process** form.

1.  Click **Budgeting** on the top link bar.

2.  On the **Action Pane**, in the **New** group. click **Budget plan**. Or, select an existing budget plan and, in the **Maintain** group, click **Edit**.

3.  In the **Filter by scenario** list, select a scenario. The **Scenario constraints** options in the **Budget planning configuration** form determine the view and edit access for each budget plan scenario. If the **Add line** button is not available, select a different scenario.

4.  In the **Budget plan lines** grid, click **Add line**.
    
    When you add a line to a budget plan scenario, the line is added only to the scenario in the current budget plan.

5.  Select an account structure and add the dimension values.

6.  View or make any required changes to the information in the remaining fields, such as **Effective date** and **Budget class**. Then enter the unit or monetary information.

7.  Optional: Click **Line details**, and then enter or select information in the following fields:
    
      - **Project ID** or **Proposed project** – Select an existing project or a proposed project for the budget line.
    
      - **Fixed asset number** or **Proposed asset** – Select an existing asset or a proposed asset for the budget line.
    
      - **Position** – Select a forecast position for the budget line.
    
      - **Is recurring** – Select this check box to indicate that the budget line recurs each year.
    
      - **New request** – Select this check box to indicate that the budget line is a new request.
    
      - **Comment** – Enter a description or comment for the budget plan line.

8.  To view details for the selected line, click **Details**.

9.  To allocate the budget amounts for the selected lines, click **Allocate budget**. Then select **Allocate across periods** or **Allocate to dimensions**.
    
      - If you click **Allocate across periods**, select the period key and the destination budget plan scenario.
    
      - If you click **Allocate to dimensions**, select the allocation term and the destination budget plan scenario.
    
    In the **Multiply by** field, enter a value by which to multiply the currency amounts or quantities for the selected lines.

Back to top

## Use worksheets and justifications in budget plans

Microsoft Dynamics AX can be integrated with Microsoft Word and Microsoft Excel by using the Office Add-ins for Microsoft Dynamics AX. Users can create Word justifications and Excel worksheets that are linked dynamically to the tables in Microsoft Dynamics AX. When you route a justification with a budget plan, reviewers can add comments and track changes in the document. You can import the data from a multiple scenarios, analyze and modify the data, and publish it back to the budget plan. Integration for the Office Add-ins must be set up before users can use the Office Add-ins to create files.

A template author creates templates for the worksheets and justifications. The templates contain fields from the budget plans. The worksheets and justifications that are created by using the templates contain the data from the budget plan that you are working with.

Each budget plan has one justification template that you can use to create justification documents for that budget plan. Each budget planning stage can have a different template that you can use to create a worksheet for that stage. When you save the worksheet, it automatically becomes a budget plan attachment.

When you create a justification, you can add information to support your budget plan. When you route the justification and the budget plan for review and approval, the reviewers can add comments and use change tracking to add information to the justification.

When you create a worksheet, you can import the data from multiple scenarios, analyze and modify the data, and then publish the data back to the budget plan. You can use a separate worksheet template for each budget planning stage, and the worksheets that you create are automatically attached to the budget plan before it is routed for review.

### Import, modify, and publish budget plan data by using worksheets

1.  Click **Budgeting** on the top link bar.

2.  Select a budget plan.

3.  Click **Worksheet** on the **Action Pane**. Information is exported to the worksheet.

4.  In Excel, you can update the amounts in the worksheet. Then, on the **Dynamics AX** tab, click **Publish** to import the updated information to the budget plan.

5.  In Microsoft Dynamics AX, on the **Action Pane**, click **Refresh** to update the form.

### Create justifications for budget plans

1.  Click **Budgeting** on the top link bar.

2.  Select a budget plan.

3.  Click **Justification** on the **Action Pane**.

4.  Use the features in Word to add and format information.

5.  Save the file, and then close Word.

Back to top

## Submit a budget plan to workflow

To submit a budget plan to workflow, you must be either the preparer or a member of the budget planning user group assigned to the plan. Before you can submit the budget plan, all required fields must be filled in, and the budget plan must contain at least one line item. The budget plan must also have a status of **Draft**.

1.  Click **Budgeting** on the top link bar.

2.  Select the budget plan to submit to workflow.

3.  In the workflow message bar, click **Submit**.

4.  In the **Comment** field that is displayed, enter a comment, and then click **Submit**.

5.  To recall a budget plan that you have submitted to workflow, in the workflow message bar, click **Actions** \> **Recall**.

6.  To view the workflow history for a budget plan that you have submitted to workflow, in the workflow message bar, click **Actions** \> **View history**.

Back to top

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

