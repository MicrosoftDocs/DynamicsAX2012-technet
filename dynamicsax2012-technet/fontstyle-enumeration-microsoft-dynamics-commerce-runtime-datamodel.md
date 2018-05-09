---
title: FontStyle Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FontStyle Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.FontStyle
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.fontstyle(v=AX.60)
ms:contentKeyID: 65322528
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.FontStyle
- Microsoft.Dynamics.Commerce.Runtime.DataModel.FontStyle.Bold
- Microsoft.Dynamics.Commerce.Runtime.DataModel.FontStyle.Italic
- Microsoft.Dynamics.Commerce.Runtime.DataModel.FontStyle.Regular
- Microsoft.Dynamics.Commerce.Runtime.DataModel.FontStyle.Strikeout
- Microsoft.Dynamics.Commerce.Runtime.DataModel.FontStyle.Underline
dev_langs:
- CSharp
- C++
- VB
---

# FontStyle Enumeration

Specifies style information applied to text.

This enumeration has a [FlagsAttribute](https://technet.microsoft.com/en-us/library/dk06fkbc\(v=ax.60\)) attribute that allows a bitwise combination of its member values.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<FlagsAttribute> _
Public Enumeration FontStyle
'Usage
Dim instance As FontStyle
```

``` csharp
[FlagsAttribute]
public enum FontStyle
```

``` c++
[FlagsAttribute]
public enum class FontStyle
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
<td>Regular</td>
<td>Normal text.</td>
</tr>
<tr class="even">
<td></td>
<td>Bold</td>
<td>Bold text.</td>
</tr>
<tr class="odd">
<td></td>
<td>Italic</td>
<td>Italic text.</td>
</tr>
<tr class="even">
<td></td>
<td>Underline</td>
<td>Underlined text.</td>
</tr>
<tr class="odd">
<td></td>
<td>Strikeout</td>
<td>Text with a line through the middle.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

