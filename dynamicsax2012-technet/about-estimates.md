---
title: About estimates
TOCTitle: About estimates
ms:assetid: 0a070d06-1236-409a-91bf-dd8a44a7bf25
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569736(v=AX.60)
ms:contentKeyID: 43881146
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- cost template
- cost line
- estimate
- completed contract
- completed percentage
- estimate structure
- contract value
audience: Application User
ms.search.region: Global
---

# About estimates 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

An estimate provides a snapshot of a project’s finances at a single point in time. The progress of a project to date is measured by factoring together the value of the transactions that have been incurred to date and a prediction of the cost to complete the project.

In Microsoft Dynamics AX, estimates are used for Investment projects and Fixed-price projects only.

## Estimates and Investment projects

For Investment projects, which have no immediate earnings, costs are entered on profit and loss accounts, and are transferred to work in process (WIP) accounts when estimates are posted. When the project is completed and project transactions are eliminated, the WIP value is transferred to a fixed asset, a ledger account, or a new project.

## Estimates and Fixed-price projects

For Fixed-price projects, the consumption cost is compared to the contract value to estimate the expected profit. Estimates are also applied to calculate the percentage of a project that has been completed, and to match and recognize cost and revenue on the profit and loss account in the same ledger period.

For Fixed-price projects, you can choose between the **Completed percentage** accounting principle and the **Completed contract** accounting principle, depending on your goals:

  - **Completed percentage** – The estimate is used to calculate the revenue during the project. Revenue is accrued based on the completion percentage and the contract value to match cost and revenue during the project.

  - **Completed contract** – The estimate is used at the end of the project to capitalize expenses, items, and hours to match cost and revenue on the profit and loss account.

## Cost lines and category grouping

Cost estimates are used to group categories in Fixed-price projects.

Every transaction on a project references a category, and every category references a cost line. This makes it possible to estimate how close to completion a Fixed-price project is.

This referencing also makes it possible to view estimates for individual cost lines. Expenses, hours, and items always reference three different cost lines. The benefit of this structure is that you can follow up on multiple transactions on a project by estimating the remaining work on a cost estimate.

By default, all existing categories are attached to three cost lines:

  - All hour categories are attached to the **Hour** cost line.

  - All expense categories are attached to the **Expense** cost line.

  - All item categories are attached to the **Item** cost line.

If you create additional cost lines in the **Cost lines** form, you must redefine one or more of your categories to refer to the new cost lines.

## Setup requirements for estimate projects

If you want to work with estimates for a project, you must attach the project to an estimate project.

You can create an estimate for an individual project or for a complete project hierarchy, which consists of a project and its subprojects. If you create estimates for a project hierarchy, the consumption on all projects in the hierarchy is included in one estimate calculation.

  - If you want to work with estimates for an individual project, the project itself must be defined as the estimate project.

  - If you want to work with estimates for a project hierarchy, the parent project must be defined as the estimate project.

Often, the contract amount of a project is based on the parent project. Therefore, you must select the parent project as an estimate project for all subprojects.


> [!NOTE]
> <P>The estimate project and all related projects must be attached to the same project group.</P>



## See also

[Create an estimate project](create-an-estimate-project.md)

[Set up estimates](set-up-estimates.md)

[Attach a project to an estimate](attach-a-project-to-an-estimate.md)

[About maintaining estimates](about-maintaining-estimates.md)

[About estimate periods](about-estimate-periods.md)

  


