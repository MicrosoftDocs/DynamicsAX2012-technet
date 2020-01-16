---
title: About creating and using price groups
TOCTitle: About creating and using price groups
ms:assetid: bc697b30-85bc-491a-ac95-7dd6608b5c77
ms:mtpsurl: https://technet.microsoft.com/library/Gg213600(v=AX.60)
ms:contentKeyID: 37835231
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- price group
- sales price
- trade agreement
audience: Application User
ms.search.region: Global
---

# About creating and using price groups 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX, price groups can be used to specify a set of prices that you want apply to a group of customers, vendors, or items. In **Project management and accounting**, price groups can be used to determine sales prices for project transactions. However, how price groups are referenced depends on the type of project transaction:

  - For transactions for hours, expenses, fees, and subscriptions, prices are derived from price groups that are referenced in the corresponding sales prices in the **Project management and accounting** module.

  - For item transactions, prices are derived from price groups that are referenced in trade agreements in the **Sales and marketing** module.

Sales prices can be derived from price groups that are assigned at the project contract level, the project level, and the customer level. If price groups are assigned to more than one of these levels, the system must determine which price group to apply. First, the system checks to see whether a price group has been defined for the project. If a price group has been defined for the project, the system applies that price group. If no price group has been defined for the project, the system checks the project contract. If no price group has been defined for the contract, the system checks the customer.

## About price groups for hour, expense, fee, and subscription transactions

Price groups can be referenced in the **Sales price (hour)**, **Sales price (expense)**, **Sales price (fee)**, and **Sales price - subscription** forms in **Project management and accounting**. The sales prices that are specified for a price group are applied when you create forecasts or transactions for hours, expenses, fees, and subscriptions.

## About price groups for item transactions

In **Project management and accounting**, sales prices for item transactions are derived from price groups that are assigned to trade agreements. Trade agreements are used to record negotiated prices for selling items to customers. They are set up in the **Sales and marketing** module.

## See also

[Create price groups](create-price-groups.md)

[Assign a price group to a project, project contract, or customer](assign-a-price-group-to-a-project-project-contract-or-customer.md)

[View item requirements](view-item-requirements.md)

[Item requirements (form)](https://technet.microsoft.com/library/aa552021\(v=ax.60\))

[Inventory journal (form)](https://technet.microsoft.com/library/aa558607\(v=ax.60\))

  


