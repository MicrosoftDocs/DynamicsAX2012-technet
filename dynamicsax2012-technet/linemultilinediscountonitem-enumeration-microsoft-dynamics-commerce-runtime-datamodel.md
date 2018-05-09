---
title: LineMultilineDiscountOnItem Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineMultilineDiscountOnItem Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.LineMultilineDiscountOnItem
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.linemultilinediscountonitem(v=AX.60)
ms:contentKeyID: 49853989
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LineMultilineDiscountOnItem
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LineMultilineDiscountOnItem.Both
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LineMultilineDiscountOnItem.Line
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LineMultilineDiscountOnItem.Multiline
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LineMultilineDiscountOnItem.None
dev_langs:
- CSharp
- C++
- VB
---

# LineMultilineDiscountOnItem Enumeration

Represents a multiline discount on the item per line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration LineMultilineDiscountOnItem
'Usage
Dim instance As LineMultilineDiscountOnItem
```

``` csharp
[DataContractAttribute]
public enum LineMultilineDiscountOnItem
```

``` c++
[DataContractAttribute]
public enum class LineMultilineDiscountOnItem
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
<td>No discount applied on the line.</td>
</tr>
<tr class="even">
<td></td>
<td>Line</td>
<td>The discount is on a single line.</td>
</tr>
<tr class="odd">
<td></td>
<td>Multiline</td>
<td>The discount is on multiple lines.</td>
</tr>
<tr class="even">
<td></td>
<td>Both</td>
<td>The discount is on both line and multilines.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

