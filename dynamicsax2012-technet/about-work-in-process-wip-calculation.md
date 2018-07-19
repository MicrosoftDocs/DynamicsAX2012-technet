---
title: About work in process (WIP) calculation
TOCTitle: About work in process (WIP) calculation
ms:assetid: ecc03d50-ae70-4079-a3b3-3fad31040d9e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551530(v=AX.60)
ms:contentKeyID: 42520742
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- WIP structure
- WIP calculation
- WIP to cost value
- WIP to sales value
- work in process
audience: Application User
ms.search.region: Global
---

# About work in process (WIP) calculation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A work in process (WIP) amount is the total accumulated costs or revenue on a project that is still in progress. Depending on the project group, actual project costs and revenue for hours, expenses, and items can be posted to a WIP financial account on the balance sheet. When you invoice a customer for a project or close an internal project, the accumulated costs for the project are reversed from the WIP account.

On external projects, calculating a WIP amount ensures that the costs and revenue that are recorded for projects are recognized and posted on the profit and loss statement in the same accounting period.

On internal Investment projects, a WIP amount is calculated in anticipation of costs being capitalized on balance sheet accounts when the project is completed.

You can calculate WIP values based on cost value or sales value. The method that you use depends on the project type. The following table provides details about each method.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Method</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>WIP - cost value</strong></p></td>
<td><p>Actual costs for hours, expenses, and items are posted to a financial account on the balance sheet. When costs on a project are invoiced to the project customer or an internal project is completed, the costs and associated revenue are posted to profit and loss accounts.</p>
<p>This option is available for all project types.</p></td>
</tr>
<tr class="even">
<td><p><strong>WIP - sales value</strong></p></td>
<td><p>When actual costs are posted to a project, the costs are accrued as revenue. This is done by crediting a revenue account on the profit and loss statement and debiting a <strong>WIP - sales value</strong> account.</p>
<p>This option is available only for Fixed-price projects and Time and material projects.</p></td>
</tr>
</tbody>
</table>


The following sections explain how to apply WIP amounts to different project types.

## Time and material projects and Fixed-price projects

For both Time and material projects and Fixed-price projects, WIP amounts are calculated periodically by using batch jobs or when projects are invoiced, depending on the ledger settings that you select in the **Project groups** form.

For Time and material projects, the WIP amounts are posted to an invoice. For Fixed-price projects, they are posted to an estimate.

## Internal projects

For internal projects, the WIP amount is calculated periodically by using batch jobs or journal entries, depending on the ledger settings that you select for the project group. The WIP amount that is posted is only calculated at the actual cost price. The posting activity is the same as when calculating WIP amounts for Time and material projects.

## Investment projects

For Investment projects, the WIP amount is posted by using the estimate system in **Project management and accounting**. WIP amounts can only be calculated at the cost price. Revenue is accrued during the project to match actual costs on the profit and loss statement, and the estimated WIP amount is calculated as a percentage of the sales price.

## See also

[Create an estimate project](create-an-estimate-project.md)

[About WIP accrued loss accounts](about-wip-accrued-loss-accounts.md)

[About WIP cost value accounts](about-wip-cost-value-accounts.md)

[About WIP cost value item accounts](about-wip-cost-value-item-accounts.md)

[About WIP invoice on-account accounts](about-wip-invoice-on-account-accounts.md)

[About WIP profit accounts](about-wip-profit-accounts.md)

[About WIP production accounts](about-wip-production-accounts.md)

[About WIP sales value accounts](about-wip-sales-value-accounts.md)

[About WIP subscription accounts](about-wip-subscription-accounts.md)

  


