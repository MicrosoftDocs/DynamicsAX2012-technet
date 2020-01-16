---
title: RoundingMethod Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RoundingMethod Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingMethod
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.roundingmethod(v=AX.60)
ms:contentKeyID: 62210190
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingMethod.Nearest
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingMethod.Down
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingMethod.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingMethod.Up
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RoundingMethod
dev_langs:
- CSharp
- C++
- VB
---

# RoundingMethod Enumeration

Rounding method for tender types.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration RoundingMethod
'Usage
Dim instance As RoundingMethod
```

``` csharp
[DataContractAttribute]
public enum RoundingMethod
```

``` c++
[DataContractAttribute]
public enum class RoundingMethod
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
<td>No rounding.</td>
</tr>
<tr class="even">
<td></td>
<td>Nearest</td>
<td>The rounding method round to the nearest value.</td>
</tr>
<tr class="odd">
<td></td>
<td>Up</td>
<td>The rounding method to round up.</td>
</tr>
<tr class="even">
<td></td>
<td>Down</td>
<td>The rounding method to round down.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

