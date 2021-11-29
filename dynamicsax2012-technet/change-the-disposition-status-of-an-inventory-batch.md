---
title: Change the disposition status of an inventory batch
TOCTitle: Change the disposition status of an inventory batch
ms:assetid: 95606b16-8c43-4c9c-b9bc-5566c86c0629
ms:mtpsurl: https://technet.microsoft.com/library/Hh209396(v=AX.60)
ms:contentKeyID: 36058620
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Change the disposition status of an inventory batch 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to change the disposition status for an inventory batch. The status of the batch disposition is defined by the batch disposition code that is associated to the inventory batch. The status of the batch disposition can be either **Available** or **Unavailable**.

If a batch disposition code is set to **Available** and it is associated to an inventory batch, this batch is available for reservation. It is also available for picking, and shipping in sales orders, transfer orders, and production orders. The inventory batch is also available for master planning.

If a batch disposition code is set to **Unavailable**, the inventory is blocked for reservation. It is also blocked for picking, and shipping in sales order, transfer orders, and production orders. In this case, the inventory batch is not available for master planning either.

1.  Click **Inventory management** \> **Inquiries** \> **Dimensions** \> **Batches**.

2.  Select the batch with the disposition status that you want to change.

3.  Select the **Reset batch disposition** button.

4.  In the **New batch disposition code** field, select the batch disposition code with the desired batch disposition status.

5.  Click **OK** to save your changes.

## See also

[(PM) Batches (form)](https://technet.microsoft.com/library/hh209252\(v=ax.60\))

  


