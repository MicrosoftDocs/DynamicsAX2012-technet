---
title: About updating standard costs in a manufacturing environment
TOCTitle: About updating standard costs in a manufacturing environment
ms:assetid: 12e6158c-95f5-4381-84d3-7dc5127b7a0f
ms:mtpsurl: https://technet.microsoft.com/library/Gg230934(v=AX.60)
ms:contentKeyID: 36687814
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- cost
- updates
- costs
- manufacturing
- costing
- standard cost
- standard costs
audience: Application User
ms.search.region: Global
---

# About updating standard costs in a manufacturing environment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Manufacturing environments involve maintaining standard costs for purchased items and manufactured items, which includes the scenario for updating standard costs throughout the frozen period. Updates may reflect new items, cost categories, or indirect cost calculation formulas, corrections, and cost changes. The type of update will affect the steps that are required to update standard costs, as illustrated in the following cases.

  - Enter expected standard cost changes for purchased items, and then change the status of the item cost records to active on the appropriate date. However, do not recalculate the costs of manufactured items that use the purchased items.

  - Enter standard costs for a new purchased item, but do not recalculate the costs of manufactured items with a bill of material (BOM) version that contains the new purchased item as a component.

  - Correct or change the cost of a purchased item, or change the cost group that is assigned to a purchased item, and calculate the cost for all manufactured items with a BOM version that contains the purchased item as a component.

  - Change the cost for a cost category, and calculate the cost for all manufactured items with a route version that contains routing operations that use the cost category.

  - Change the cost categories that are assigned to routing operations or the cost group that is assigned to cost categories. Then calculate the cost for all manufactured items with a route version that contains routing operations that use the cost category.

  - Change an indirect cost calculation formula, and calculate the cost for all manufactured items that are affected by the change.

  - Change or add a manufacturing site for a manufactured item, and calculate the item's manufactured cost for the site.

  - Calculate, or recalculate, the cost for a manufactured item, and recalculate the cost for all manufactured items with a BOM version that contains the manufactured item as a component.

  - Calculate costs for a new manufactured item based on its defined, approved, and active BOM and route information.

Each case requires careful consideration about how to update standard costs.

## See also

[About updating standard costs for a new manufactured item](about-updating-standard-costs-for-a-new-manufactured-item.md)

  


