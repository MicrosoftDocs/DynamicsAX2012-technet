---
title: About manufactured items that are treated as purchased items
TOCTitle: About manufactured items that are treated as purchased items
ms:assetid: b746cb6e-aea1-41e5-b292-0bc3e6aed14a
ms:mtpsurl: https://technet.microsoft.com/library/Gg232436(v=AX.60)
ms:contentKeyID: 36059101
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- manufactured items
- manufactured items as purchased
- purchased items
audience: Application User
ms.search.region: Global
---

# About manufactured items that are treated as purchased items 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A manufactured item can be treated as a purchased item for master scheduling and cost-rollup purposes. Typical situations include a purchased item that is occasionally manufactured or a manufactured item that has been changed to being a primarily purchased item. The item is first designated as a manufactured item in order to define bill-of-material and route information, and to support production orders for the item.

The item cost record can be calculated for the manufactured item, but it might not match the standard cost that you want for purchasing purposes. The standard cost that must be manually entered and activated for the item cost record. In addition, a manufactured item at one site can be transferred to another site. Therefore, the item's cost must be manually entered and activated for the site that the item is transferred to.

When you use the manufactured item as a component in higher-level products, the component's costs should be treated as a purchased item. This applies whether the component’s costs were calculated or manually entered. That is, a BOM calculation should treat the item's costs as a purchased component instead of calculating costs that are based on its bill and route information. You can prevent this calculation from occurring by selecting the stop explosion flag that is embedded in the BOM calculation group that is assigned to the item.

You can prevent master scheduling calculations from exploding requirements through the item by selecting the stop explosion flag (for item coverage) for the item. The master scheduling calculation will treat the item as a purchased item and will not perform more calculations for its bill and route information.

## See also

[About BOM calculation groups](about-bom-calculation-groups.md)

[About BOM calculations](about-bom-calculations.md)

  


