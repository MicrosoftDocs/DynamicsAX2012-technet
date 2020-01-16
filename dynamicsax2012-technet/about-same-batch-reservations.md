---
title: About same batch reservations
TOCTitle: About same batch reservations
ms:assetid: ea7616bc-06b4-40c1-844c-df5de4417865
ms:mtpsurl: https://technet.microsoft.com/library/Hh227481(v=AX.60)
ms:contentKeyID: 36059854
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About same batch reservations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Same batch reservation lets you reserve inventory for a sales order line against a single batch of inventory. For example, a customer who orders wallpaper may request that the whole order be filled from the same batch or lot to avoid any inconsistencies among the rolls of paper.

## Set up a product to use same batch reservation

To set up a product to use same batch reservation, these settings must be active in the **Item model groups**, **Tracking dimension group**, and **Storage dimension group** that you assign to the product.

  - **Item model groups** — The item model group must have the **Same batch selection** and **Consolidate requirement** fields selected in the **Reservation** field group on the **Setup FastTab**. You access this form in **Inventory and warehouse management**.

  - **Tracking dimensions groups** — The tracking dimension group must have the **Coverage plan by dimension** field selected for the **Batch number**. You access this form in **Product information management**.

  - **Storage dimensions groups** — The storage dimension group must have the **Coverage plan by dimension** field selected for **Site** and **Warehouse**. You access this form in **Product information management**.

## Reserve same batch inventory for a product

When you reserve inventory for a product in a sales order line that is set up for same batch selection, **Process manufacturing** attempts to reserve the quantity ordered from a single inventory batch. It also takes into consideration any specific batch attribute requirements.

If the quantity cannot be filled from a single batch, the **Same batch reservation conflict** form is displayed. This form contains details and functions that let you make informed decisions about how to continue with the reservation.

To determine the available quantity of physical inventory, **Process manufacturing** considers any inventory conditions that might prevent the batch from being reserved, which can include the following:

  - The batch disposition code has **Block reservation** for Sales flagged as **Blocked**.

  - The batch has expired based on the expiration date and any applicable customer sellable days. The item may still be considered for reservation if the **Item model group** for the item is **FEFO date controlled** and the **Best before date** is selected as the **Pick criteria**.

  - The batch has insufficient shelf life days remaining based on the expiration and best before date plus any customer sellable days.

## See also

[Item model groups (form)](https://technet.microsoft.com/library/aa577092\(v=ax.60\))

[Same batch reservation conflict (form)](https://technet.microsoft.com/library/hh328606\(v=ax.60\))

[Storage dimension groups (form)](https://technet.microsoft.com/library/hh209317\(v=ax.60\))

[Tracking dimension groups (form)](https://technet.microsoft.com/library/hh209465\(v=ax.60\))

  


