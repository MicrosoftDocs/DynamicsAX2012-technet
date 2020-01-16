---
title: ConcurrencyMode Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ConcurrencyMode Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ConcurrencyMode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.concurrencymode(v=AX.60)
ms:contentKeyID: 49833004
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ConcurrencyMode
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ConcurrencyMode.BestPrice
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ConcurrencyMode.Compounded
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ConcurrencyMode.Exclusive
dev_langs:
- CSharp
- C++
- VB
---

# ConcurrencyMode Enumeration

Specifies how the discount should interact with other discounts on a line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration ConcurrencyMode
'Usage
Dim instance As ConcurrencyMode
```

``` csharp
[DataContractAttribute]
public enum ConcurrencyMode
```

``` c++
[DataContractAttribute]
public enum class ConcurrencyMode
```

## Members

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
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
<td>Exclusive</td>
<td>If this discount applies, it overrides all others. If multiple Exclusive discounts apply, the Best Price is chosen.</td>
</tr>
<tr class="even">
<td></td>
<td>BestPrice</td>
<td>If this discount applies, the best price between all discounts applies.
<p>This only has an effect if there are no Exclusive discounts.</p></td>
</tr>
<tr class="odd">
<td></td>
<td>Compounded</td>
<td>If this discount applies, it will be compounded with all other discounts also marked as Compounded.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to the RetailDiscountConcurrency enum in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

