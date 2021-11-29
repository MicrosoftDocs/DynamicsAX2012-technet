---
title: PriceType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PriceType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.pricetype(v=AX.60)
ms:contentKeyID: 62208957
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceType.Percent
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceType.FromItem
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceType.Price
dev_langs:
- CSharp
- C++
- VB
---

# PriceType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Price type. Maps to RetailPriceType enum in AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration PriceType
'Usage
Dim instance As PriceType
```

``` csharp
[DataContractAttribute]
public enum PriceType
```

``` c++
[DataContractAttribute]
public enum class PriceType
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
<td>Default value.</td>
</tr>
<tr class="even">
<td></td>
<td>FromItem</td>
<td>From item type.</td>
</tr>
<tr class="odd">
<td></td>
<td>Price</td>
<td>The price type.</td>
</tr>
<tr class="even">
<td></td>
<td>Percent</td>
<td>The percent.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

