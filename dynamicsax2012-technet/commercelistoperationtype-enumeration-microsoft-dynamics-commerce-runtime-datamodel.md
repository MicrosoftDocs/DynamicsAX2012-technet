---
title: CommerceListOperationType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CommerceListOperationType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListOperationType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.commercelistoperationtype(v=AX.60)
ms:contentKeyID: 62209093
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListOperationType.AddLine
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListOperationType.Unknown
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListOperationType.Update
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListOperationType.Create
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListOperationType.UpdateLine
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListOperationType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListOperationType.Delete
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceListOperationType.RemoveLine
dev_langs:
- CSharp
- C++
- VB
---

# CommerceListOperationType Enumeration

Represents the types of operations for a commerce list.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration CommerceListOperationType
'Usage
Dim instance As CommerceListOperationType
```

``` csharp
[DataContractAttribute]
public enum CommerceListOperationType
```

``` c++
[DataContractAttribute]
public enum class CommerceListOperationType
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
<td>Unknown</td>
<td>The unknown operation.</td>
</tr>
<tr class="even">
<td></td>
<td>Create</td>
<td>The create operation.</td>
</tr>
<tr class="odd">
<td></td>
<td>Update</td>
<td>The update operation.</td>
</tr>
<tr class="even">
<td></td>
<td>Delete</td>
<td>The delete operation.</td>
</tr>
<tr class="odd">
<td></td>
<td>AddLine</td>
<td>The add line operation.</td>
</tr>
<tr class="even">
<td></td>
<td>UpdateLine</td>
<td>The update line operation.</td>
</tr>
<tr class="odd">
<td></td>
<td>RemoveLine</td>
<td>The remove line operation.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

