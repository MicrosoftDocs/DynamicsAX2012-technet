---
title: About commodity pricing
TOCTitle: About commodity pricing
ms:assetid: df52bf9a-ff1d-46e3-9897-13fcfb0fd526
ms:mtpsurl: https://technet.microsoft.com/library/Hh227418(v=AX.60)
ms:contentKeyID: 36059697
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- item
- prices
- price
- commodity pricing
- process industries
- goods
audience: Application User
ms.search.region: Global
---

# About commodity pricing 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Commodity pricing is the ability to set the sales price for commodity-based end items using the market replacement cost of the main ingredient. Commodity items, such as iron ore, coffee beans, and sugar, are items for which there is a demand across commodity trading markets. The price for these items fluctuates periodically, such as daily or weekly, based on global supply and demand. When the price of the commodity item changes, any end item that uses that commodity is adjusted and the new price is updated in the related sales price trade agreement.

## Example

This example illustrates how commodity pricing works:

To produce animal feed, 90% or more of its cost comes from one main ingredient, cornmeal. The price of the corn needed to produce the cornmeal is determined by commodity trading markets, usually weekly. So any fluctuation in the cost of the corn not only affects the price of the cornmeal, but in turn also affects the price of the end item, which is animal feed.

## Updating trade agreements

Commodity pricing functionality lets you pass new costs, price break quantities, and effective dates to all related sales trade agreements. You can update commodity pricing information in the **Create price and margin data** form, and review the changes in the **Price margin update** form. You can then use the **Trade agreement** button to pass the updated prices to the trade agreements. To actually apply the new prices to trade agreements, you must post the **Price/discount agreement journals** in **Sales and marketing**.

## See also

[Create price and margin data (form)](https://technet.microsoft.com/library/hh242859\(v=ax.60\))

[Price margin update (form)](https://technet.microsoft.com/library/hh227659\(v=ax.60\))

  


