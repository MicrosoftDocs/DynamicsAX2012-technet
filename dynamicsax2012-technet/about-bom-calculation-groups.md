---
title: About BOM calculation groups
TOCTitle: About BOM calculation groups
ms:assetid: 850802da-169a-49ed-a25c-fbfc49309994
ms:mtpsurl: https://technet.microsoft.com/library/Gg213176(v=AX.60)
ms:contentKeyID: 36058401
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About BOM calculation groups 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

One purpose of assigning a BOM calculation group to items is to define applicable warning conditions so that a BOM calculation generates warning messages about potential sources of calculation errors. A BOM calculation generates an Infolog that contains the warning messages. You can view this warning Infolog about a selected item when you use the **Complete** form to review BOM calculation results. The form displays an icon that indicates that a warning Infolog exists for an item.

Two warning conditions only apply to manufactured items, and four warning conditions apply to any item.

  - Identify when a manufactured item does not have an active BOM.

  - Identify when a manufactured item does not have an active route.

  - Identify a warning when the item in a BOM line has a 0 (zero) quantity.

  - Identify a warning when the item in a BOM line has a 0 (zero) cost or when it does not have a cost record.

  - Identify a warning when the item in a BOM line has an out-of-date cost. The warning reflects a comparison of the calculation date to the specified days for a maximum age of cost.

  - Identify a warning when the item in a BOM line has less than the profitability percentage that you want.

The definition of various BOM calculation groups depends on the need for variations in applicable warning messages. For example, one BOM calculation group may be sufficient, with warning conditions about an active BOM, a zero component quantity, and a zero component cost.

The applicable warning conditions that are associated with the BOM calculation group can be optionally overridden when you initiate a BOM calculation. You can add or remove an applicable warning condition. For example, you could remove the applicable warning condition about an active route when the specific situation does not involve routing data.

The assignment of a BOM calculation group to items can serve other special purposes. The special purposes include the following:

  - Indicate the source of a purchased component’s cost contribution data in calculating the planned cost of a manufactured item (by using the cost price model field). Some manufacturers calculate planned costs by using the purchase price trade agreements for purchased components or another basis, such as the purchase price records in a costing version. The approach that you want is termed the cost price model. The decision about the source of cost data should be reflected in the definition and assignment of BOM calculation groups.

  - Indicate how the item’s data will be used to calculate a suggested sales price. This is done in the sales price model field. Some manufacturers want to calculate a suggested sales price for manufactured items. The calculated sales price can reflect a rolled-price approach that is based on the component’s sales price record. It could also be a cost-plus-markup approach that is based on the component’s cost and applicable profit percentage. This is associated with the item’s cost group.. The approach that you want is termed the sales price model, with a choice between item sales price and cost group. The decision about a rolled-price versus cost-plus-markup approach should be reflected in the definition and assignment of BOM calculation groups.

  - Indicate that a manufactured item should be treated as a purchased item for BOM calculation purposes by using the stop explosion field. A manufactured item can be treated as a purchased item for cost-rollup purposes. The typical situations include a purchased item that is occasionally manufactured or a manufactured item that is now being purchased. The item will first be designated as a manufactured item to define BOM and route information, and to support production orders for the item. However, the stop explosion flag prevents cost calculations from using the item’s BOM and route, and the BOM calculation uses the item’s specified costs.


> [!NOTE]
> <P>The <STRONG>Time and attendance</STRONG> module contains the <STRONG>Calculation groups</STRONG> form, but that form has no relationship to BOM calculation groups. In <STRONG>Time and attendance</STRONG>, workers can be assigned to calculation groups which reflect the grouping of workers associated with the same supervisor or manager. Calculation of workers’ registrations can be done automatically or manually by a supervisor or manager.</P>



## See also

[About BOM calculations](about-bom-calculations.md)

[About manufactured items that are treated as purchased items](about-manufactured-items-that-are-treated-as-purchased-items.md)

[About BOM calculation of a suggested sales price](about-bom-calculation-of-a-suggested-sales-price.md)

  


