---
title: About order-specific BOM calculations
TOCTitle: About order-specific BOM calculations
ms:assetid: 9a87c706-3c3c-4abe-9e76-cbfd48942092
ms:mtpsurl: https://technet.microsoft.com/library/Gg232253(v=AX.60)
ms:contentKeyID: 36687936
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About order-specific BOM calculations 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

An order-specific bill of materials (BOM) calculation represents a variation of a BOM calculation for a manufactured item. An order-specific BOM calculation is performed in the context of a sales order, sales quotation, or service order line item. An order-specific BOM calculation generates a calculation record that is displayed in the **BOM calculation results** form. The calculation record includes a calculated weight, a calculated cost that is based on active cost records, and a calculated sales price. Each order-specific BOM calculation for an item generates a calculation record in the **BOM calculation results** form, uniquely identified by a calculation number. The results of a calculation record can optionally be transferred to the originating line item.

An order-specific BOM calculation differs from a BOM calculation for a manufactured item. First, an order-specific BOM calculation does not generate an item cost record throughout a costing version. This results in the BOM calculation policies not applying to create an item cost record or to overwrite a cost record. Second, an order-specific BOM calculation always uses the active cost records for components, cost categories, and indirect cost calculation formulas.

## See also

[About BOM calculations](about-bom-calculations.md)

  


