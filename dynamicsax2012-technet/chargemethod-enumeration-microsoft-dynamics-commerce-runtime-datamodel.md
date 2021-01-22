---
title: ChargeMethod Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChargeMethod Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeMethod
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargemethod(v=AX.60)
ms:contentKeyID: 49836048
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeMethod
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeMethod.External
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeMethod.Fixed
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeMethod.Percent
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeMethod.Pieces
dev_langs:
- CSharp
- C++
- VB
---

# ChargeMethod Enumeration

Represents the charge method.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration ChargeMethod
'Usage
Dim instance As ChargeMethod
```

``` csharp
public enum ChargeMethod
```

``` c++
public enum class ChargeMethod
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
<td>Fixed</td>
<td>A fixed charge.</td>
</tr>
<tr class="even">
<td></td>
<td>Pieces</td>
<td>A piece-based charge.</td>
</tr>
<tr class="odd">
<td></td>
<td>Percent</td>
<td>A percentage-based charge.</td>
</tr>
<tr class="even">
<td></td>
<td>External</td>
<td>An external charge.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to the MarkupCategory enum in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

