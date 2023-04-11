---
title: About costing versions containing item sales prices related to BOM calculations
TOCTitle: About costing versions containing item sales prices related to BOM calculations
ms:assetid: e0b1ebf4-fd31-4263-aa7c-9224519e3eb5
ms:mtpsurl: https://technet.microsoft.com/library/Gg243207(v=AX.60)
ms:contentKeyID: 36688019
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About costing versions containing item sales prices related to BOM calculations 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A costing version can include content about the sales price records for items. The main reason for including content about sales prices is to retain a manufactured item's calculated sales price. The calculated sales price can then be analyzed to determine how components, routing operations, and overhead contribute to the cost and sales price.

A secondary reason for including content about sales prices is to define the sales price records for component items. These records can then be used to calculate the sales price of manufactured items. To use content about sales prices for this purpose, you define the sales price model that is embedded in a bill of material (BOM) calculation group, and then assign the BOM calculation group to purchased items. Then, when you perform BOM calculations with planned costs, you select the cost price model of the BOM calculation group.

Otherwise, the sales price records for items are only used for reference information, regardless of whether the records are manually entered or calculated. By activating an item's sales price record, you can update the item's base sales price. However, the base sales price is not site-specific, and it can be manually overridden. The item's base sales price is used as a default sales price on sales orders and sales quotations.

## See also

[About BOM calculation of a suggested sales price](about-bom-calculation-of-a-suggested-sales-price.md)

  


