---
title: CartStatus Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CartStatus Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartStatus
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cartstatus(v=AX.60)
ms:contentKeyID: 65320788
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartStatus
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartStatus.Created
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartStatus.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartStatus.Suspended
dev_langs:
- CSharp
- C++
- VB
---

# CartStatus Enumeration

Represents the status of cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration CartStatus
'Usage
Dim instance As CartStatus
```

``` csharp
public enum CartStatus
```

``` c++
public enum class CartStatus
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
<td>Default value, new cart (from request) which hasn't be processed.</td>
</tr>
<tr class="even">
<td></td>
<td>Created</td>
<td>The cart is created.</td>
</tr>
<tr class="odd">
<td></td>
<td>Suspended</td>
<td>The cart is suspended.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

