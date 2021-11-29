---
title: TaxableBasisIndia Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxableBasisIndia Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableBasisIndia
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxablebasisindia(v=AX.60)
ms:contentKeyID: 62204782
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableBasisIndia.ExclusiveLineAmount
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableBasisIndia.MaxRetailPrice
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableBasisIndia.LineAmount
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableBasisIndia.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableBasisIndia.Assessable
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableBasisIndia
dev_langs:
- CSharp
- C++
- VB
---

# TaxableBasisIndia Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the type of tax base.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration TaxableBasisIndia
'Usage
Dim instance As TaxableBasisIndia
```

``` csharp
public enum TaxableBasisIndia
```

``` c++
public enum class TaxableBasisIndia
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
<td>No available tax basis.</td>
</tr>
<tr class="even">
<td></td>
<td>LineAmount</td>
<td>Line amount.</td>
</tr>
<tr class="odd">
<td></td>
<td>ExclusiveLineAmount</td>
<td>Exclude line amount.</td>
</tr>
<tr class="even">
<td></td>
<td>MaxRetailPrice</td>
<td>Max retail price.</td>
</tr>
<tr class="odd">
<td></td>
<td>Assessable</td>
<td>Assessable value.</td>
</tr>
</tbody>
</table>


## Remarks

This enum is mapped to base enum TaxableBasis\_IN in Ax.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

