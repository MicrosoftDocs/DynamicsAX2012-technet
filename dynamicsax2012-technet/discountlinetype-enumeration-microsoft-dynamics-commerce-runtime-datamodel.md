---
title: DiscountLineType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountLineType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLineType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountlinetype(v=AX.60)
ms:contentKeyID: 49847016
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLineType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLineType.CustomerDiscount
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLineType.PeriodicDiscount
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLineType.LoyaltyDiscount
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLineType.ManualDiscount
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountLineType.None
dev_langs:
- CSharp
- C++
- VB
---

# DiscountLineType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the different types of discount lines.

Maps to base enum RetailDiscountOrigin in AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration DiscountLineType
'Usage
Dim instance As DiscountLineType
```

``` csharp
[DataContractAttribute]
public enum DiscountLineType
```

``` c++
[DataContractAttribute]
public enum class DiscountLineType
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
<td>No discount line type.</td>
</tr>
<tr class="even">
<td></td>
<td>CustomerDiscount</td>
<td>A customer discosunt.</td>
</tr>
<tr class="odd">
<td></td>
<td>PeriodicDiscount</td>
<td>A periodic discount.</td>
</tr>
<tr class="even">
<td></td>
<td>ManualDiscount</td>
<td>A manual discount.</td>
</tr>
<tr class="odd">
<td></td>
<td>LoyaltyDiscount</td>
<td>A loyalty points discount.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

