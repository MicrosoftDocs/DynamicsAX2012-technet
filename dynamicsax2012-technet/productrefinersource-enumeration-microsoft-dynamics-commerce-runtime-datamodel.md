---
title: ProductRefinerSource Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductRefinerSource Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerSource
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrefinersource(v=AX.60)
ms:contentKeyID: 65321362
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerSource
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerSource.Attribute
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerSource.Category
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerSource.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerSource.Price
dev_langs:
- CSharp
- C++
- VB
---

# ProductRefinerSource Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the product information being used as a product refiner.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration ProductRefinerSource
'Usage
Dim instance As ProductRefinerSource
```

``` csharp
[DataContractAttribute]
public enum ProductRefinerSource
```

``` c++
[DataContractAttribute]
public enum class ProductRefinerSource
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
<td>No product refinement source defined.</td>
</tr>
<tr class="even">
<td></td>
<td>Attribute</td>
<td>Represents a product refiner that is derived from products' attributes/properties.</td>
</tr>
<tr class="odd">
<td></td>
<td>Category</td>
<td>Represents a product refiner that is derived from products' categories.</td>
</tr>
<tr class="even">
<td></td>
<td>Price</td>
<td>Represents a product refiner that is derived from products' prices.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

