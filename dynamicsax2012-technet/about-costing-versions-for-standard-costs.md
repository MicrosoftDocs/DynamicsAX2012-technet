---
title: About costing versions for standard costs
TOCTitle: About costing versions for standard costs
ms:assetid: a7eb1e2f-32bc-452e-89c3-2ab2554b4cfc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243057(v=AX.60)
ms:contentKeyID: 36058882
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About costing versions for standard costs 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Costing versions for standard costs must be assigned to a type of standard cost, and they must allow content to include cost data. A costing version can contain a set of standard cost records about items, cost categories for routing operations, and calculation formulas for indirect costs.

Some restrictions apply to a costing version for standard costs. The following restrictions guarantee adherence to standard costing principles:

  - Charges must be included in an item's cost. The charges for a manufactured item represent the amortized constant costs in the bill of materials (BOM) and route information. Therefore, they must be included in the unit cost. The charges for a purchased item are also included in the item's unit cost.

  - Calculation of standard costs for manufactured items must be based on the cost records in a costing version for standard costs. Alternative sources of cost data, which are defined by the BOM calculation group, can only be used with a costing version for planned costs, such as purchase price trade agreements for purchased items.

  - BOM calculations must be performed in a single-level explosion mode.

The item cost data for standard costs can be copied to another costing version that contains standard costs or planned costs. However, the item cost data for planned costs cannot be copied to a cost version that contains standard costs, because the restrictions that are listed earlier in this topic do not apply to planned costs.

## See also

[About costing versions](about-costing-versions.md)

[Maintaining standard costs in a nonmanufacturing environment](maintaining-standard-costs-in-a-nonmanufacturing-environment.md)

[Maintaining standard costs in a manufacturing environment](maintaining-standard-costs-in-a-manufacturing-environment.md)

  


