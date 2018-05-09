---
title: About creating production orders
TOCTitle: About creating production orders
ms:assetid: 78e4c758-bbac-4421-889e-947d5f165a61
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550055(v=AX.60)
ms:contentKeyID: 36058231
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- production
- manufacturing
- production order
- manufacture
---

# About creating production orders 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you create a production order, you start to monitor and work with the item as it passes through the stages of the production life cycle. The system assigns an order status to each step in this cycle. The status tells you where the item is in the production process. When an order is created, it is assigned the status **Created**.

General and production-specific base data must be created before you can create a production order. When you select the item for production and specify the quantity that you want in the current order, the fields that remain are filled in automatically with information about the item that is already in the system. You can change these fields to suit a specific production order.

When you create a production order, you initiate a request to start the manufacture of an item. The production order contains information about what will be produced, the quantity to produce, and the planned finish date. After you select an item number and enter a quantity, the remaining information for the production order comes from the data that is defined in the bill of materials, operations resources, routes, and operations.

Production orders are generated during master planning or created manually for the following reasons:

  - Generated to meet sales order demands when inventory is insufficient

  - Generated to supply BOM items as subassemblies to other items in demand

  - Created manually by authorized personnel to cover exceptional demand

## See also

[Production orders (form)](https://technet.microsoft.com/en-us/library/aa617966\(v=ax.60\))

[Create production order (form)](https://technet.microsoft.com/en-us/library/aa497150\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

