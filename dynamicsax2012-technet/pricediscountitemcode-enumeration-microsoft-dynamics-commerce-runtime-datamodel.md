---
title: PriceDiscountItemCode Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PriceDiscountItemCode Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountItemCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.pricediscountitemcode(v=AX.60)
ms:contentKeyID: 49849429
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountItemCode
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountItemCode.AllItems
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountItemCode.Item
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountItemCode.ItemGroup
dev_langs:
- CSharp
- C++
- VB
---

# PriceDiscountItemCode Enumeration

Enables to grant a discount with regard to an item, a superordinate item group or to all items.

Refers to table PriceDiscTable.ItemCode.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration PriceDiscountItemCode
'Usage
Dim instance As PriceDiscountItemCode
```

``` csharp
public enum PriceDiscountItemCode
```

``` c++
public enum class PriceDiscountItemCode
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
<td>Item</td>
<td>A discount for an item.</td>
</tr>
<tr class="even">
<td></td>
<td>ItemGroup</td>
<td>A discount for an item group.</td>
</tr>
<tr class="odd">
<td></td>
<td>AllItems</td>
<td>A discount for all items.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to the TableGroupAll enum in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

