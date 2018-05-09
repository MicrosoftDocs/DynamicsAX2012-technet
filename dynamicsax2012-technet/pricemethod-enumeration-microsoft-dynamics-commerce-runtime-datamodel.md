---
title: PriceMethod Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PriceMethod Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceMethod
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.pricemethod(v=AX.60)
ms:contentKeyID: 62209474
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceMethod.PercentOff
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceMethod.Fixed
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceMethod.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceMethod.AmountOff
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceMethod
dev_langs:
- CSharp
- C++
- VB
---

# PriceMethod Enumeration

Defines meaning of the value on a PriceLine.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration PriceMethod
'Usage
Dim instance As PriceMethod
```

``` csharp
[DataContractAttribute]
public enum PriceMethod
```

``` c++
[DataContractAttribute]
public enum class PriceMethod
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
<td>Unspecified price method.</td>
</tr>
<tr class="even">
<td></td>
<td>Fixed</td>
<td>The value is a fixed price.</td>
</tr>
<tr class="odd">
<td></td>
<td>AmountOff</td>
<td>The value should be subtracted from a fixed price or previously reduced price.</td>
</tr>
<tr class="even">
<td></td>
<td>PercentOff</td>
<td>The percent should be multiplied against a fixed price or previously reduced price.
<p>E.g. value of 30 means 30% off. So price before reduction should be muliplied by 0.7 to get the new price.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

