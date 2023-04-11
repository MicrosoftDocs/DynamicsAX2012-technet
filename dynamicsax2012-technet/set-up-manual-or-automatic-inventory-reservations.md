---
title: Set up manual or automatic inventory reservations
TOCTitle: Set up manual or automatic inventory reservations
ms:assetid: eeb096bf-9891-4df4-9cec-646fa3cb974c
ms:mtpsurl: https://technet.microsoft.com/library/Aa551553(v=AX.60)
ms:contentKeyID: 36059912
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up manual or automatic inventory reservations 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following steps describe how to set up manual or automatic inventory reservations. If you change the existing setup, existing inventory reservations, order lines, or orders are not affected. Changes affect only future orders and order lines.


> [!NOTE]
> <P>If you must create several orders or order lines, and the items use the same method of reservation, you can temporarily select the reservation method, based on the method of reservation that you need for those order lines. Afterward, you can select the method of reservation that is most frequently used.</P>



1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  Click **General**, and then click the **Sales** FastTab.

3.  In the **Reservation** field, select the method of inventory reservation:
    
      - **Manual** – Inventory for orders is reserved manually.
    
      - **Automatic** – Inventory is reserved when order lines are created, in the order in which the order lines are created. For bills of materials (BOMs), reservations are made for the BOM item number, not for the individual elements of the BOM.
    
      - **Explosion** – Inventory is reserved when order lines are created, in the order in which the order lines are created. For BOMs, reservations are made for the individual elements of the BOM, not for the BOM item number.

  


