---
title: CalculationModes Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CalculationModes Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.calculationmodes(v=AX.60)
ms:contentKeyID: 49826765
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes.All
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes.Charges
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes.Discounts
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes.Prices
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes.Taxes
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes.Totals
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes.AmountDue
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes.Deposit
dev_langs:
- CSharp
- C++
- VB
---

# CalculationModes Enumeration

An enumeration used to indicate which combination of calculations should be performed when returning the cart.

This enumeration has a [FlagsAttribute](https://technet.microsoft.com/library/dk06fkbc\(v=ax.60\)) attribute that allows a bitwise combination of its member values.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<FlagsAttribute> _
Public Enumeration CalculationModes
'Usage
Dim instance As CalculationModes
```

``` csharp
[FlagsAttribute]
public enum CalculationModes
```

``` c++
[FlagsAttribute]
public enum class CalculationModes
```

## Members

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
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
<td>No calculations are performed.
<p>This value must be checked directly and not used with HasFlags method.</p></td>
</tr>
<tr class="even">
<td></td>
<td>Prices</td>
<td>Prices are calculated.</td>
</tr>
<tr class="odd">
<td></td>
<td>Discounts</td>
<td>Discounts are calculated.</td>
</tr>
<tr class="even">
<td></td>
<td>Charges</td>
<td>Charges are calculated.</td>
</tr>
<tr class="odd">
<td></td>
<td>Taxes</td>
<td>Taxes are calculated.</td>
</tr>
<tr class="even">
<td></td>
<td>Totals</td>
<td>Totals are calculated and rounded.</td>
</tr>
<tr class="odd">
<td></td>
<td>Deposit</td>
<td>Deposit and prepayments are calculated.</td>
</tr>
<tr class="even">
<td></td>
<td>AmountDue</td>
<td>Amount due (balance due) is calculated.</td>
</tr>
<tr class="odd">
<td></td>
<td>All</td>
<td>All calculations are performed.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

