---
title: About analyzing common sources of production variances
TOCTitle: About analyzing common sources of production variances
ms:assetid: c9cda8e9-49eb-4224-99bc-35b5e7bb3ff1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213654(v=AX.60)
ms:contentKeyID: 36059327
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About analyzing common sources of production variances 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Each production variance can stem from several sources. The common sources for a lot-size variance include the following:

  - The good quantity for a production order differs from the calculation quantity that is used in the standard cost calculation. The quantity provides the basis for amortizing constant costs.

  - The value of constant costs in the production order differs from the constant costs that are used in the standard cost calculation. The constant costs in the production order can be different for several reasons. For example, the constant costs could reflect:
    
      - Manual changes to the production bill of materials (BOM) or route.
    
      - The selection of a different BOM version or route version when you are creating the production order.
    
      - Planned engineering changes to the BOM version or route version that is assigned to the item.

The common sources for a production-price variance include the following:

  - The cost category (and its cost-category price) for the reported consumption of a routing operation differs from the cost category that is used in standard cost calculation.

  - The active cost for the cost-category price differs from the cost-category price that is used in standard cost calculation.

The common sources for a production-quantity variance include the following:

  - Over-issue a material component or under-issue a material component.

  - Over-report time for a routing operation or under-report time for a routing operation.

  - Over-receive or under-receive the good quantity of the parent item relative to the order quantity, but issue components and report operations completely, based on the order quantity for the production order.

The common sources for a production-substitution variance include the following:

  - Issue a material component that is not in the production BOM.

  - Add a component manually to the production BOM, and report it as consumed.

  - Report an item as consumed, without adding it manually to the production BOM.

  - Add an operation manually to the production route, and report it as consumed.

  - Select a different BOM version when you are creating the production order, where the BOM version differs from the one that is used in the standard cost calculation.

  - Select a different route version when you are creating the production order, where the route version differs from the one that is used in the standard cost calculation.

  


