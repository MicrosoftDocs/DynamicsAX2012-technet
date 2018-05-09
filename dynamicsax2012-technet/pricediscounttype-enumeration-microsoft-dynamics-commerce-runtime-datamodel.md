---
title: PriceDiscountType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PriceDiscountType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.pricediscounttype(v=AX.60)
ms:contentKeyID: 49839106
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountType.EndDiscountSales
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountType.LineDiscountSales
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountType.MultilineDiscountSales
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountType.PriceSales
dev_langs:
- CSharp
- C++
- VB
---

# PriceDiscountType Enumeration

Represents the type of a trade agreement.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration PriceDiscountType
'Usage
Dim instance As PriceDiscountType
```

``` csharp
public enum PriceDiscountType
```

``` c++
public enum class PriceDiscountType
```

## Members

<table>
<thead>
<tr class="header">
<th></th>
<th>Member name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td></td>
<td>None</td>
<td>No price discount type specified.</td>
</tr>
<tr class="even">
<td></td>
<td>PriceSales</td>
<td>Sales price trade agreement.</td>
</tr>
<tr class="odd">
<td></td>
<td>LineDiscountSales</td>
<td>Predefined line discount for an item.</td>
</tr>
<tr class="even">
<td></td>
<td>MultilineDiscountSales</td>
<td>Predefined discount for the multiple of a certain item.</td>
</tr>
<tr class="odd">
<td></td>
<td>EndDiscountSales</td>
<td>Total discount value granted at the end of a transaction (globally) retroactive to each item.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to the PriceType enum in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

