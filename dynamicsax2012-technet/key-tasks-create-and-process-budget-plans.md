---
title: 'Key tasks: Create and process budget plans'
TOCTitle: 'Key tasks: Create and process budget plans'
ms:assetid: 8f829874-e5fd-44a0-beb4-c420726b8f5a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677349(v=AX.60)
ms:contentKeyID: 49384123
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- budget plan
- budget planning
- budget plans
---

# Key tasks: Create and process budget plans [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to manually create a budget plan. For information about how to automatically generate a budget plan from another budget plan, the general ledger, fixed assets, or forecast positions, see [Generate budget plans from source information](generate-budget-plans-from-source-information.md).

A budget plan is a document that contains a header, budget plan lines, and line details. When you create a budget plan, it is automatically assigned a unique document number, and your name is displayed in the **Budget plan preparer** field. The budget planning process and the responsibility center of the preparer determine the organization hierarchy and the budget planning workflow for the budget plan. After you have finished preparing a budget plan, you submit it to workflow. Then the budget plan, together with worksheets, justifications, and attachments, is automatically routed through your organization for review and approval.


> [!NOTE]
> <P>The procedure for completing this task changed for cumulative update 7 or later for Microsoft Dynamics AX 2012 R2. The updated procedure also applies to AX 2012 R3. For more information, see the section later in this topic.</P>



We recommend that you use Management Reporter for Microsoft Dynamics ERP to create, maintain, deploy, and view financial reports that include budget planning data. Management Reporter lets you design financial reports based on ledger accounts and financial dimensions, drill down to transaction-level detail, and use web-based report viewing. For more information about how to print financial reports by using Management Reporter, see [Management Reporter for Microsoft Dynamics ERP](http://go.microsoft.com/fwlink/?linkid=324762).

You can use Management Reporter to report on budget planning data only if you have rollup 4 or later for Management Reporter 2012 installed.

## What do you want to do?

Learn more about...

Create a budget plan

Create an associated budget plan

Add or modify budget plan lines and line details

Use worksheets and justifications in budget plans

Add forecast positions to budget plan lines

Submit a budget plan to workflow

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[Budget planning overview](budget-planning-overview.md)

[About budget planning configuration and setup](about-budget-planning-configuration-and-setup.md)

[About budget plans](about-budget-plans.md)

## Create a budget plan

Before you can create a budget plan, a budget planning process must be active. Each budget planning process is associated with a budget cycle, ledger, and budget organization. To be a budget plan preparer, you must be in a budget planning user group, or you must be a worker in a responsibility center in a budget organization hierarchy.

1.  Click **Budgeting** \> **Common** \> **Budget plans** \> **All budget plans**. On the **Action Pane**, in the **New** group, click **Budget plan**.

2.  Enter or select information in the following fields, and then click **Create**:
    
      - **Budget planning process** – Select an active budget planning process.
    
      - **Responsibility center** – Select the responsibility center for the budget plan. By default, your responsibility center is displayed.
    
      - **Parent budget plan** – Specify the parent budget plan, if there is a parent budget plan.
    
      - **Budget plan preparer** – Select the name of the user who prepares the budget plan. By default, your name is displayed.
    
      - **Budget planning user group** – For users who are outside the budget organization that is assigned to the budget planning process, select the user group whose members require access to the budget plan.
        
        Starting with cumulative update 7 for Microsoft Dynamics AX 2012 R2, you can select a user group in this field only if the **Allow access to budget plans by user group** check box is selected in the **Budget planning configuration** form.
    
      - **Document number** – The unique identification number for the budget plan.
    
      - **Budget plan** – Enter a descriptive name for the budget plan.
    
      - **Budget plan priority** – Select the priority of the budget plan, if your organization evaluates budget plans by priority.

Back to top

## Create an associated budget plan

Before you can create an associated budget plan, the budget planning process that you select must be set up for associated budget plans. Additionally, the budget organization hierarchy must have at least two levels. The **Associate budget plans** check box for the current budget planning stage must be selected for the budget planning stage rules in the **Budget planning process** form.

1.  Click **Budgeting** \> **Common** \> **Budget plans** \> **All budget plans**. On the **Action Pane**, in the **New** group, click **Associate plan**.

2.  Enter or select information in the following fields, and then click **Create**:
    
      - **Budget planning process** – Specify the budget planning process for the parent plan.
    
      - **Responsibility center** – Select the responsibility center for the budget plan. By default, your responsibility center is displayed.
    
      - **Parent budget plan** – Specify the name of the parent budget plan.
    
      - **Budget plan preparer** – Select the name of the user who prepares the budget plan. By default, your name is displayed.
    
      - **Budget planning user group** – For users who are outside the budget organization that is assigned to the budget planning process, select the user group whose members require access to the budget plan.
        
        Starting with cumulative update 7 for Microsoft Dynamics AX 2012 R2, you can select a user group in this field only if the **Allow access to budget plans by user group** check box is selected in the **Budget planning configuration** form.
    
      - **Document number** – The unique identification number for the budget plan.
    
      - **Budget plan** – Enter a descriptive name for the budget plan.
    
      - **Budget plan priority** – Select the priority of the budget plan, if your organization evaluates budget plans by priority.

Back to top

## Add or modify budget plan lines and line details

Before you can add or modify budget plan lines, the budget planning process that you selected when you created the budget plan must be set up so that budget plan lines can be added and modified. The **Add lines** and **Modify lines** check boxes for the current budget planning stage must be selected for the budget planning stage rules in the **Budget planning process** form.

1.  Click **Budgeting** \> **Common** \> **Budget plans** \> **All budget plans**. Double-click an existing budget plan, or create a new budget plan.

2.  In the **Filter by scenario** list, select a scenario. The **Scenario constraints** options in the **Budget planning configuration** form determine the view and edit access for each budget plan scenario. If the **Add line** button is not available, select a different scenario.

3.  In the **Budget plan lines** grid, click **Add line**.
    
    When you add a line to a budget plan scenario, the line is added only to the scenario in the current budget plan.

4.  Select an account structure and add the dimension values.

5.  View or make any required changes to the information in the remaining fields, such as **Effective date** and **Budget class**. Then enter the unit or monetary information.

6.  To allocate the budget amounts for the selected lines, click **Allocate budget**. Then enter or select information in the following fields that are displayed:
    
      - **Allocation method** – Select one of the following allocation methods:
        
          - **Allocate across periods** – Allocate the budget plan lines from the source budget plan scenario across periods in the destination scenario. Select the period allocation key in the **Period key** field.
        
          - **Allocate to dimensions** – Allocate the budget plan lines from the source budget plan scenario across the financial dimensions in the destination scenario. Select the budget allocation term in the **Allocation term** field.
        
          - **Aggregate** – Aggregate the budget plan lines from the source budget plan scenario in the associated budget plans to the destination scenario in the parent budget plan.
        
          - **Distribute** – Distribute the budget plan lines from the source budget plan scenario in the parent budget plan to the destination scenario in the associated budget plans.
        
          - **Use ledger allocation rules** – Starting with cumulative update 7 for Microsoft Dynamics AX 2012 R2, you can use ledger allocation rules for budget plan lines. Distribute the budget plan lines from the source budget plan scenario to the destination budget plan scenario according to the ledger allocation rule that is selected. Select a ledger allocation rule in the **Allocation rule** field.
    
      - **Budget plan scenario** (in the **Source** field group) – If you selected the **Aggregate** or **Use ledger allocation rules** allocation method, select the source scenario. If you did not select **Aggregate**, the source is the budget plan scenario that you selected in the **Filter by scenario** list.
    
      - **Budget plan scenario** (in the **Destination** field group) – If you selected any allocation method except **Aggregate**, select the destination budget plan. If you selected **Aggregate**, the destination is the budget plan scenario that you selected in the **Filter by scenario** list.
    
      - **Multiply by** – Enter a value by which to multiply the currency amounts or quantities for the selected lines.

7.  To add forecast positions, click **Select forecast positions** to open the **Select forecast positions** form. For information about how to add forecast positions, see “Add forecast positions to budget plan lines” later in this topic.

8.  Optional: Click **Line details**, and then enter or select information in the following fields:
    
      - **Project ID** or **Proposed project** – Select an existing project or a proposed project for the budget line.
    
      - **Fixed asset number** or **Proposed asset** – Select an existing asset or a proposed asset for the budget line.
    
      - **Position** – Select a forecast position for the budget line.
    
      - **Is recurring** – Select this check box if the budget line recurs each year.
    
      - **New request** – Select this check box if the budget line is a new request.
    
      - **Comment** – Enter a description or comment for the budget plan line.

9.  On the **Action Pane**, click **Refresh** to update the form.

To work with worksheets or justifications, continue to the next procedure.

Back to top

## Use worksheets and justifications in budget plans

Microsoft Dynamics AX can be integrated with Microsoft Word and Microsoft Excel by using the Office Add-ins for Microsoft Dynamics AX. Users can create Word justifications and Excel worksheets that are linked dynamically to the tables in Microsoft Dynamics AX. Integration for the Office Add-ins must be set up before users can use the Office Add-ins to create files.

A template author creates templates for the worksheets and justifications. The templates contain fields from the budget plans. The worksheets and justifications that are created by using the templates contain the data from the budget plan that you are working with.

Each budget plan has one justification template that you can use to create justification documents for that budget plan. Each budget planning stage can have a different template that you can use to create worksheets for that stage. When you save the justification or worksheet, it becomes a budget plan attachment.

When you create a justification, you can add information to support the budget plan. When you route the justification and the budget plan for review and approval, the reviewers can add comments and use change tracking to add information to the justification.

When you create a worksheet, you can import the data from multiple scenarios, analyze and modify the data, and then publish the data back to the budget plan.

For more information, see [Create budget plan templates manually](create-budget-plan-templates-manually.md).

### Import, modify, and publish budget plan data by using worksheets

1.  In the **Budget plan** form, on the **Action Pane**, click **Worksheet**. Information is exported to the worksheet.

2.  In Excel, you can analyze, chart, and update the amounts in the worksheet. Then, on the **Dynamics AX** tab, click **Publish** to import the updated information back to the budget plan.

3.  In Microsoft Dynamics AX, on the **Action Pane**, click **Refresh** to update the form.

### Create justifications for budget plans

1.  In the **Budget plan** form, on the **Action Pane**, click **Justification**.

2.  Use the features in Word to add and format information.

3.  Save the file and close Word.

Back to top

## Add forecast positions to budget plan lines

You can select specific forecast positions to add budget amounts for personnel to the budget plan lines. These budget amounts include salary, benefits, and counts of full-time equivalents (FTEs). For information about the budgets for forecast positions, see [Key tasks: Forecast positions](https://technet.microsoft.com/en-us/library/jj729760\(v=ax.60\)). For information about how to automatically generate a budget plan from all forecast positions, see [Generate budget plan from forecast positions (form)](https://technet.microsoft.com/en-us/library/jj677428\(v=ax.60\)).

1.  Click **Budgeting** \> **Common** \> **Budget plans** \> **All budget plans**. On the **Action Pane**, in the **New** group, click **Budget plan**.

2.  Enter or select the header information, such as the budget planning process and the responsibility center. Then click **Create**.

3.  In the **Filter by scenario** list, select a scenario that includes the **Monetary** unit of measure.

4.  Click **Add line**, and then enter or select the information for the line.

5.  To add one forecast position to the budget plan line, click **Line details**, and then select a forecast position in the **Position** list.

6.  To add multiple forecast positions to the budget plan line, follow these steps:
    
    1.  Click **Select forecast positions**.
    
    2.  Filter the positions by selecting a **Department** value and, optionally, a **Last modified date** value.
    
    3.  Select the check boxes next to the positions to add, and then click **Add** to add the positions to the selection grid.
        

        > [!TIP]
        > <P>In the <STRONG>Factor</STRONG> field in the selection grid, you can change the factor. For example, for half-time positions, change 1.0 to 0.50.</P>

    
    4.  To generate an FTE count, select a budget plan FTE scenario and an FTE main account. The FTE scenario must have a **Quantity** unit of measure.
    
    5.  Click **Generate**.

Back to top

## Submit a budget plan to workflow

To submit a budget plan to workflow, you must be either the preparer or a member of the budget planning user group that is assigned to the budget plan. Before you can submit the budget plan, all required fields must be entered, and the budget plan must contain at least one line item. The budget plan must also have a status of **Draft**.

For more information about how to configure workflow for budget plans, see [Set up Budgeting workflows](set-up-budgeting-workflows.md).

1.  Click **Budgeting** \> **Common** \> **Budget plans** \> **Budget plans prepared by me**.

2.  Select the budget plan to submit to workflow.

3.  In the workflow message bar, click **Submit**.

4.  In the **Comment** field that is displayed, enter a comment, and then click **Submit**.

5.  To recall a budget plan that you have submitted to workflow, in the workflow message bar, click **Actions** \> **Recall**.

6.  To view the workflow history for a budget plan that you have submitted to workflow, in the workflow message bar, click **Actions** \> **View history**.

Back to top

## Find form help

[Budget plan (form)](https://technet.microsoft.com/en-us/library/jj677376\(v=ax.60\))

[Budget planning process (form)](https://technet.microsoft.com/en-us/library/jj677441\(v=ax.60\))

[Budget planning configuration (form)](https://technet.microsoft.com/en-us/library/jj677418\(v=ax.60\))

## Find related tasks

[Key tasks: Configure budget planning and set up budget planning processes](key-tasks-configure-budget-planning-and-set-up-budget-planning-processes.md)

[Generate budget plans from source information](generate-budget-plans-from-source-information.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

