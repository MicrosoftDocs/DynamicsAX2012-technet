---
title: DiscountCalculationMode Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountCalculationMode Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCalculationMode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.discountcalculationmode(v=AX.60)
ms:contentKeyID: 62214076
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCalculationMode.CalculateThreshold
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCalculationMode
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCalculationMode.CalculateAll
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCalculationMode.CalculateOffer
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCalculationMode.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCalculationMode.CalculateMixAndMatch
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCalculationMode.CalculateMultipleBuy
dev_langs:
- CSharp
- C++
- VB
---

# DiscountCalculationMode Enumeration

Defines how the pricing calculation should act on the set of lines passed into it.

This enumeration has a [FlagsAttribute](https://technet.microsoft.com/en-us/library/dk06fkbc\(v=ax.60\)) attribute that allows a bitwise combination of its member values.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
<FlagsAttribute> _
Public Enumeration DiscountCalculationMode
'Usage
Dim instance As DiscountCalculationMode
```

``` csharp
[DataContractAttribute]
[FlagsAttribute]
public enum DiscountCalculationMode
```

``` c++
[DataContractAttribute]
[FlagsAttribute]
public enum class DiscountCalculationMode
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
<td>Calculate none.</td>
</tr>
<tr class="even">
<td></td>
<td>CalculateOffer</td>
<td>Calculate discount offer.</td>
</tr>
<tr class="odd">
<td></td>
<td>CalculateMultipleBuy</td>
<td>Calculate multiple buy.</td>
</tr>
<tr class="even">
<td></td>
<td>CalculateMixAndMatch</td>
<td>Calculate mix and match.</td>
</tr>
<tr class="odd">
<td></td>
<td>CalculateThreshold</td>
<td>Calculate threshold.</td>
</tr>
<tr class="even">
<td></td>
<td>CalculateAll</td>
<td>Calculate all.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

