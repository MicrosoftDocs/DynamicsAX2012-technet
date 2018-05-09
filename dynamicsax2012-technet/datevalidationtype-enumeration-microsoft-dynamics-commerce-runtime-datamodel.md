---
title: DateValidationType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DateValidationType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.DateValidationType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.datevalidationtype(v=AX.60)
ms:contentKeyID: 62209839
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DateValidationType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DateValidationType.Advanced
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DateValidationType.Standard
dev_langs:
- CSharp
- C++
- VB
---

# DateValidationType Enumeration

Indicates whether the discount/promotion validation period is standard (i.e. date range) or advanced (i.e. periodic validity periods).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration DateValidationType
'Usage
Dim instance As DateValidationType
```

``` csharp
public enum DateValidationType
```

``` c++
public enum class DateValidationType
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
<td>Advanced</td>
<td>Advanced periodic date validation which includes days and times.</td>
</tr>
<tr class="even">
<td></td>
<td>Standard</td>
<td>Standard periodic date validation which only include to/from date.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to RetailDateValidationTypeBase enum in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

