---
title: About setting up a budget model for flexible budgets
TOCTitle: About setting up a budget model for flexible budgets
ms:assetid: d36935bf-aac1-475b-8087-4bd9b1bfed53
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551075(v=AX.60)
ms:contentKeyID: 36059512
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# About setting up a budget model for flexible budgets [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You set up the budget model for a flexible budget in the **Budget model** form. Select **Flexible budgeting** in the **Budget model type** field. When you select this type of budget model, you have the following options:

  - To set up dimensions manually by clicking the **Dimension setup** button, select the **Check dimensions** check box on the **General** tab. Otherwise, the dimensions are available in the dimension setup when plan values have been entered in the flexible budget.

  - To set up the cost categories, service categories, and cost lines to plan on, click **Cost category setup**.

  - To set up the dimensions to plan on in the flexible budget, click **Dimension setup**.

## Cost category setup

Use the **Cost category setup** form to specify the cost categories, service categories, or cost lines that you want to plan on in the flexible budget. These are displayed automatically in the flexible budget. You must decide whether the planning of costs is based on cost categories or cost lines.

If planning is based on cost lines, select the **Budget** check box for the required cost lines on the **Cost lines** tab of the **Cost category setup** form. If you do this, you cannot plan on the cost or service categories that are included in these cost lines.

The cost and service categories are displayed in blue in the flexible budget, and you cannot enter values for them.

## Cost categories tab

On the **Cost categories** tab, enter the cost categories to plan on and select a period key for each cost category. If you leave the **Period key** field blank, the planning on this cost category is linear. You set up period allocation keys in the **Period allocation key** form in General ledger.

If an entry was made in the **Calculation setup** form for this cost category, the **Calculated** check box is selected. This means that the plan value for this cost category is calculated from the plan values of the other cost category.

Click **Load cost categories** to create a query to enter the cost categories automatically. This is especially useful if you are entering all cost categories. You can still modify the list of cost categories after you load it.

Click **Calculation setup** to use the **Calculation setup** form, in which you can implement a proportional dependency on another cost category. This means that the plan value in the flexible budget is not entered manually. Instead, it is calculated according to this calculation setup as a percentage of another plan value. Select a cost category in the **Cost category** field and enter a percentage in the **Percent** field. You can also select the **Invert sign** check box to indicate that the calculated plan value has the opposite sign from the typical planned value.

## Service categories tab

On the **Service categories** tab, enter the service categories to plan on and select a period key for each service category. If you leave the **Period key** field blank, the planning on this service category is linear.

Click **Load service categories** to create a query to enter the service categories automatically. This is especially useful if you are entering all service categories.

You can modify the list of service categories after you load it.

## Cost lines tab

On the **Cost lines** tab, enter the cost lines to plan on, and select values in the following fields for each cost line, as appropriate:

  - Select the **Budget** check box to base the costs on a cost line instead of planning values on the cost categories that are included in this cost line.

  - Select a period key. If you leave the **Period key** field blank, the planning on this cost line is linear.

  - To use this cost line for planning, use the **Share fixed costs** and **Share variable costs** fields to define cost shares for the cost line.

  - If an entry was made in the **Calculation setup** form for this cost line, the **Calculated** check box is selected. This means that the plan value for this cost line is calculated from the plan values of the other cost line.

  - Click **Calculation setup** to open the **Calculation setup** form, in which you can implement a proportional dependency on another cost line. This means that the plan value in the flexible budget is not entered manually. Instead, it is calculated according to this calculation setup as a percentage of another plan value. In the **Calculation setup** form, select a cost line in the **Cost line** field and enter a percentage in the **Percent** field. You can also select the **Invert sign** check box to indicate that the calculated plan value has the opposite sign from the typical planned value.

  - Click **Cost allocation** to open the **Cost allocation** form, in which you can define, as a percentage, how the planned costs that are based on this cost line are allocated among the cost categories that are included in this cost line. If a cost allocation is not defined, all planned costs that are based on the cost line are allocated to the first cost category that is included in this cost line.

## Dimension setup

Use the **Dimension setup** form to specify the dimensions to plan on in the flexible budget. You can select dimensions manually only if the **Check dimensions** check box on the **General** FastTab of the **Budget model** form is selected. Otherwise, each dimension is automatically displayed in the **Dimension setup** form when plan costs have been entered for the dimension in the flexible budget.

When you enter dimensions, you must select values in the following fields for each dimension:

  - **Dimension** – The type of dimension.

  - **Number** – The dimension number. If no number is selected in this field, the costs can be planned without a defined dimension. These costs can later be distributed on dimensions by using the cost distribution.

  - **Locked for journal** – If this check box is selected, you cannot plan on this dimension in the flexible budget.

  - **Determination of load** – If you are working with a workload in the flexible budget, you can select whether to enter data manually or to have data be loaded automatically.

  - **Service category** – This check box is selected when the **Determination of load** field is set to service category.

To delete plan costs for a specific dimension, delete the dimension in the **Dimension setup** form. All plan costs for this dimension are deleted automatically in the flexible budget.

## See also

[Flexible budgets](flexible-budgets.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

