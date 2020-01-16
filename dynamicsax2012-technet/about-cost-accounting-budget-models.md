---
title: About cost accounting budget models
TOCTitle: About cost accounting budget models
ms:assetid: 3cf2d92b-895f-41d3-a064-106e48e7b807
ms:mtpsurl: https://technet.microsoft.com/library/Aa570267(v=AX.60)
ms:contentKeyID: 36056671
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About cost accounting budget models 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Click **Cost accounting** \> **Setup** \> **Budget model**. You create various budget models to enter budget costs.

A budget model can contain many submodels that you attach to the budget model on the **Submodel** tab. For example, you can create a budget with submodels that represent various departments of the company.


> [!NOTE]
> <P>Submodels can contain other submodels. Also, if you use budget control, budget models with submodels cannot be used in the calculation of the available budget balance. For more information, see <A href="about-basic-budgeting-and-budget-control-setup.md">About basic budgeting and budget control setup</A>.</P>



In **Cost accounting**, there are three different types of budget models:

  - **Cost budget** – Used for basic budgeting, such as budgeting of costs and services.

  - **Ledger budget** – Instead of creating a special budget in Cost accounting, you can use the ledger budget.

  - **Flexible budgeting**– Used for complex flexible budgets with planning for costs and services. You can also calculate different cost rates.


> [!NOTE]
> <P>Select the <STRONG>Stopped</STRONG> check box to indicate that the budget model and the budgets that are based on the budget model are blocked for modifications.</P>



## Cost accounting budget

Use the **Cost accounting budget** model type for standard budgeting of costs and services.

Click **Cost accounting** \> **Journals** \> **Cost budget**. You enter budget amounts for dimensions and cost categories.

In this form, only budget models of the **Cost accounting budget** type are available.

Click **Cost accounting** \> **Journals** \> **Service budget**. You enter budget amounts for **Service categories**.

## Ledger budget

Use the **Ledger budget** model type to use a budget from the **General ledger**. This is useful, because you do not have to create a new budget in Cost accounting.

When you use the **Ledger budget** model type, you must select a specific budget from the **General ledger** in the **Ledger budget** field on the **General** tab.

## Flexible budget

Use the **Flexible budgeting** model type for advanced budgeting, such as flexible planning of costs and services or planning of calculations. Before you work with the **Flexible budgeting** model type, you must enter the following settings:

Click **Cost accounting** \> **Setup** \> **Budget model**.

  - **Cost category setup**

  - **Dimension setup**

  - **Line structure** on the **General** tab

## See also

[About cost accounting budgeting](about-cost-accounting-budgeting.md)

[About flexible budgets](about-flexible-budgets.md)

  


