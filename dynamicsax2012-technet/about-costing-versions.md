---
title: About costing versions
TOCTitle: About costing versions
ms:assetid: 3f27786f-9a91-4699-88a1-2776e437c18b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231168(v=AX.60)
ms:contentKeyID: 36056698
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- cost
- costs
- costing version
- costing
- costing versions
---

# About costing versions [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A costing version can serve one or more purposes based on the data that is contained within the costing version. The primary purpose of a costing version is to contain cost records about items, cost categories, and indirect cost calculation formulas. A costing version can contain a set of standard cost records or a set of planned cost records that are based on the costing type that is assigned to the costing version.

  - Standard costs − A costing version can support a standard cost inventory model for items, where the costing version contains a set of standard cost records about items and manufacturing processes. Cost data about manufacturing processes is expressed in terms of the cost categories for routing operations and the calculation formulas for manufacturing overheads.

  - Planned costs − A costing version can contain a set of planned cost records about items and manufacturing processes. A costing version with planned costs is often used to support cost calculation simulations, such as simulating the effect of cost changes to purchased materials or manufacturing processes on the calculated costs of manufactured items. The item cost records for planned costs can also be used to support an actual cost inventory model by providing the initial values for item costs, including the calculation of planned costs for manufactured items.

Maintaining cost records within a costing version involves entering costs for purchased items and for items that are transferred between sites. Additional data maintenance for manufacturers involves entering costs for cost categories, which are associated with routing operations; entering calculation formulas for the indirect costs reflecting manufacturing overheads; and calculating costs for manufactured items.

The item cost data within a costing version will consist of one or more cost records for each item. An item cost record is initially entered with a pending status and an intended effective date. Activating the item cost record updates the status to active and the effective date to the activation date. Different item cost records may reflect different sites, effective dates, or status. When calculating costs for manufactured items for a future date, the BOM calculation will use cost records with the relevant effective date whether status is pending or active. An item's current active cost record will be used for estimating production order costs and valuing inventory transactions under a standard costing inventory model. The maintenance of cost records for cost categories and indirect cost calculation formulas is similar to the maintenance of item cost records.

Two blocking policies for a costing version determine whether pending costs can be maintained and whether the pending cost can be activated. Use the blocking policies to permit data maintenance, and then to prevent data maintenance for cost records within a costing version.

A costing version can also contain data about item sales prices or purchase prices for BOM calculation purposes.

  - Item sales prices for BOM calculation purposes − A BOM calculation can calculate a sales price for manufactured items, and a BOM calculation can generate an associated sales price record within the costing version.

  - Item purchase prices for BOM calculation purposes − A BOM calculation with planned costs can be based on item purchase price records within the costing version, rather than item cost records. The item purchase price records must be manually entered.

  - The item sales price records and purchase price records are only used for BOM calculation purposes.

## See also

[About costing versions for standard costs](about-costing-versions-for-standard-costs.md)

[About costing versions containing item sales prices related to BOM calculations](about-costing-versions-containing-item-sales-prices-related-to-bom-calculations.md)

[About costing versions containing item purchase prices related to BOM calculations](about-costing-versions-containing-item-purchase-prices-related-to-bom-calculations.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

