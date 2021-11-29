---
title: Prepare to maintain standard costs for manufactured items
TOCTitle: Prepare to maintain standard costs for manufactured items
ms:assetid: 157e0b55-5075-4f1c-85a1-e99e4473b1e8
ms:mtpsurl: https://technet.microsoft.com/library/Gg230951(v=AX.60)
ms:contentKeyID: 36056062
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- cost
- standard costs, manufactured items
- costs
- costing
- standard cost
audience: Application User
ms.search.region: Global
---

# Prepare to maintain standard costs for manufactured items 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The preparation steps for maintaining costs for manufactured item are slightly different than for purchased items. Policies assigned to manufactured items can affect the cost calculations for their parent manufactured items. To prepare for maintaining costs for manufactured items, follow these steps:

1.  Assign an item model group to the manufactured item.
    
    The item model group identifies the use of standard costs.

2.  Assign an item group to the manufactured item.
    
    The item group contains ledger accounts that apply to the manufactured item. The ledger accounts for a manufactured item with a standard cost inventory model include several production variances, the cost change variance, and inventory cost revaluation.

3.  Assign the inventory unit of measure to the item.
    
    The item’s costs are always expressed in the item’s inventory unit of measure.

4.  Do not assign a cost group to the manufactured item unless it will be treated as a purchased item.

5.  Assign a BOM calculation group to the manufactured item.
    
    The item’s BOM calculation group defines applicable warning conditions so that performing a BOM calculation will generate warning messages about possible sources of calculation errors. For example, a warning message can identify when an active BOM or route does not exist.
    
    The BOM calculation group contains a stop explosion policy that indicates when to treat a manufactured item as a purchased item.

6.  Assign a standard order quantity to the manufactured item when it has constant costs.
    
    The standard order quantity is an accounting lot size for amortizing constant costs. For example, setup times in routing operations or a constant component quantity in the bill of material.

7.  Define the BOM for the manufactured item. One or more BOM versions can be defined for the manufactured item. Verify that the versions that you want have been marked as approved and active and that they have the effective dates that you want. The BOM version can be company-wide or site-specific.

8.  Define the routing for the manufactured item. One or more route versions can be defined for the manufactured item. Verify that the versions that you want have been marked as approved and active and that they have the effective dates that you want. The route version must be site-specific.

The use of routing information for costing purposes will require additional preparation steps. For example, the cost categories that are assigned to routing operations must be correct and completed.

## See also

[About BOM calculation groups](about-bom-calculation-groups.md)

[About manufactured items that are treated as purchased items](about-manufactured-items-that-are-treated-as-purchased-items.md)

[About amortizing constant costs for a manufactured item](about-amortizing-constant-costs-for-a-manufactured-item.md)

[About displaying charges for a manufactured item](about-displaying-charges-for-a-manufactured-item.md)

  


