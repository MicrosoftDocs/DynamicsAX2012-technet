---
title: About physical and financial updates
TOCTitle: About physical and financial updates
ms:assetid: c8b100a0-6f4d-4a77-8eb6-44ab9e0dbfe2
ms:mtpsurl: https://technet.microsoft.com/library/Gg213650(v=AX.60)
ms:contentKeyID: 36059321
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About physical and financial updates 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides an overview of which types of transactions increase or decrease inventory quantities.

Inventory transactions can be physically updated and financially updated in Microsoft Dynamics AX, and certain types of physical and financial transactions increase inventory quantities, whereas others decrease the quantity.

## Physical increases

When a physical transaction is posted, the status of the transaction record is “Received.” The following transactions are considered physical increases:

  - Purchase order receipt

  - Sales order packing slip return

  - Production order report as finish

  - By-product on a production order picking list

## Financial increases

When a financial receipt transaction is posted, the status of the transaction record that increases the quantity is “Purchased.” The following transactions are considered financial increases:

  - Vendor invoice

  - Sales order invoice for a return

  - Production order costing

  - Positive quantity inventory journals, such as movement, profit loss, counting journals, bills of material, and transfer

## Transactions that increase quantity

Transactions that increase quantity are posted at the running average cost price. Microsoft Dynamics AX calculates a running average cost price that is based on the cost of each of these transactions for each inventory dimension that is being tracked financially. For information about how to run average cost price, see [About running average cost price](about-running-average-cost-price.md).

## Transactions that decrease quantity

Microsoft Dynamics AX uses the calculated running average cost price when a transaction that decreases quantity is posted, regardless of which inventory model is associates with that inventory. This requires that the transaction that decreases quantity was not previously marked to another transaction before posting.

If the physical on-hand inventory goes negative, Microsoft Dynamics AX uses the inventory cost that is defined for the item in the **Item** form. Click **Inventory management** \> **Periodic** \> **Forecast** \> **Entry** \> **Items**.


> [!NOTE]
> <P>If multisite functionality is enabled, this cost will instead be the inventory cost that is defined for a site in the <STRONG>Default order settings</STRONG> form.</P>



## Physical issues vs. financial issues

When a physical issue transaction is posted, the status of the transaction record is “Deducted.” The following transactions are considered physical issues:

  - Production order picking list journal

  - Sales order packing slip

  - Purchase order packing slip return

When a financial transaction is posted, the status of the transaction record is “Sold.” The following transactions are considered financial issues:

  - Production order ended

  - Sales order invoice

  - Vendor invoice return

  - Negative quantity inventory journals, such as movement, profit loss, counting journal, bills of material, and transfer

Transactions that decrease quantity are posted at the running average cost price. Thus, the inventory close procedure is required to settle issue transactions to receipt transactions based on the inventory model that is assigned to each item.

## See also

[About running average cost price](about-running-average-cost-price.md)

[Track running average cost per inventory dimension](track-running-average-cost-per-inventory-dimension.md)

  


