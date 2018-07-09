---
title: About basic budgeting
TOCTitle: About basic budgeting
ms:assetid: 57dea2ae-d1f4-42d2-8276-2ab28dee4781
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa549062(v=AX.60)
ms:contentKeyID: 36057336
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- basic budgeting
- budget models
- budget register entries
- budgeting workflows
- financial dimensions for budgeting
- basic budget
---

# About basic budgeting [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Organizations, whether private or public, set financial and operational goals by creating budgets. The users who are responsible for setting up and maintaining budgets can do so by using the basic budgeting features in Budgeting.

You can use basic budgeting to define the financial dimensions for budgets, create budget models, and set up and use budget register entries. You can also set up optional Budgeting workflows to automate the review of budget register entries, including budget transfers.


> [!NOTE]
> <P>This topic includes information about financial budgets. For information about budgets for projects, see <A href="about-project-budgets-and-forecasts.md">About project budgets and forecasts</A>.</P>



## Financial dimensions for Budgeting

You can define financial dimensions for Budgeting to determine which financial dimensions and main accounts in the account structures that are associated with the chart of accounts are available for budgeting. Some organizations might not define a specific financial dimension for Budgeting, such as the main account, to allow for more flexibility. For example, an organization could define only the Department and Cost center financial dimensions for Budgeting. Then the combinations of departments and cost centers could hold budget amounts without regard to the specific main accounts.

## Budget models

Budget models identify budgets and can contain submodels. For example, you can create a budget that has submodels that represent the various departments of a legal entity.

## Budget register entries

Budget register entries are used to enter budget amounts and provide an audit trail of budgeting activities. You can define budget codes for any of the budget types to track the budget register entries. For example, you could assign a budget code of **Original** to the budget type of **Original budget**. On the **Budget register entry** FastTab in the **Budget register entry** form, you would select the budget model to identify the budget, and the **Original** budget code to identify the budget type. In the **Budget account entries** grid, you would add a line that identifies the account structure, financial dimension values, and budget amount.

  - The **Original budget** type is used for the approved budget amounts that are posted at the start of the budget year.

  - Transfers move amounts from one financial dimension value to another.

  - Revisions increase or decrease the budget.

  - Pre-encumbrances and encumbrances are available with budget control. These entries reserve budget funds for source documents such as purchase requisitions and purchase orders. They are often referred to as budget reservations in the private sector and commitments in other countries/regions.

  - Carry-forward entries can be used to indicate the unused budget amounts that were moved from one fiscal year to the next.

  - **Project**, **Fixed assets**, **Demand forecast**, and **Supply forecast** are the subledger budget transfer types that are used to transfer budget forecasts to general ledger budgets.

  - Public sector organizations can track preliminary budget register entries when the actual budget is being reviewed and approved. They can also use apportionment budget register entries to allocate part of a budgeted amount for spending in a specified time period.

## Budgeting workflows

You can set up Budgeting workflows so that a budget manager can approve budget register entries. For example, if approval is required when budget amounts are transferred from one department to another, an approval workflow can route the budget transfer for approval. You can also set up budget transfer rules to allow for transfers between specific financial dimensions or financial dimension values. For example, you can set up a budget transfer rule that allows for budget transfers only within a department. If a budget transfer rule was violated by a budget transfer between departments, a Budgeting workflow could route the transfer to a specific user or user group for approval.

## Basic budgeting setup

Before you use basic budgeting, complete the steps that are described in the following topics. If you are using budget control, you must set up basic budgeting before you configure budget control.

  - Required: [Define budget exchange rates](define-budget-exchange-rates.md)

  - Required: [Define Budgeting parameters and number sequences](define-budgeting-parameters-and-number-sequences.md)

  - Required: [Define financial dimensions for Budgeting](define-financial-dimensions-for-budgeting.md)

  - Required: [Create budget models](create-budget-models.md)

  - Required: [Define budget codes](define-budget-codes.md)

  - Optional: [Define budget transfer rules](define-budget-transfer-rules.md)

  - Optional: [Set up Budgeting workflows](set-up-budgeting-workflows.md)

  - Optional: [Set up budget allocation terms](set-up-budget-allocation-terms.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

