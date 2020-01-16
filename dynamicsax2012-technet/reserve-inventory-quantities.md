---
title: Reserve inventory quantities
TOCTitle: Reserve inventory quantities
ms:assetid: 715c0737-fcab-43dc-b5fd-549105d708a8
ms:mtpsurl: https://technet.microsoft.com/library/Aa549962(v=AX.60)
ms:contentKeyID: 36058067
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Reserve inventory quantities 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can reserve inventory quantities automatically for a specific sales order. This means that reserved inventory cannot be withdrawn from the warehouse for other orders unless the inventory reservation, or part of the inventory reservation, is canceled.

There are several reasons for reserving inventory:

  - First ordered, first delivered, which means that customers get available items in the same order in which they place their orders.

  - Shortage of items due to a long or unknown delivery time from the vendor. You might want to make sure that certain customers or orders get delivery of the first-available items.

  - Certain customers and certain types of orders have first priority for delivery.

  - Items with serial or batch numbers. You can mark certain items that have been or will be delivered to specific orders.

  - Specially ordered items that are reserved for certain orders.

  - Production orders. For example, you can mark items that are produced for and adjusted to specific orders.

Inventory can be reserved automatically when a new order line is created, or inventory can be reserved manually on the individual orders. This is a parameter in the **Accounts receivable parameters** form. The setup applies when a new order is created, but the setup on individual orders, or even on specific order lines, can also be changed in the **Sales order** form.

Only items and bills of materials (BOMs) can be reserved for sales orders. Services cannot be reserved, because there is no on-hand inventory.

Both physical on-hand inventory and ordered, but not yet received, inventory can be reserved.

If a larger quantity is reserved than what the on-hand inventory contains, a warning appears that says that you cannot reserve such a large quantity. You can then either reserve the quantity, anyway, or change the ordered quantity. The quantity can be either reserved or changed. If more items are reserved than are available, the shortage is covered the next time that items are available for delivery.

## See also

[Accounts receivable parameters (form)](https://technet.microsoft.com/library/aa576993\(v=ax.60\))

  


