---
title: Prepare pricing templates
TOCTitle: Prepare pricing templates
ms:assetid: 05ddf6ed-d9ca-44f8-92ea-46aae1cee6f4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh556856(v=AX.60)
ms:contentKeyID: 39509586
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Prepare pricing templates 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Commodity pricing is the practice of basing the sales price for commodity-based end items on the market replacement cost of the main ingredient. Commodity items, such as iron ore, coffee beans, and sugar, are items for which there is a demand across commodity trading markets. The price for these items fluctuates periodically, such as daily or weekly, based on global supply and demand. When the price of the commodity item changes, any end item that uses that commodity is adjusted and the price is updated in the related sales price trade agreement.

Use the **Commodity pricing template line grouping** form to define how existing account line codes are mapped to all customers, customers that belong to a specified pricing group, or a specific customer.

## Pricing groups replace customer groups

In Microsoft Dynamics AX 2009, line account codes that are associated with commodity pricing templates could apply to all customers, a group of customers, or a specific customer. In Microsoft Dynamics AX 2012, line account codes that are associated with commodity pricing templates can apply to all customers, customers that belong to any pricing group, or a specific customer.

## Map commodity pricing template lines

When you start preprocessing commodity pricing template lines, the **Commodity pricing template line grouping** form lists all existing pricing templates. Any template line groups that were previously associated with customer groups must now be associated with pricing groups. Any template line account codes that were previously associated with customer groups can now be associated with pricing groups.

1.  On the preprocessing checklist, click **Commodity pricing template line grouping** to open the form.

2.  If the **Account code** has a value of **Group**, change the **Pricing group** value to a valid pricing group.

## See also

[About commodity pricing](about-commodity-pricing.md)

  


