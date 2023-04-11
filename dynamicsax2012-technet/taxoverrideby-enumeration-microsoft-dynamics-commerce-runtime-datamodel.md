---
title: TaxOverrideBy Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxOverrideBy Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverrideBy
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxoverrideby(v=AX.60)
ms:contentKeyID: 62209498
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverrideBy
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverrideBy.Cart
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverrideBy.Line
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverrideBy.None
dev_langs:
- CSharp
- C++
- VB
---

# TaxOverrideBy Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the override tax by type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration TaxOverrideBy
'Usage
Dim instance As TaxOverrideBy
```

``` csharp
[DataContractAttribute]
public enum TaxOverrideBy
```

``` c++
[DataContractAttribute]
public enum class TaxOverrideBy
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
<td>Undefined value.</td>
</tr>
<tr class="even">
<td></td>
<td>Line</td>
<td>Item sales tax group override.</td>
</tr>
<tr class="odd">
<td></td>
<td>Cart</td>
<td>Sales tax group override.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

