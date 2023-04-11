---
title: Run inventory recalculation
TOCTitle: Run inventory recalculation
ms:assetid: 27c08fd7-f997-4ebb-93e8-04c93f84f1f2
ms:mtpsurl: https://technet.microsoft.com/library/Gg231004(v=AX.60)
ms:contentKeyID: 36056214
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Run inventory recalculation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Inventory recalculation results that are shown in adjustments that match inventory receipts to issues. Unlike inventory close, it does not settle issues or close transactions.

The same parameter settings are available for inventory recalculation as for inventory close, but inventory recalculation can be performed on a subset of inventory items. Inventory close must be performed on all inventory items.

You can still post transactions to a period for which inventory recalculation has already been processed. The inventory module will not be closed because of an inventory recalculation as it is with inventory close.

Since inventory recalculation can be run on a subset of items, and because inventory recalculation will not make an adjustment for less than the throughput amount, it is not as accurate as an inventory close and should not be relied on to replace inventory close.

To recalculate the inventory and match item issues with receipts in order to determine their cost price without closing the inventory, follow these steps.

1.  Click **Inventory management** \> **Periodic** \> **Closing and adjustment**. Click the **Recalculation** button to open the **Recalculate inventory** form.

2.  If you want to select specific items or item groups to be recalculated, click **Select**. Your selection displays in the **Items** field group.

3.  In the **Recalculate inventory up to** field, enter or select a date before which you want the inventory to be recalculated.

4.  Fill in the remaining fields as required.

5.  Click **OK** to start the recalculation.


> [!NOTE]
> <P>In order to speed up subsequent inventory close procedures, avoid running too many recalculations after the expected closing date.</P>



## See also

[Recalculate inventory (form)](https://technet.microsoft.com/library/aa600651\(v=ax.60\))

[Pause inventory recalculation](pause-inventory-recalculation.md)

[Resume inventory recalculation](resume-inventory-recalculation.md)

  


