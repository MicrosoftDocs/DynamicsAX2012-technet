---
title: About BOM calculations that use the fallback principle
TOCTitle: About BOM calculations that use the fallback principle
ms:assetid: 9c127b08-9328-4fd3-acfd-4dc4c6a77d8d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213366(v=AX.60)
ms:contentKeyID: 36058725
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About BOM calculations that use the fallback principle 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Bill of materials (BOM) calculations that use cost records in a single, specified costing version do not use a fallback principle. However, BOM calculations that use another costing version or active cost records as a fallback principle can be useful in certain situations. The fallback principle indicates an alternative source of cost data if there is no cost data in the specified costing version. The following situations illustrate two uses of the fallback principle:

  - Two-version approach to standard cost updates – A costing version can contain the incremental changes to standard costs, such as pending cost records that represent new items or cost changes. In this situation, the fallback principle can identify the use of the active standard costs that are contained in other costing versions.

  - Simulating the effect of cost changes with planned costs – A costing version for planned costs can contain incremental changes for simulation purposes. This costing version would include pending cost records that represent the simulated cost changes to items, cost categories, and calculation formulas for indirect cost. In this situation, the fallback principle can identify the use of the active standard costs that are contained in other costing versions.

## See also

[About managing standard cost updates](about-managing-standard-cost-updates.md)

[About simulating cost changes by using a costing version for planned costs](about-simulating-cost-changes-by-using-a-costing-version-for-planned-costs.md)

[About BOM calculations](about-bom-calculations.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

