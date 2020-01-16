---
title: Reverse a completed inventory close
TOCTitle: Reverse a completed inventory close
ms:assetid: 9282e2a5-a0e3-46b4-8bee-01053dcc28f3
ms:mtpsurl: https://technet.microsoft.com/library/Gg232180(v=AX.60)
ms:contentKeyID: 36058575
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Reverse a completed inventory close 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You may occasionally have to reverse a completed inventory close, returning settlements to the state they had before adjustments were made.


> [!NOTE]
> <P>Only the last inventory period that was closed can be reversed. To reverse an earlier inventory close, all those that followed it must be reversed individually, starting with the most recent.</P>



When you reverse a completed inventory close, inventory is reopened to enable posting in the period that the inventory close covers. Related changes may also be made in the general ledger. For more information, see [About inventory close and the general ledger](about-inventory-close-and-the-general-ledger.md).

After you finish making adjustments, you can run inventory close again for the period that you are working with.

1.  Click **Inventory management** \> **Periodic** \> **Closing and adjustment**.

2.  Select the record of the inventory closing that you want to reverse, and then click **Cancellation**.

3.  In the **Cancelation - initialize** form, specify options for canceling one voucher or all recalculations, and then click **OK**.

## See also

[About inventory close](about-inventory-close.md)

[About inventory close and the general ledger](about-inventory-close-and-the-general-ledger.md)

[Cancellation - Initialize (form)](https://technet.microsoft.com/library/hh227515\(v=ax.60\))

  


