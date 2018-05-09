---
title: About inventory close
TOCTitle: About inventory close
ms:assetid: 92c74079-fb6a-4924-8567-dae66015d6af
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg232187(v=AX.60)
ms:contentKeyID: 36058578
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- closing
- cost price
- financial
- physical
- moving average
- fifo
- inventory close
- running average
- lifo
---

# About inventory close 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Microsoft Dynamics AX inventory close process settles issue transactions to receipt transactions based on the inventory valuation method that is selected in the item’s item model group. You can also choose to have the general ledger updated to reflect the adjustments that have been made.

However, until inventory close or recalculation is run, Microsoft Dynamics AX posts issue transactions at the calculated running average cost price.

After inventory close, it is no longer possible to post in periods before the inventory close date that you set unless you reverse a completed inventory close process. For example, if inventory close is run for the period ending January 31, Microsoft Dynamics AX will prevent any transactions from being posted with a date before January 31.


> [!NOTE]
> <P>As from the Microsoft Dynamics AX release, inventory close is not required with the Standard cost valuation method.</P>



How often inventory close is run varies by company, but transaction volume should help determine how often you decide to run inventory close. In general, most companies run inventory close as part of their month-end closing and reconciliation procedures.


> [!NOTE]
> <P>We recommend that you run inventory close during off-peak hours to more evenly distribute computing resources.</P>



Items in inventory are assigned to one of two inventory types: item, or service. Inventory close will perform the same functions for all types, but for service items, inventory close will still settle issues to receipts.


> [!NOTE]
> <P>To avoid sync problems between the general ledger and inventory, the <STRONG>Update productions</STRONG> and <STRONG>Update ledger</STRONG> parameters are both hidden and set to True.</P>



## About inventory recalculation

If adjustments to inventory and the general ledger are necessary during a month or other inventory period, you can run inventory recalculation instead of inventory close. Inventory recalculation makes adjustments but does not make settlements to inventory transactions.

## See also

[About running average cost price](about-running-average-cost-price.md)

[Run inventory close](run-inventory-close.md)

[Run inventory recalculation](run-inventory-recalculation.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

