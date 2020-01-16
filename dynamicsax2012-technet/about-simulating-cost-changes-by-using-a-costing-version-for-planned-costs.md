---
title: About simulating cost changes by using a costing version for planned costs
TOCTitle: About simulating cost changes by using a costing version for planned costs
ms:assetid: 16ba839b-a321-4bbf-b494-925ee78a4c57
ms:mtpsurl: https://technet.microsoft.com/library/Gg230960(v=AX.60)
ms:contentKeyID: 36056076
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About simulating cost changes by using a costing version for planned costs 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The effects of cost changes on a manufactured item’s calculated costs can be simulated with a separate costing version for planned costs. Use the separate costing version for entering pending cost records that reflect incremental cost changes, and for calculating the cost impact on manufactured items. A fallback principle of active costs will be used in the BOM calculations so that only the incremental cost changes must be entered.

Use the following guidelines for defining the simulation costing version.

  - Assign a costing type of planned costs.

  - Assign a meaningful identifier for the costing version, such as simulation.

  - Ensure that the content includes cost records.

  - Allow the entry of cost records. Do not block the entry of pending costs.

  - Allow the entry of cost records for all sites. Entering a site will limit the entry of cost records to the single site.

  - Prevent the activation of pending costs. Only pending costs must be entered for cost records in the simulation costing version.

  - Do not enter a from-date. A calculation date will be entered for each BOM calculation that uses the simulation costing version.

  - Indicate a fallback principle of current active. The fallback principle allows the entry of incremental cost changes for simulation purposes, while using the current active costs as the source for all other cost records. It is assumed that all current active costs exist for all other cost records.

  - Indicate a cost price model of version cost price, but do not restrict calculations. For example, the simulations could also use a cost price model of BOM calculation group to indicate the source of cost contribution data for purchased items.

  - Indicate an explosion mode of multilevel, but do not restrict calculations. The simulations could use other explosion modes.

## Costing versions

The following scenarios illustrate the use of the simulation costing version to simulate the impact of cost changes. Prior to entering a simulated cost change, delete the pending cost records in the simulation costing version so that you have a clean starting point. Use the **Item price** form to view and delete the pending cost records that are related to item prices and cost category prices.

  - Simulate the cost change for a purchased item. For example, the cost change may reflect an expected increase or decrease in the costs of critical purchased materials. To define the different cost for a purchased item, use the **Item price** form to enter a pending cost record in the simulation costing version.

  - Simulate the cost change for a cost category. For example, the cost change may reflect an expected increase or decrease in labor rates, or in hourly rates for operations resources. To define the different cost for a cost category, use the **Cost category price** form to enter a pending cost record in the simulation costing version.

  - Simulate the cost change in an indirect cost calculation formula. For example, the cost change may reflect an expected increase or decrease in manufacturing overheads. To define the change in an indirect cost calculation formula, use the **Costing sheet setup** form to enter a pending cost record in the simulation costing version, and to validate and save the change.

After entering the simulated cost changes, calculate the costs for manufactured items that are affected by the cost changes. Use the **Calculation** form for the simulation costing version, and identify the selected manufactured items that will be affected by the cost changes. The BOM calculations apply to all manufactured items unless you identify the selected items. Alternatively, you can use the BOM calculation option for where-used updates.

View the item cost records in the simulation costing version to analyze how the simulated cost changes affected the costs of the selected manufactured items. Use the **Item price** form and the **Calculate item cost** form to view and analyze the costs.

## See also

[About BOM calculations](about-bom-calculations.md)

  


