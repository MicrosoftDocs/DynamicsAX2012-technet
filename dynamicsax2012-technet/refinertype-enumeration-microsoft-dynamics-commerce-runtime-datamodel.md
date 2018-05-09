---
title: RefinerType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RefinerType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.RefinerType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.refinertype(v=AX.60)
ms:contentKeyID: 65321440
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RefinerType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RefinerType.MultiSelect
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RefinerType.SingleSelect
dev_langs:
- CSharp
- C++
- VB
---

# RefinerType Enumeration

Represents the functionality that can be performed on a refiner.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration RefinerType
'Usage
Dim instance As RefinerType
```

``` csharp
[DataContractAttribute]
public enum RefinerType
```

``` c++
[DataContractAttribute]
public enum class RefinerType
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
<td>SingleSelect</td>
<td>Represents a refiner where only one refiner value can be used at a time for refinement.</td>
</tr>
<tr class="even">
<td></td>
<td>MultiSelect</td>
<td>Represents a refiner where multiple refiner values can be used at a time for refinement.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

