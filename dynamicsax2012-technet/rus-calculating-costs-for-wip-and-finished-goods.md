---
title: (RUS) Calculating costs for WIP and finished goods
TOCTitle: (RUS) Calculating costs for WIP and finished goods
ms:assetid: 16096e1e-99d7-4640-8a54-3fae9538d71e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711422(v=AX.60)
ms:contentKeyID: 49387240
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Calculating costs for WIP and finished goods 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Companies can calculate the cost of works in process (WIP) and finished items at the end of each reporting period. Microsoft Dynamics AX lets you calculate the cost of a production order by using the normative method or the proportional method.

## Normative method for calculating costs

You can use the normative method to calculate the cost of WIP and finished items by using normative costs for the production order. The remaining costs are calculated based on actual cost. When you use the normative method to distribute costs, you can calculate the standard costs for all of the production items. The bill of materials (BOM) is calculated periodically to maintain actual standard cost prices. For more information, see [About BOM calculations](about-bom-calculations.md).

## Calculating the cost of WIP

The quantity of WIP is calculated for every operation by using the following formula:

WIP quantity = (Started quantity – Defective products quantity – Good quantity produced)

The normative cost that is accumulated per unit for each operation is calculated as the sum of the normative cost for an operation and the normative cost of the previous operation. The WIP cost for every operation is calculated by multiplying the WIP quantity and the normative cost that is accumulated per unit for each operation. The sum of the WIP cost for each operation provides the WIP cost of the production order. Indirect costs contribute to the cost of the operation.

## Calculating the cost of finished items

The cost of finished items is calculated by using the following formula:

Finished item cost = (A – WIP cost – Defective products – Fr)

  - A – The actual cost of the production order.

  - WIP cost – The cost of WIP in the production order.

  - Defective products – The cost of defective products in the production order.

  - Fr – The cost of by-products in the production order.

## Proportional allocation method for calculating costs

You can use the proportional allocation method to calculate and distribute the cost of production among WIP and finished items. The proportional allocation method uses the actual costs to calculate production costs for WIP and finished items.

## Calculating the cost of WIP

WIP is calculated from the ratio between the quantity of work units that are used in the operation and the quantity of work units that are produced from the operation.

WIP cost = {(Costs – Fr) \* \[Qty (P) – Qty (C)\] / Qty (P)}

  - Costs – The actual costs accumulated on a per-operation basis up to the calculation date.

  - Fr – The cost of the by-products from the current operation.

  - Qty (P) – The quantity of work units from the previous operation.

  - Qty (C) – The quantity of work units from the current operation.

## Calculating the cost of finished items

The cost of the finished goods generated during the period is calculated by using the following formula:

Finished goods cost = Costs – WIP cost – Defective products – Fr

  


