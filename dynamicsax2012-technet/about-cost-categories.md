---
title: About cost categories
TOCTitle: About cost categories
ms:assetid: bd1c5278-084e-4874-9ff4-5aa2f740328f
ms:mtpsurl: https://technet.microsoft.com/library/Aa498874(v=AX.60)
ms:contentKeyID: 36059146
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- cost
- cost categories
- category
- costs
- costing
- cost category
audience: Application User
ms.search.region: Global
---

# About cost categories 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The function of a cost category in **Cost accounting** is equivalent to the function of a chart of accounts in **General ledger**. Cost amounts are posted to cost categories through general ledger postings or cost accounting postings.

Each cost category must have one of the following three cost types assigned to it:

  - Primary costs: Primary costs are always posted directly. They can be set up to be identical to the following general ledger accounts: profit and loss, revenue, or costs. When the cost categories are the same as general ledger accounts, they are created automatically as primary costs.

  - Secondary costs: Secondary costs cannot be posted directly. They are used to post allocations. When you set up allocations, cost categories that are secondary costs are mandatory.

  - Service categories: Service categories are used to post quantities. They are usually linked with the production cost categories or the project categories. For more information, see [About service categories](about-service-categories.md).

When a cost category is created manually in **Cost accounting**, the local account option is enabled automatically, and the cost category can be used in cost accounting only. The cost category numbers cannot be used later as account numbers for general ledger accounts.

## Referencing a general ledger account

There are two ways to reference a general ledger account:

  - If the cost categories and the general ledger accounts (profit and loss, cost, and revenue) are identical, enable the transaction control after you create a new ledger account.

  - If the cost categories and the general ledger accounts are not identical, create the cost categories manually, and then link them to the general ledger account by using the **Cost category reference** form.

## Transaction control

If no dimension is selected, no cost transactions are created by the general ledger, and no posting entries are possible for this cost category. When one or more dimensions are enabled, cost transactions are created.


> [!NOTE]
> <P>When more than one dimension is selected for a cost category, <STRONG>Cost accounting</STRONG> creates one cost transaction for each dimension.</P>



When a dimension in one or more cost categories is enabled, general ledger transactions can be reposted to the **Process ledger transactions** form to create cost transactions. (Click **Cost accounting** \> **Periodic** \> **Transactions** \> **Process production transactions**.)

After the transactions have been created, the dimension cannot be cleared for this cost category.

## See also

[Setting up and maintaining cost categories](setting-up-and-maintaining-cost-categories.md)

[Create cost categories (CA)](create-cost-categories-ca.md)

[Chart of accounts (form)](https://technet.microsoft.com/library/aa618234\(v=ax.60\))

  


