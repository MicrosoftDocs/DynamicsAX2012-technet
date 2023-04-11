---
title: ProductSource Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductSource Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSource
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productsource(v=AX.60)
ms:contentKeyID: 62205201
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSource
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSource.Remote
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSource.Local
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSource.None
dev_langs:
- CSharp
- C++
- VB
---

# ProductSource Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the source of the product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration ProductSource
'Usage
Dim instance As ProductSource
```

``` csharp
[DataContractAttribute]
public enum ProductSource
```

``` c++
[DataContractAttribute]
public enum class ProductSource
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
<td>The product was not found.</td>
</tr>
<tr class="even">
<td></td>
<td>Local</td>
<td>The product was retrieved from a local source.</td>
</tr>
<tr class="odd">
<td></td>
<td>Remote</td>
<td>The product was retrieved from a remote source.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

