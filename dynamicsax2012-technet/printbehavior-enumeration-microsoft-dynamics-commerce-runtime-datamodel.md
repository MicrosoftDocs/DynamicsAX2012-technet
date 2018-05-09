---
title: PrintBehavior Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PrintBehavior Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.PrintBehavior
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.printbehavior(v=AX.60)
ms:contentKeyID: 62205562
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PrintBehavior
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PrintBehavior.Prompt
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PrintBehavior.Never
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PrintBehavior.Always
dev_langs:
- CSharp
- C++
- VB
---

# PrintBehavior Enumeration

Describes the alignment for text and variables.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration PrintBehavior
'Usage
Dim instance As PrintBehavior
```

``` csharp
public enum PrintBehavior
```

``` c++
public enum class PrintBehavior
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
<td>Always</td>
<td>The defult value indicating always print.</td>
</tr>
<tr class="even">
<td></td>
<td>Never</td>
<td>The value indicating never print.</td>
</tr>
<tr class="odd">
<td></td>
<td>Prompt</td>
<td>The value indicating prompt user.</td>
</tr>
</tbody>
</table>


## Remarks

Maps to the PRINTBEHAVIOUR column in ax.RETAILFORMLAYOUT table.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

