---
title: About inventory recalculation and the general ledger
TOCTitle: About inventory recalculation and the general ledger
ms:assetid: f0e972dc-bd9d-43ae-b646-442d5c57d2bc
ms:mtpsurl: https://technet.microsoft.com/library/Gg243272(v=AX.60)
ms:contentKeyID: 37008251
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About inventory recalculation and the general ledger 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Several of the tasks that you can perform from the **Closing and adjustment** form cause an update to the general ledger. These tasks include adjusting on-hand inventory, adjusting inventory transactions, running inventory recalculations, and running inventory closes.

These tasks affect any ledger account that is linked to the original inventory transaction.

For example, when you create a purchase order from a sales order, the general ledger accounts that are used for the original sales order are updated. Even if the ledger accounts for the item group that is assigned to the item were changed after the sales order was posted, and an inventory recalculation created an adjustment amount, the adjustment amount is posted to the original ledger accounts. It is not posted to the new ledger accounts that are assigned to the item.

After the update is completed, you can review the ledger voucher that is posted because of one of these tasks.

1.  On the **Overview** tab of the **Closing and adjustment** form, select the update that you want to review.

2.  Click **Ledger**, and then select **Voucher**.

## See also

[Voucher transactions (form)](https://technet.microsoft.com/library/aa583215\(v=ax.60\))

  


