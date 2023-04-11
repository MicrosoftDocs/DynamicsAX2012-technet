---
title: About catch weight items
TOCTitle: About catch weight items
ms:assetid: d0714a35-3569-4001-89e8-a601246db894
ms:mtpsurl: https://technet.microsoft.com/library/Hh242918(v=AX.60)
ms:contentKeyID: 36059488
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- item
- product
- items
- catch weight
- process industries
- CW
- catch weight item
audience: Application User
ms.search.region: Global
---

# About catch weight items 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You often use catch weight products in industries where products can vary slightly by weight or size, or both, such as the food industry. Catch weight products use two units of measure – an inventory unit and a catch weight unit. The inventory unit is the unit of measure in which the product is weighed and invoiced. The catch weight unit is the unit in which the inventory transactions are performed, such as sold, received, transferred, picked, and shipped. The nominal quantity represents the conversion between the catch weight unit and the inventory unit. Minimum and maximum quantities represent the allowed interval in which the inventory quantity can vary.

## Example

Consider fresh shrimps packed in boxes, which is also the unit in which customers order the shrimps. Because each box varies in weight, the shrimps are invoiced in kilograms. When several boxes are picked to a sales order, the boxes are weighed to determine how much to invoice the customer. In this example, we use kilograms as the inventory unit and boxes as the catch weight unit.

## Full or partial visibility

The dimension configuration and weight that you set up for a catch weight product determines whether the item uses full or partial visibility.

  - Catch weight items that use full visibility require that the inventory quantity is known for each catch weight unit. For example, assume shrimps are sold in boxes and the customer requires that each box must have a unique identification and a known weight. In this example, the item number for the boxes of shrimps should be created as a catch weight item that uses full visibility. You create catch weight items that use full visibility if you assign a unique serial number to each catch weight unit.

  - Catch weight items that use partial visibility require that the inventory quantity is known for batches of items that use a catch weight unit. For example, assume that a company receives a batch of 100 boxes of shrimps with a nominal weight of 10 kilograms. Because all of the boxes belong to the same batch, they all use the same batch number. As each box can vary in weight, the whole batch of boxes is weighed. The number of boxes and their total weight can be registered in a single transaction.

## Set up catch weight items

To set up a catch weight item, be familiar with these setup guidelines:

  - When the item is created in the **New released product** form, the catch weight, the **CW product** check box, must be selected to designate the item as catch weight. You select this check box on the **Product** tab of the form.

  - You must set up a conversion between the inventory unit and catch weight unit. Set the conversion up as an inter-class conversion.

  - You set up the catch weight unit on the item master and define the minimum and maximum quantities in inventory units that are allowed for the item.

  - You cannot set up an item as catch weight if the item has existing inventory transactions or is associated with a batch or serial number group that has a per quantity defined.

  - You cannot set up a catch weight item for a product type of **Service** or production types of **BOM** or **Planning item**.

  - To designate a catch weight item as full visibility, you must specify a tracking dimension group for the item where the **Serial number dimension** is set to active with **Serial number control**.

## Reserve catch weight inventory

When you reserve inventory for a catch weight item that uses full visibility and the physically reserved or on-hand quantity is a value of 1, all of the inventory is reserved to the order. For example, assume for a sales order that the **CW physical reserved** quantity is 1 with a **Physical reserved** quantity of 20. If the actual **Physical inventory** value for this item dimension is 21, all of the inventory quantity (21) is reserved to the order.

## See also

[Create a catch weight item with full visibility](create-a-catch-weight-item-with-full-visibility.md)

[Create a catch weight item with partial visibility](create-a-catch-weight-item-with-partial-visibility.md)

[Unit conversions (form)](https://technet.microsoft.com/library/hh209285\(v=ax.60\))

  


