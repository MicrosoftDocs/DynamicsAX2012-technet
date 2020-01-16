---
title: ChangeAction Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChangeAction Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangeAction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.changeaction(v=AX.60)
ms:contentKeyID: 49846075
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangeAction
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangeAction.Delete
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangeAction.Insert
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangeAction.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangeAction.Update
dev_langs:
- CSharp
- C++
- VB
---

# ChangeAction Enumeration

Represents the change action.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration ChangeAction
'Usage
Dim instance As ChangeAction
```

``` csharp
public enum ChangeAction
```

``` c++
public enum class ChangeAction
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
<td>No change action specified.</td>
</tr>
<tr class="even">
<td></td>
<td>Insert</td>
<td>The row has been inserted.</td>
</tr>
<tr class="odd">
<td></td>
<td>Update</td>
<td>The row has been modified.</td>
</tr>
<tr class="even">
<td></td>
<td>Delete</td>
<td>The row has been deleted.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

