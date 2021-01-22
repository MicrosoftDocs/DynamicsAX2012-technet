---
title: About batch orders
TOCTitle: About batch orders
ms:assetid: 54f9f5e5-fe5e-47d4-bb72-e2c2ad6557fa
ms:mtpsurl: https://technet.microsoft.com/library/Hh352205(v=AX.60)
ms:contentKeyID: 36687839
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- about batch orders
- about creating batch orders
- about generating batch orders
- batch processes
- process manufacturing
- rework a batch order
- split a batch order
audience: Application User
ms.search.region: Global
---

# About batch orders 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In process manufacturing, batch orders are requests to begin the manufacture of new items that use formulas. When you create a batch order, you start to monitor and work with the item as it passes through the stages of the production life cycle. The system assigns an order status to each step in this cycle. The status tells you where the item is in the production process. When an order is created, it is assigned the status **Created**.

Before you can create a batch order, you must create the general and production-specific base data for the items that are used as ingredients in the order. When you select the item and specify the quantity for an order, the remaining information about the item comes from data that is already defined in the system. You can modify this information for a specific batch order.

When you create a batch order, you initiate a request to start the manufacture of an item. The batch order contains information about what will be produced, the quantity to produce, and the planned finish date. After you select an item number and enter a quantity, the remaining information for the order comes from the data that is defined in the formula, operations resources, routes, and operations.

Batch orders are generated during master planning or created manually for the following reasons:

  - They are generated to meet sales order demand when inventory is insufficient.

  - They are generated for planning to meet future demand.

  - They are created manually by authorized personnel to cover exceptional demand.

## Related batch processes

You can use the following processes to split a batch order into two or more batch orders and to create rework batch orders.

  - **Split** ─ Split a batch order into two batch orders. You can only split the quantity that has not yet started production. The batch order status must be either: **Created**, **Estimated**, **Scheduled**, or **Released**.

  - **Rework** ─ You may want to rework a finished formula item that has already been produced. For example, you may want to correct a product flaw or enhance the quality of a product. You can rework a finished formula item only if its source batch order is at or beyond the status of **Reported as finished**. For a rework batch order, the costing is calculated by using the cost of the reworked formula item, any additional materials, and rework operations.

## See also

[Batch order (form)](https://technet.microsoft.com/library/hh352323\(v=ax.60\))

[Create batch (form)](https://technet.microsoft.com/library/hh328644\(v=ax.60\))

  


