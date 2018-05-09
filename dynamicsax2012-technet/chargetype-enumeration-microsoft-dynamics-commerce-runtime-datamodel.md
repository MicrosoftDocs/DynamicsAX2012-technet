---
title: ChargeType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChargeType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.chargetype(v=AX.60)
ms:contentKeyID: 49826182
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeType.AutoCharge
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeType.ManualCharge
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeType.PriceCharge
dev_langs:
- CSharp
- C++
- VB
---

# ChargeType Enumeration

Represents the type of charge being applied to the line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration ChargeType
'Usage
Dim instance As ChargeType
```

``` csharp
[DataContractAttribute]
public enum ChargeType
```

``` c++
[DataContractAttribute]
public enum class ChargeType
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
<td>ManualCharge</td>
<td>A manual charge.</td>
</tr>
<tr class="even">
<td></td>
<td>PriceCharge</td>
<td>A price charge.</td>
</tr>
<tr class="odd">
<td></td>
<td>AutoCharge</td>
<td>An automatic charge such as customer or shipping.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

