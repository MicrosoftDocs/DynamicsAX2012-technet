---
title: ThresholdDiscountMethod Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ThresholdDiscountMethod Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ThresholdDiscountMethod
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.thresholddiscountmethod(v=AX.60)
ms:contentKeyID: 62214224
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ThresholdDiscountMethod
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ThresholdDiscountMethod.AmountOff
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ThresholdDiscountMethod.PercentOff
dev_langs:
- CSharp
- C++
- VB
---

# ThresholdDiscountMethod Enumeration

Describes the discount method for threshold tier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration ThresholdDiscountMethod
'Usage
Dim instance As ThresholdDiscountMethod
```

``` csharp
[DataContractAttribute]
public enum ThresholdDiscountMethod
```

``` c++
[DataContractAttribute]
public enum class ThresholdDiscountMethod
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
<td>AmountOff</td>
<td>Give amount off discount.</td>
</tr>
<tr class="even">
<td></td>
<td>PercentOff</td>
<td>Give percent off discount.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to AX enum RetailThresholdDiscountMethod.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

