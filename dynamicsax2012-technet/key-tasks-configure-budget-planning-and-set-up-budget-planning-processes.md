---
title: 'Key tasks: Configure budget planning and set up budget planning processes'
TOCTitle: 'Key tasks: Configure budget planning and set up budget planning processes'
ms:assetid: 70ce9e1b-d81c-4568-b631-e4cc929141de
ms:mtpsurl: https://technet.microsoft.com/library/JJ677344(v=AX.60)
ms:contentKeyID: 49384118
author: Khairunj
ms.date: 11/19/2014
mtps_version: v=AX.60
f1_keywords:
- budget plan
- budget planning
- budget plans
- plan budget
audience: Application User
ms.search.region: Global
---

# Key tasks: Configure budget planning and set up budget planning processes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to configure budget planning and set up budget planning processes. When you configure budget planning, you define elements such as budget plan scenarios and budget planning stages that you use when you set up a budget planning process. When you set up a budget planning process, you combine the budget planning elements into a single process for a budget cycle, ledger, and budget organization hierarchy.

Before you can configure budget planning, you must set up a budget organization hierarchy, budget plan templates, and budgeting workflows. For more information, see [Budget planning overview](budget-planning-overview.md) and [About budget planning configuration and setup](about-budget-planning-configuration-and-setup.md).


> [!NOTE]
> <P>The procedure for completing this task changed for cumulative update 7 or later for Microsoft Dynamics AX 2012 R2. The updated procedure also applies to AX 2012 R3. For more information, see the section later in this topic.</P>



## What do you want to do?

Learn more about...

Configure budget planning

Set up budget planning processes

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[Budget planning overview](budget-planning-overview.md)

[About budget planning configuration and setup](about-budget-planning-configuration-and-setup.md)

[About budget plans](about-budget-plans.md)

## Configure budget planning

The key elements that you need to configure for budget planning include:

  - Budget plan scenarios that categorize and contain the data for the lines in the budget plans.

  - Budget planning stages that the budget plans must follow.

  - Budget planning workflows arrange the stages and provide the structure for the access levels and permissions users must have to view and modify budget plan lines.

Additional configurable elements include scenario constraints, allocation schedules and stages, priorities, and locations for attachments and templates. After you configure budget planning, you can set up one or more budget planning processes.


> [!NOTE]
> <P>If your organization has workplaces in multiple countries/regions, you can specify translated text for the names and descriptions of scenarios, stages, workflows, and priorities. For more information, see <A href="https://technet.microsoft.com/library/hh697726(v=ax.60)">Text translation (form)</A>.</P>



### Specify budget plan parameters

1.  Click **Budgeting** \> **Setup** \> **Budget planning** \> **Budget planning configuration**.

2.  In the **Parameters** area, in the **Security** field group, select how you want to control access to the budget plans.
    
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
    <td><p><strong>Security model</strong></p></td>
    <td><p>The security for budget plans is determined by the security model that you select for each legal entity in your organization.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>Based on worker positions</strong> – All budget plan preparers who are associated with workers whose positions report to an organization unit in the budget planning organization hierarchy can access the budget plans.</p></li>
    <li><p><strong>Based on security organizations</strong> – All users who are granted access to an organization in the security roles can access the budget plans for that organization. To enable this security model, the organization hierarchy used must have both Security and Budget planning purposes assigned. For more information, see <a href="organization-hierarchies.md">Organization hierarchies</a>, <a href="configure-budget-planning-security.md">Configure budget planning security</a>, and <a href="configuring-budget-planning-for-microsoft-dynamics-ax-2012-r2.md">Configuring Budget Planning for Microsoft Dynamics AX 2012 R2</a>.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Allow access to budget plans by user group</strong></p></td>
    <td><p>Select this check box if you want to control access to specific budget plans by user group.</p>
    <p>If you select this check box, you’ll specify the user group that can access the budget plan for each budget plan in the <strong>Budget plan</strong> form.</p>
    <p>If you don’t select this option, all users who have access to the <strong>Budget plan</strong> form can access the budget plans based on the security model selection in the <strong>Budget planning configuration</strong> form.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The user must have access to the responsibility center in the budget planning hierarchy to be able to create a budget plan for this responsibility center. The user can view and edit budget plans if they are part of the user group assigned to the budget plan even if they don’t have access to the budgeting organization hierarchy responsibility center.</P>


    </div></td>
    </tr>
    </tbody>
    </table>


3.  To reduce the time that is required to export budget plan lines to Microsoft Excel, select the **Limit the associated budget plan lines to include** check box, and then select the number of levels of child budget plans to include in Excel workbooks. To export all budget plan lines for all child budget plans, clear the **Limit the associated budget plan lines to include** check box.

### Create budget plan scenarios

1.  Click **Budgeting** \> **Setup** \> **Budget planning** \> **Budget planning configuration**.

2.  In the **Scenarios** area, click **Add** and enter a name and a description for the budget plan scenario. When they are displayed in the **Filter by scenario**, the scenarios are sorted by name. Therefore, we recommend that you use a consistent naming convention so that you can easily sort and identify the scenarios. For example, you might start the scenarios with a year so that all the scenarios for particular year are sorted together.

3.  Select a unit of measure class. **Monetary** is the typical unit of measure class, but you can select **Quantity** if the scenario includes quantitative data. If you select **Quantity**, a default unit of measure of **Each** is displayed. For more information, see [Unit setup (form)](https://technet.microsoft.com/library/aa596781\(v=ax.60\)).

### Create budget planning stages

1.  Click **Budgeting** \> **Setup** \> **Budget planning** \> **Budget planning configuration**.

2.  Click **Stages**.

3.  Click **Add** and enter a name and a description for the budget planning stage.

### Create budget planning workflows

1.  Click **Budgeting** \> **Setup** \> **Budget planning** \> **Budget planning configuration**.

2.  Click **Workflows**.

3.  Click **Add** and enter a name and a description for the budget planning workflow.

4.  Select a workflow ID. Make sure that the stage transitions and the other elements and tasks in the workflow are set up for the stages in the budget planning workflow. For more information, see “Workflows” in [About budget planning configuration and setup](about-budget-planning-configuration-and-setup.md).

5.  Select the stages and move them to the **Selected planning stages** list. Make sure that the planning stages are in the correct order.

### Define scenario constraints

1.  Click **Budgeting** \> **Setup** \> **Budget planning** \> **Budget planning configuration**.

2.  Click **Scenario constraints**.

3.  Click **Add** and select a budget planning workflow.

4.  Select a budget plan scenario.

5.  In the **Access level** field, select either **View** or **Edit**. The permissions for viewing and editing budget planning data is determined by this access level, and also by whether the **Add lines** and **Modify lines** check boxes are selected for each **Budget planning stage** that you select in the **Budget planning process** form. For more information, see “Budget planning stage rules and scenario constraints” in [About budget planning configuration and setup](about-budget-planning-configuration-and-setup.md).

### Define allocation schedules and stage allocations for the automated workflow allocation task

1.  Click **Budgeting** \> **Setup** \> **Budget planning** \> **Budget planning configuration**.

2.  Click **Allocation schedules**.
    

    > [!NOTE]
    > <P>The allocation in the allocation schedule occurs during an automated workflow process. The scenario constraints and stage rules must be set up correctly for the workflow process to access the data in the source scenarios and allocate it to the destination scenarios. For more information, see “Budget planning stage rules and scenario constraints” in <A href="about-budget-planning-configuration-and-setup.md">About budget planning configuration and setup</A>.</P>



3.  Click **Add**, enter a name for the allocation schedule. Enter or select the following information:
    
      - **Allocation method** – Select one of the following allocation methods:
        
          - **Allocate across periods** – Allocate the budget plan lines from the source budget plan scenario across periods in the destination scenario. Select the period allocation key in the **Period key** field.
        
          - **Allocate to dimensions** – Allocate the budget plan lines from the source budget plan scenario across the financial dimensions in the destination scenario. Select the budget allocation term in the **Allocation term** field.
        
          - **Aggregate** – Aggregate the budget plan lines from the source scenario in the associated budget plans to the destination scenario in the parent budget plan.
        
          - **Distribute** – Distribute the budget plan lines from the source budget plan scenario in the parent budget plan to the destination scenario in the associated budget plans.
        
          - **Use ledger allocation rules** – Distribute the budget plan lines from the source budget plan scenario to the destination budget plan scenario according to the ledger allocation rule that is selected.
            
            This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.
    
      - **Source scenario** – Select the source scenario.
    
      - **Destination scenario** – Select the destination scenario.
    
      - **Multiply by** – Enter a value by which to multiply the currency amounts or quantities for the budget plan lines.
    
    For more information, see “Allocations” in [About budget planning configuration and setup](about-budget-planning-configuration-and-setup.md).

4.  Click **Budgeting** \> **Setup** \> **Budget planning** \> **Budget planning configuration**.

5.  Click **Stage allocations**.

6.  Click **Add** and select a budget planning stage and budget planning workflow.

7.  Select an allocation schedule.

### Define budget plan priorities

1.  Click **Budgeting** \> **Setup** \> **Budget planning** \> **Budget planning configuration**.

2.  Click **Priorities**.

3.  Click **Add** and enter a name and a description for the priority.
    
    For more information, see “Budget planning priorities” in [About budget planning configuration and setup](about-budget-planning-configuration-and-setup.md).

### Select folders for attachments

1.  Click **Budgeting** \> **Setup** \> **Budget planning** \> **Budget planning configuration**.

2.  Click **Folders**.

3.  Click **Add**, browse to the folder, and then click **OK**.

### Select templates for the budget planning process

1.  Click **Budgeting** \> **Setup** \> **Budget planning** \> **Budget planning configuration**. Click **Templates**.

2.  Click **Add**, browse for the file, and then click **Open**.

3.  Select the template type, which is either **Justification** or **Worksheet**.

Back to top

## Set up budget planning processes

Budget planning processes determine how budget plans can be updated, routed, reviewed, and approved in the budgeting organization hierarchy. After you set up and activate a budget planning process, users can create budget plans and submit them to workflow for updates, reviews, and approvals.

1.  Click **Budgeting** \> **Setup** \> **Budget planning** \> **Budget planning process**.

2.  Click **New**.

3.  Enter a name and a description for the budget planning process, and then select the budget cycle and ledger.

4.  On the **Template folder** FastTab, select the justification template to use to create justifications for the budget plans that are created by using this budget planning process. Select the attachment folder that you want to use to store the attachments to the budget plans that are created by using this budget planning process.

5.  On the **Budget planning process administration** FastTab, select the budget planning organization hierarchy. Select the budget planning workflow for each responsibility center. To assign a budget planning workflow to similar types of responsibility centers, click **Assign workflow**, and then select the organization type and budget planning workflow.

6.  On the **Budget planning stage rules and templates** FastTab, select a budget planning workflow.

7.  For each budget planning stage, define the following options:
    
      - **Associate budget plans** – Select this check box if budget plans can be associated with a parent budget plan in this planning stage.
    
      - **Add lines** – Select this check box if budget plan lines can be added during this budget planning stage.
    
      - **Modify lines** – Select this check box if budget plan lines can be modified during this budget planning stage.
    
      - **Template** – Select the template to use when you create worksheets for this budget planning stage. Each stage can have a unique worksheet template.
    
    The permissions for the budget planning data is determined by the scenario constraints that you select in the **Budget planning configuration** form, and by whether the **Add lines** and **Modify lines** check boxes are selected for each budget planning stage. For more information, see “Budget planning stage rules and scenario constraints” in [About budget planning configuration and setup](about-budget-planning-configuration-and-setup.md).

8.  On the **Budget plan priority constraints** FastTab, select the priorities that can be assigned to the budget plans in this budget planning process.

9.  When you click **Activate** for the budget planning process, the **State** field value at the top of the form changes from **Draft** to **In process**. Users then can create budget plans by using this budget planning process.

10. After all the budget plans that used this budget planning process are complete, you can click **Complete**. The budget planning process can no longer be used to create budget plans, and the **State** field value changes to **Completed**.


> [!NOTE]
> <P>We recommend that you use Management Reporter for Microsoft Dynamics ERP to create, maintain, deploy, and view financial reports that include budget planning data. Management Reporter lets you design financial reports based on ledger accounts and financial dimensions, drill down to transaction-level detail, and use web-based report viewing. For more information about how to print financial reports by using Management Reporter, see <A href="https://go.microsoft.com/fwlink/?linkid=324762">Management Reporter for Microsoft Dynamics ERP</A>.</P>
> <P>You can use Management Reporter to report on budget planning data only if you have rollup 4 or a later version of Management Reporter 2012 installed.</P>



Back to top

## Find form help

[Budget planning configuration (form)](https://technet.microsoft.com/library/jj677418\(v=ax.60\))

[Budget planning process (form)](https://technet.microsoft.com/library/jj677441\(v=ax.60\))

## Find related tasks

[Key tasks: Create and process budget plans](key-tasks-create-and-process-budget-plans.md)

[Generate budget register entries from budget plans](generate-budget-register-entries-from-budget-plans.md)

[Configure budget planning security](configure-budget-planning-security.md)

  


