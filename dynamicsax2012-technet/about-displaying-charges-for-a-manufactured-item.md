---
title: About displaying charges for a manufactured item
TOCTitle: About displaying charges for a manufactured item
ms:assetid: a7e77c49-797e-45b5-8f0e-247a7b15cee7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243055(v=AX.60)
ms:contentKeyID: 36058881
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About displaying charges for a manufactured item 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Charges are the calculated amount of an item's amortized constant costs. The constant costs of a manufactured item reflect the operation setup times and the components that have a constant quantity or a constant scrap amount. For more information, see [About amortizing constant costs for a manufactured item](about-amortizing-constant-costs-for-a-manufactured-item.md).

The calculated amount of an item's charges can be displayed with the item's unit costs. However, the charges are sometimes displayed as separate fields, and they are not included in the item's unit costs. When the charges appear as separate fields, one field displays the total amount of charges, and another field displays the costing lot size that is used to amortize the amount. The **Item price** form, for example, displays the charges as two separate fields. However, the **Complete** form displays the item's total cost per unit, and the amortized costs are included in the unit costs.

The charges for a manufactured item are always included in the item's unit cost for standard cost purposes. They can optionally be included for planned cost purposes. A policy in the costing version enforces the inclusion of charges in the cost of a manufactured item.

When you activate an item's cost record, you update the charges for the item's base cost information, which is displayed in the **Item price** form. The charges are displayed as two separate fields, and they are not included in the item's unit cost. Each activation updates the item's base cost information, even if the activation reflects different sites. Therefore, you should view the base cost information as reference information.

## See also

[About amortizing constant costs for a manufactured item](about-amortizing-constant-costs-for-a-manufactured-item.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

