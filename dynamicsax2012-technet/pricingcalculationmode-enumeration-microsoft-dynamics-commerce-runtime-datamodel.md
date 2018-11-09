---
title: PricingCalculationMode Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PricingCalculationMode Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.PricingCalculationMode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.pricingcalculationmode(v=AX.60)
ms:contentKeyID: 62207610
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PricingCalculationMode
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PricingCalculationMode.Independent
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PricingCalculationMode.Transaction
dev_langs:
- CSharp
- C++
- VB
---

# PricingCalculationMode Enumeration

Defines how the pricing calculation should act on the set of lines passed into it.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration PricingCalculationMode
'Usage
Dim instance As PricingCalculationMode
```

``` csharp
[DataContractAttribute]
public enum PricingCalculationMode
```

``` c++
[DataContractAttribute]
public enum class PricingCalculationMode
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
<td>Transaction</td>
<td>The set of lines should be interpreted as part of the same transaction.</td>
</tr>
<tr class="even">
<td></td>
<td>Independent</td>
<td>The set of lines should be interpreted separately. (E.g. for browsing or publishing).</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

