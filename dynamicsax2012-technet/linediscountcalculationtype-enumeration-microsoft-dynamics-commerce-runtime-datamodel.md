---
title: LineDiscountCalculationType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineDiscountCalculationType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.LineDiscountCalculationType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.linediscountcalculationtype(v=AX.60)
ms:contentKeyID: 49832999
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LineDiscountCalculationType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LineDiscountCalculationType.Line
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LineDiscountCalculationType.LineMultiplyMultiline
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LineDiscountCalculationType.LinePlusMultiline
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LineDiscountCalculationType.MaxLineMultiline
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LineDiscountCalculationType.MinLineMultiline
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LineDiscountCalculationType.Multiline
dev_langs:
- CSharp
- C++
- VB
---

# LineDiscountCalculationType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents how trade agreement discount conflicts will be resolved when totalling.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration LineDiscountCalculationType
'Usage
Dim instance As LineDiscountCalculationType
```

``` csharp
public enum LineDiscountCalculationType
```

``` c++
public enum class LineDiscountCalculationType
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
<td>Line</td>
<td>Discount always equal to the line discount.</td>
</tr>
<tr class="even">
<td></td>
<td>Multiline</td>
<td>Discount always equal to the multiline discount.</td>
</tr>
<tr class="odd">
<td></td>
<td>MaxLineMultiline</td>
<td>Discount is always the max discount of line and multiline discount.</td>
</tr>
<tr class="even">
<td></td>
<td>MinLineMultiline</td>
<td>Discount is always the min discount of line and multiline discount.</td>
</tr>
<tr class="odd">
<td></td>
<td>LinePlusMultiline</td>
<td>Discount is the sum of the line and multiline discount.</td>
</tr>
<tr class="even">
<td></td>
<td>LineMultiplyMultiline</td>
<td>The same as LinePlusMultiline.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to the Account Receivable Parameters (under Price Section) in AX.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

