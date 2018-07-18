---
title: 'Key tasks: Create and maintain indirect costs'
TOCTitle: 'Key tasks: Create and maintain indirect costs'
ms:assetid: d9649c64-1c6e-4912-b361-3919675f9646
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh227398(v=AX.60)
ms:contentKeyID: 36059650
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- project add-in
- compounding rules
- indirect costs
- cost components
- indirect cost compounding rules
- indirect cost component groups
audience: Application User
ms.search.region: Global
---

# Key tasks: Create and maintain indirect costs 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Indirect costs are costs such as rent, office supplies, telephone charges, and computer support, which are often shared among various projects. You can associate indirect costs with projects and set up the method for calculating the amount of indirect costs to post to a project.

When you identify the indirect costs to associate with a project, you can set up indirect cost component groups to track a group of indirect costs for the project. You can set up compounding rules to increase the value that is added to a project for an indirect component’s cost, revenue, or invoice amount.

After you have set up the indirect cost components, indirect cost component groups, and compounding rules, you can assign an indirect cost component group to a project for a specific customer. When you create an invoice for the customer, indirect costs are calculated based on the hours charged to the project. You can assign a specific value per hour, or you can select a percentage of the hourly cost of workers assigned to a project.

## What do you want to do?

Learn more about...

Set up project categories for indirect cost components

Set up indirect cost components

Set up indirect cost component groups

Assign indirect cost components to a group

Define indirect cost compounding rules

Assign indirect cost component groups to a project

Find form help

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About indirect costs for projects](about-indirect-costs-for-projects.md)

## Set up project categories for indirect cost components

Use this procedure to set up a project category that defines how indirect costs are posted to financial accounts. When you assign the category to a project, the expenses associated with the category are allocated as indirect costs to the project.


> [!NOTE]
> <P>If you set up a category for indirect costs, you cannot associate the category with direct costs on projects.</P>



1.  Click **Project management and accounting** \> **Setup** \> **Categories** \> **Project categories**.

2.  In the **Project categories** form, create a new category, or select an existing category in the list.

3.  Enter any required information about the category.

4.  On the **Project** FastTab, select the **Indirect cost component** check box to use this project category for indirect cost components.

For more information about how to set up project categories, see [About project category groups](about-project-category-groups.md). For more information about the **Project categories** form, see [Project categories (form)](https://technet.microsoft.com/en-us/library/aa582118\(v=ax.60\)).

Back to top

## Set up indirect cost components

Use this procedure to create an indirect cost component and associate it with a project category that is designated for use with indirect cost components.

1.  Click **Project management and accounting** \> **Setup** \> **Indirect costs** \> **Indirect cost components**.

2.  Click **New** to create a new indirect cost component.

3.  In the **Indirect cost component** field, enter a unique short name.

4.  In the **Name** field, enter a descriptive name.

5.  Select a project category for the indirect cost component. The financial accounts used to post the indirect costs are defined in the project category that you select.
    

    > [!NOTE]
    > <P>You can select only categories that were set up for indirect costs.</P>



6.  You can now set up indirect cost component groups.

For more information about how to set up indirect cost components, see [Indirect cost component (form)](https://technet.microsoft.com/en-us/library/hh208810\(v=ax.60\)).

Back to top

## Set up indirect cost component groups

Use this procedure to create indirect cost component groups to which you can assign indirect cost components.

1.  Click **Project management and accounting** \> **Setup** \> **Indirect costs** \> **Indirect cost component groups**.

2.  Click **New** to create a new indirect cost component group.

3.  In the **Indirect cost component group** field, enter a unique short name.

4.  In the **Indirect component group name** field, enter a descriptive name.

5.  You can now assign indirect cost components to the group.

For more information about how to set up indirect cost component groups, see [Indirect cost component groups (form)](https://technet.microsoft.com/en-us/library/hh209621\(v=ax.60\)).

Back to top

## Assign indirect cost components to a group

After you create an indirect cost component group, you can assign indirect cost components to the group. Each indirect cost component group must include at least one indirect cost component. Indirect cost components can be associated with more than one group.

1.  Click **Project management and accounting** \> **Setup** \> **Indirect costs** \> **Indirect cost component groups**.

2.  In the **Indirect cost component groups** form, click **Assign indirect cost components**.

3.  In the **Assigned indirect cost components** form, click **New**.

4.  In the **Date** field, enter the date that the indirect cost component rule is effective.

5.  In the **Indirect cost component** field, select the indirect cost component to include in the indirect cost component group.

6.  In the **Calculate method** field, select one of the following options:
    
      - **Percent** – The indirect cost is calculated as a percentage of the transaction cost for a worker’s hours posted to a project.
    
      - **Unit rate** – The indirect cost is calculated as an amount per hour of work posted to a project.

7.  In the **Cost rate** field, enter the rate, either as a percentage or as a value, to use to calculate the amount of the indirect cost. If you enter a percentage, the percentage is multiplied by the worker’s hourly rate. If you enter a value, the value is multiplied by the number of hours posted to the project.

8.  In the **Revenue rate** field, enter the rate, either as a percentage or as a value, to use to calculate the amount of revenue to post to the project. If you enter a percentage, the percentage is multiplied by the worker’s hourly rate. If you enter a value, the value is multiplied by the number of hours posted to the project.

9.  In the **Invoice rate** field, enter the rate, either as a percentage or as a value, to use to calculate the amount to add to the customer invoice. If you enter a percentage, the percentage is multiplied by the worker’s hourly rate. If you enter a value, the value is multiplied by the number of hours posted to the project.

10. Optionally, you can create indirect cost compounding rules.

For more information about how to assign indirect cost components to a group, see [Indirect cost component group assignment rules (form)](https://technet.microsoft.com/en-us/library/hh227451\(v=ax.60\)).

Back to top

## Define indirect cost compounding rules

Use this procedure to select indirect cost components to use to create compounding rules, and to specify the multiplier for the indirect cost. A compounding rule adjusts the value that is added to a project for the selected indirect component’s cost, revenue, or invoice amount. In the **Assigned indirect cost components** form, you can also set the sequence in which the compounding rules are calculated by changing the sequence in which the indirect cost components are displayed in the list.


> [!NOTE]
> <P>The indirect cost component must use a percentage calculation method to create compounding rules.</P>



There are three rate types for which you can create compounding rules:

  - **Cost**

  - **Revenue**

  - **Invoice**

For each rate type, you define the basis of the percentage calculation method as a combination of the indirect costs that you select for the compounding rule.

1.  In the **Assigned indirect cost components** form, click **Compounding rules**, and then click the type of compounding rule to create.

2.  In the **Compounding rules** form for the rate type that you selected, select an indirect cost component. If you select an indirect cost component that uses a unit rate calculation method, you do not select an indirect cost component to use as the basis of calculation, because the basis of calculation is always hours from a timesheet.
    

    > [!NOTE]
    > <P>By default, the indirect cost components are listed in the same sequence as they are listed in the <STRONG>Assigned indirect cost components</STRONG> form. To change the sequence of the indirect cost components, use the <STRONG>Move up</STRONG> and <STRONG>Move down</STRONG> buttons. You cannot move an indirect cost component before the indirect cost component it depends on.</P>



3.  In the **Available indirect cost components** list, select the indirect cost component to include in the compounding rule, and then click **Add**. The selected indirect cost component is displayed in the **Selected indirect cost components** list.
    

    > [!NOTE]
    > <P>All indirect cost components have <STRONG>Base amount</STRONG> available as a selection, which represents the cost for worker hours posted to the project from timesheets.</P>



4.  Continue to select available indirect cost components until you complete the compounding rule. If you want to remove an indirect cost component from the list of selected components, select the indirect cost component, and then click **Remove**.

For more information about how to create compounding rules for indirect cost components, see [Compounding rules - Cost (form)](https://technet.microsoft.com/en-us/library/hh227384\(v=ax.60\)), [Compounding rules - Revenue (form)](https://technet.microsoft.com/en-us/library/hh209617\(v=ax.60\)), and [Compounding rules - Invoice (form)](https://technet.microsoft.com/en-us/library/hh242812\(v=ax.60\)).

Back to top

## Assign indirect cost component groups to a project

Use this procedure to assign an indirect cost component group to a project. When you assign the indirect cost component group to the project, you must also select the worker whose hours are the basis for calculating the indirect costs for the indirect cost component group.

The hours posted by the worker that you select in the **Indirect cost component group assignment rules** are multiplied by the indirect cost rule that you created in the **Assigned indirect cost components** form. The resulting indirect costs are added to the project.

1.  Click **Project management and accounting** \> **Setup** \> **Indirect costs** \> **Indirect cost component group assignment rules**.

2.  Click **New** to assign an indirect cost component group to a project contract.

3.  In the **Effective** field, enter the date on which the calculation of the indirect cost rule starts.

4.  Select the customer account of the customer for the project contract.

5.  Select the project contract ID that is associated with the customer for whom to calculate indirect costs.

6.  Select a category that describes the work performed by a resource on the project. The transaction type is always **Hour**, and the category must be set up for indirect costs.

7.  Select a worker. The hours charged by the worker that you select are multiplied by the indirect cost rule.

8.  Select a project associated with the project contract.

9.  Select the indirect cost component group to use to calculate indirect costs for the project contract.

For more information about how to assign indirect cost components groups to a project contract, see [Indirect cost component group assignment rules (form)](https://technet.microsoft.com/en-us/library/hh227451\(v=ax.60\)).

Back to top

## Find form help

[Indirect cost component (form)](https://technet.microsoft.com/en-us/library/hh208810\(v=ax.60\))

[Indirect cost component groups (form)](https://technet.microsoft.com/en-us/library/hh209621\(v=ax.60\))

[Indirect component transaction (form)](https://technet.microsoft.com/en-us/library/hh209467\(v=ax.60\))

[Assigned indirect cost components (form)](https://technet.microsoft.com/en-us/library/hh209589\(v=ax.60\))

[Indirect cost component group assignment rules (form)](https://technet.microsoft.com/en-us/library/hh227451\(v=ax.60\))

  


