---
title: About amortizing constant costs for a manufactured item
TOCTitle: About amortizing constant costs for a manufactured item
ms:assetid: c9921d7a-7d46-45b8-94fc-ae09a4bbaabb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213653(v=AX.60)
ms:contentKeyID: 36059326
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About amortizing constant costs for a manufactured item 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A manufactured item’s constant costs reflect the operation setup times and the components that have a constant quantity or a constant scrap amount. The concept of a costing lot size is used to amortize these constant costs in the calculated cost of a manufactured item. This concept has several synonyms, one of which is accounting lot size. The concept of amortizing constant costs also has several synonyms, one of which is proportional constant costs.

The quantity of a costing lot size for a manufactured item is used in a bill of material (BOM) calculation. The quantity depends on how you initiate and perform the BOM calculation, as illustrated by the following:

  - Default calculation quantity in an item’s BOM calculation − The item’s standard order quantity (for inventory) acts as the costing lot size, but the default value might be a greater quantity to reflect the item’s order quantity multiple. The item’s standard order quantity and multiple can be defined within its default order settings or site-specific order settings.

  - Specified calculation quantity in an item’s BOM calculation − The specified calculation quantity acts as the costing lot size for the item. The calculation quantity initially uses the item’s standard order quantity, but the default value can be manually overridden. The specified calculation quantity represents the costing lot size for the specified item, and for manufactured components that have a BOM line type of production. This is because it is assumed that the component will be produced to the exact quantity. The costing lot size for other manufactured components that have a BOM line type of item will reflect their standard order quantity.

  - Specified make-to-order calculation quantity in an item’s BOM calculation − The specified calculation quantity acts as the costing lot size for the item and its manufactured components when BOM calculations use a make-to-order explosion mode. It is assumed that the manufactured components will be produced to the exact quantity, just like a manufactured component that has a BOM line type of production.

  - Specified calculation quantity in an order-specific BOM calculation − An order-specific BOM calculation can be performed for a line item on a sales order, sales quotation, or service order. The specified calculation quantity uses the quantity on the originating line item, but the default quantity can be overridden. You can select whether the order-specific BOM calculation uses a make-to-order or multilevel explosion mode.

The calculated amount of a manufactured item’s amortized constant costs is termed charges.

## See also

[About displaying charges for a manufactured item](about-displaying-charges-for-a-manufactured-item.md)

  


