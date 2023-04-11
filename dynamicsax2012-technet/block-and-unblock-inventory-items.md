---
title: Block and unblock inventory items
TOCTitle: Block and unblock inventory items
ms:assetid: ca766554-5b65-4da5-8332-20279edf8125
ms:mtpsurl: https://technet.microsoft.com/library/Hh242851(v=AX.60)
ms:contentKeyID: 36059333
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- automatically blocked
- block item
- unblock items
- manual blocking
audience: Application User
ms.search.region: Global
---

# Block and unblock inventory items 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Inventory items can be blocked manually. They can be blocked automatically when they are a part of a quality inspection process. This topic deals only with the manual blocking and unblocking of inventory items.

For information about how to block items through an inspection process, see [About inventory blocking](about-inventory-blocking.md).

### Block inventory items manually

1.  Click **Inventory management** \> **Periodic** \> **Inventory blocking**.

2.  Press CTRL+N to create a new blocking transaction, and in the **Item number** field, select the item that you want to block.

3.  In the **Quantity** field, enter the quantity that you want to block.
    

    > [!NOTE]
    > <P>If the item that you want to block has a specific serial number as indicated on the <STRONG>Inventory dimensions</STRONG> FastTab, you can only block a quantity of one.</P>



4.  If you want to include the blocked quantity in planning activities as an expected on-hand quantity, select the **Expected receipts** check box.

### Unblock inventory items manually

1.  Click **Inventory management** \> **Periodic** \> **Inventory blocking**.

2.  Select the blocking transaction for the inventory items that you want to unblock, and click the **Delete** button or press ALT+F9 to delete the transaction.
    

    > [!TIP]
    > <P>If you change a dimension on the <STRONG>Inventory dimensions</STRONG> FastTab, you delete the existing blocking transaction and replace it with a blocking transaction that includes the item quantity with the new dimension.</P>
    > <P>If you want to unblock only part of a blocked quantity, you can change the quantity in the <STRONG>Quantity</STRONG> field in the <STRONG>Inventory blocking</STRONG> form.</P>


  


