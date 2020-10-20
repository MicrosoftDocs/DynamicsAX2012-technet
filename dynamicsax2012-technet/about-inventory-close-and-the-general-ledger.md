---
title: About inventory close and the general ledger
TOCTitle: About inventory close and the general ledger
ms:assetid: 0a72628b-5a53-4a10-b96a-629c4e8b6a4c
ms:mtpsurl: https://technet.microsoft.com/library/Gg230701(v=AX.60)
ms:contentKeyID: 36055985
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About inventory close and the general ledger 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Several of the tasks that you can complete in the **Closing and adjustment** form result in an update to the general ledger. These tasks include making inventory on-hand adjustments, making inventory transaction adjustments, running inventory recalculation, and running inventory close.

The ledger accounts that are updated as a result of completing these tasks are linked to the original inventory transaction.


> [!NOTE]
> <P>The general ledger might also be updated by reversing an inventory close. For more information, see <A href="reverse-a-completed-inventory-close.md">Reverse a completed inventory close</A></P>



For example, if a sales order is settled to a purchase order, the general ledger accounts that were used for the original sales order will be adjusted. This is true even if the ledger accounts for the item group assigned to this item have changed since the sales order was posted. After inventory close creates a settlement amount, the settlement amount is still posted to the original ledger accounts, instead of the new ledger accounts assigned to the item.

## Review ledger vouchers after an inventory close update

After the update is complete, you can review the resulting ledger voucher that is posted because of one of these tasks.

1.  Click **Inventory management** \> **Periodic** \> **Closing and adjustment**.

2.  On the **Overview** tab, select the update to review.

3.  Click **Ledger** \> **Voucher** to review the transaction.

## See also

[About inventory close](about-inventory-close.md)

[Reverse a completed inventory close](reverse-a-completed-inventory-close.md)

[Voucher transactions (form)](https://technet.microsoft.com/library/aa583215\(v=ax.60\))

  


