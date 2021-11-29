---
title: Track running average cost per inventory dimension
TOCTitle: Track running average cost per inventory dimension
ms:assetid: 7f118cf4-a510-4df5-8b3a-a1147b2ed6b5
ms:mtpsurl: https://technet.microsoft.com/library/Gg213146(v=AX.60)
ms:contentKeyID: 36058327
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Track running average cost per inventory dimension 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Each inventory item is assigned an inventory dimension group. The running average cost price for an item is therefore calculated based on the selection of inventory dimensions that are being tracked financially.

There are three different types of inventory dimensions: product, storage, and tracking. Product dimensions include configuration, size, and color. Product dimensions are always tracked financially. Storage and tracking dimensions include site, warehouse, batch number, location, pallet ID, and serial number. You decide which storage and tracking dimensions will be tracked financially.

## Example

If the inventory dimension group attached to the item is financially tracked by warehouse, the running average cost price is calculated per warehouse.

The following purchase orders have been invoiced:

  - Purchase order for a quantity of 2 at a cost price of USD 10.00 has been invoiced for warehouse GW

  - Purchase order for a quantity of 3 at a cost price of USD 12.00 has been invoiced for warehouse GW

  - Purchase order for a quantity of 5 at a cost price of USD 15.00 has been invoiced for warehouse MW

The running average cost price for warehouse GW is USD 11.20

The running average cost price for warehouse MW is USD 15.00.

A sales order invoice is posted for warehouse GW. The value of the inventory and cost of goods sold (before inventory close is run and without marking) will be USD 11.20. Another sales order is posted for warehouse MW. The value of the inventory and cost of goods sold (before inventory close is run without marking) will be USD 15.00.

## Example

If the inventory dimension group attached to the item is financially tracked by warehouse and batch number, the running average cost price will be calculated for each batch.


> [!NOTE]
> <P>We recommend always viewing the cost price with all financial dimensions being tracked.</P>



The following purchase orders have been invoiced:

  - Purchase order for a quantity of 2 at a cost price of USD 10.00; invoiced for warehouse GW and batch AAA

  - Purchase order for a quantity of 3 at a cost price of USD 12.00; invoiced for warehouse GW and batch AAA

  - Purchase order for a quantity of 2 at a cost price of USD 15.00; invoiced for warehouse GW and batch BBB

The running average cost price for warehouse GW and batch AAA is USD 11.20.

The running average cost price for warehouse GW and batch BBB is USD 15.00.

## See also

[About running average cost price](about-running-average-cost-price.md)

  


