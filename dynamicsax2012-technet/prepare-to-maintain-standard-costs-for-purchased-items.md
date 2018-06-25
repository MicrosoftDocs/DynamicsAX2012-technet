---
title: Prepare to maintain standard costs for purchased items
TOCTitle: Prepare to maintain standard costs for purchased items
ms:assetid: 2070913a-605d-4e69-a53d-614780fccb61
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg230981(v=AX.60)
ms:contentKeyID: 36056160
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Prepare to maintain standard costs for purchased items [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To maintain purchased items' costs, follow these steps:

1.  Assign an item model group to each purchased item.
    
    The item model group determines whether the item’s costs reflect a standard cost or an actual cost inventory model.

2.  Assign an item group to each purchased item.
    
    The item group contains ledger accounts that apply to the purchased item. The ledger accounts for an item with a standard cost inventory model include the purchase price variance, the inventory cost revaluation, and the cost change variance.

3.  Assign a cost group to each purchased item.
    
    The cost group can act as the basis for assigning ledger accounts, such as assigning ledger accounts for purchase price variances.

4.  Assign the inventory unit of measure to each item.
    
    The item’s costs are always expressed in the item’s inventory unit of measure.

The purchased items’ costs can be maintained after you complete the preparation steps. Additional preparation steps are necessary when a purchased item will be a component in a manufacturing environment.

## See also

[Set up initial standard costs in a nonmanufacturing environment](set-up-initial-standard-costs-in-a-nonmanufacturing-environment.md)

[Update standard costs in a nonmanufacturing environment](update-standard-costs-in-a-nonmanufacturing-environment.md)

[Prepare to maintain standard costs for purchased items](prepare-to-maintain-standard-costs-for-purchased-items.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

