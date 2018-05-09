---
title: About basic budgeting and budget control setup
TOCTitle: About basic budgeting and budget control setup
ms:assetid: ae172470-3248-4564-9cfa-a4bac0726af0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242705(v=AX.60)
ms:contentKeyID: 36058938
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- basic budgeting setup
- budget concepts
- budget control setup
- budget control concepts
- concepts about budget control
- set up budget control
- concepts about budgets
- set up basic budgeting
---

# About basic budgeting and budget control setup 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains the setup for basic budgeting and budget control. For more information about what you have to do before you start the setup, see [Basic budgeting and budget control setup overview](setup-overview-basic-budgeting-and-budget-control.md).


> [!NOTE]
> <P>This topic includes information about financial budgets. For information about budgets for projects, see <A href="about-project-budgets-and-forecasts.md">About project budgets and forecasts</A>.</P>



## Basic budgeting

To create a budget for your organization, you establish budget amounts for the financial dimension values of the financial dimensions that are enabled for Budgeting. Typically, you establish budget amounts for all activities that are related to expenses. To establish budget amounts for financial dimension values, you first create a budget register entry that has a type of **Original budget**. After you update the budget balances, the financial dimension values have a budget.

When you view all budget register entries that have the same budget model, you can see a budget scenario for the organization. For more information, see [Create budget models](create-budget-models.md). As you make revisions and updates to the initial budget amount, more budget register entries are created.

Because budget register entries can involve more than one currency, you define exchange rates for the budget rate type before you start submitting budget register entries.


> [!IMPORTANT]
> <P>After you create a budget register entry for a financial dimension or ledger account, you cannot close or delete that financial dimension or account.</P>



## Budget control

Budget control includes all the functionality of basic budgeting, and also budget control. Budget control is a method of enforcing that sufficient budget funds are available for planned or actual purchases. For example, you can prevent a purchase order from being confirmed if the budget funds are insufficient to satisfy the purchase.

## Budget checking

You can use budget checking and budget thresholds to prevent users in a specific user group from processing source documents. For example, if 90 percent of a budget has been used, you can use budget checking to inform users that the available budget balance or budget threshold was exceeded, and prevent or allow processing.

## Budget control rules and budget groups

When you configure budget control, you can define budget control rules and budget groups. Budget control rules determine the financial dimension value combinations for budget control. You can also define budget groups to form a budget pool, or collection of financial dimension values whose budgets will be pooled for a secondary budget check. The financial dimension combinations in the budget control rules are always checked for budget amounts. If a financial dimension combination is also in a budget group, a second budget check is performed at the budget-group level.

For example, if you have a budget control rule for all combinations of the department and cost center dimensions, you could also define a budget group for Department 010 and select all the cost centers in that department. This budget group would pool the budget of all the cost centers for Department 010. After an initial budget check failed for a cost center in Department 010, a second budget check would be performed on the aggregate budget for all the cost centers in Department 010.

For more information, see [Examples: Budgeting and budget control](examples-budgeting-and-budget-control.md).

## Revenue amounts

For revenue amounts, budget register entries that have an amount type of **Revenue** can be used to create the revenue goal for a financial dimension combination. Revenue amounts have a budget calculation that is separate from the one that is used for expenses. To help prevent a user from creating a revenue goal that is not realistic, such as a goal that is less than zero, you can require a warning or prevent budget register entries from being processed. This warning or prevention is the only time when the budget calculation for revenue amounts is used. Unlike expense amounts, there is no threshold for revenue amounts. Also unlike expenses, if you use up the budget amount, you have reached your revenue goal. At that point, users can continue to process additional revenue amounts as sales continue. Therefore, budget control to prevent processing is not needed.

## See also

[Examples: Budgeting and budget control](examples-budgeting-and-budget-control.md)

[Create budget register entries](create-budget-register-entries.md)

[About basic budgeting](about-basic-budgeting.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

