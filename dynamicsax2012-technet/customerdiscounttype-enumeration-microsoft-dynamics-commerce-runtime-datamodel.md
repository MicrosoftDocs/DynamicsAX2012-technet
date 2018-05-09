---
title: CustomerDiscountType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerDiscountType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerDiscountType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.customerdiscounttype(v=AX.60)
ms:contentKeyID: 49845360
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerDiscountType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerDiscountType.LineDiscount
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerDiscountType.MultilineDiscount
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerDiscountType.TotalDiscount
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerDiscountType.None
dev_langs:
- CSharp
- C++
- VB
---

# CustomerDiscountType Enumeration

Represents the customer discount type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration CustomerDiscountType
'Usage
Dim instance As CustomerDiscountType
```

``` csharp
[DataContractAttribute]
public enum CustomerDiscountType
```

``` c++
[DataContractAttribute]
public enum class CustomerDiscountType
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
<td>Not a Customer discount.</td>
</tr>
<tr class="even">
<td></td>
<td>LineDiscount</td>
<td>A single line discount.</td>
</tr>
<tr class="odd">
<td></td>
<td>MultilineDiscount</td>
<td>A multiline discount.</td>
</tr>
<tr class="even">
<td></td>
<td>TotalDiscount</td>
<td>A total discount.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

