---
title: About packing materials and packing material fees
TOCTitle: About packing materials and packing material fees
ms:assetid: 58c2025e-426a-4e49-aaf6-ff0cc37cabdd
ms:mtpsurl: https://technet.microsoft.com/library/Aa549072(v=AX.60)
ms:contentKeyID: 39519149
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About packing materials and packing material fees 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Packing material fees are paid to a recycling company at certain intervals. An amount is paid, per unit of weight, for each material that a packing unit consists of. Packing material fees are calculated and reported, but no ledger transactions are posted because the fees are not regarded as taxes to be paid to an authority.

## How to use packing material fees

Packing material weights and fees are calculated for sales order lines and for purchase order lines.

You can define one or more packing units for an item, for a packing group of items, or for all items. A packing unit consists of the packing materials, their weights, and the number of items that are included in the packing unit. A packing material code is assigned to each type of packing material that is defined.

Based on the packing material code, you can specify a price for a specified period. The packing material fee is calculated based on this information.

> [!NOTE]
> <P>Even if your company does not pay packing material fees, you can use the functionality to calculate statistics for the weights of packing materials.</P>



## Setup requirements for packing material fees

Before you calculate packing material weights or packing material fees, or both, you must create the following base data:

  - **Packing groups** – Create packing groups to assign to items.

  - **Packing material codes** – Create packing material codes for each type of packing material that is defined.

  - **Packing units** – Specify a packing unit for an item, for a packing group, or for all items. For each packing unit, define which packing materials to include, assign weights, and, in the **Packing unit factor** field, enter the conversion factor from the inventory unit.

  - **Packing material fees** – Specify packing material fees per packing material code. For each type of material, define the period of validity, the price per material, the currency, and the unit.

## Packing units on sales order lines

When you create a sales order line, the system checks to see whether packing units are specified for the item. If packing units are specified, the system updates the sales order line with the specified packing unit and the packing unit quantity. The packing unit quantity is based on the ordered quantity divided by the number of items in the selected packing unit. If a packing unit has not been specified, you can manually enter a packing unit and a packing unit quantity on the sales order line.

You can also change the packing unit and the packing unit quantity when you post the sales order line. This is relevant if the sales order line is only partly delivered or partly invoiced.

When you invoice the sales order, packing material transactions are created. Packing material transactions contain the weights of the packing materials for the sales line. You can also modify the transactions after you invoice them, and then create new transactions.

## Packing units on purchase order lines

Packing material transactions for a purchase order line are not created by the system. You create transactions for invoiced purchase order lines manually in the **Packing material transactions** form.

## See also

[About setting up and calculating packing material fees](about-setting-up-and-calculating-packing-material-fees.md)

[Create packing material codes](create-packing-material-codes.md)

  


