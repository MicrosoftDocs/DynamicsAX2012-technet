---
title: About costing versions containing item purchase prices related to BOM calculations
TOCTitle: About costing versions containing item purchase prices related to BOM calculations
ms:assetid: ecb5f988-6e20-481c-b2b2-e69eb55cb875
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243256(v=AX.60)
ms:contentKeyID: 36059896
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About costing versions containing item purchase prices related to BOM calculations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A costing version can include content about the purchase price records for an item. You enable purchase price content primarily to define purchase price records for component items, so that these records can be used to calculate the costs of manufactured items. To enable purchase price content, you must define a BOM calculation group that contains a cost price model for the item's purchase price, and then assign the BOM calculation group to purchased items. You must then use a cost price model for the BOM calculation group when you perform BOM calculations with planned costs to calculate the sales price of manufactured items.

An item's purchase price records are also used for reference information. By changing the status of an item's purchase price record from pending to active, you can update the item's base purchase price. The base purchase price is not site-specific, and it can be manually overridden. It acts as a default purchase price on purchase orders.

## See also

[About BOM calculation of a suggested sales price](about-bom-calculation-of-a-suggested-sales-price.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

