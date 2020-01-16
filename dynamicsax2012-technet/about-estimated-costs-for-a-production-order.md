---
title: About estimated costs for a production order
TOCTitle: About estimated costs for a production order
ms:assetid: 212fab4c-dde6-41fe-b452-3596f6781775
ms:mtpsurl: https://technet.microsoft.com/library/Gg230983(v=AX.60)
ms:contentKeyID: 36056163
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- cost
- production
- orders
- estimate
- estimates
- production order
- estimation
- costing
- estimating
audience: Application User
ms.search.region: Global
---

# About estimated costs for a production order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The estimate task calculates estimated costs for a production order. The calculations of estimated cost are based on the quantity in the production order, the components in the production bills of materials (production BOMs), the routing operations in the production route, the indirect costs that apply to these components and operations, and the active cost data as of the calculation date. If there is a phantom line item in the production BOMs, the calculations reflect the phantom's components and route operations.

The estimate task can be used to recalculate estimated costs to reflect updated information. For example, the updated information can be changes to the quantity in the production order, the components in the production BOMs, the routing operations in the production route, the indirect costs that apply to these components and operations, or the active cost data as of the recalculation date.

The calculations of estimated cost also suggest a sales price for the production item, based on a cost-plus-markup approach.

The calculations of estimated cost can optionally apply to reference orders that reflect production orders that are linked to the production order.

## See also

[About analyzing costs for a production order](about-analyzing-costs-for-a-production-order.md)

  


