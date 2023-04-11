---
title: SearchLocation Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SearchLocation Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchLocation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.searchlocation(v=AX.60)
ms:contentKeyID: 62209446
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchLocation.Remote
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchLocation.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchLocation.All
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchLocation
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchLocation.Local
dev_langs:
- CSharp
- C++
- VB
---

# SearchLocation Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

An enumeration used to indicate where to search for entity.

This enumeration has a [FlagsAttribute](https://technet.microsoft.com/library/dk06fkbc\(v=ax.60\)) attribute that allows a bitwise combination of its member values.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<FlagsAttribute> _
Public Enumeration SearchLocation
'Usage
Dim instance As SearchLocation
```

``` csharp
[FlagsAttribute]
public enum SearchLocation
```

``` c++
[FlagsAttribute]
public enum class SearchLocation
```

## Members

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
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
<td>Default value to enforce location to be set explicitly.
<p>If use search will fail. This value must be checked directly and not used with HasFlags method.</p></td>
</tr>
<tr class="even">
<td></td>
<td>Local</td>
<td>Search in local database.</td>
</tr>
<tr class="odd">
<td></td>
<td>Remote</td>
<td>Search via transaction service.</td>
</tr>
<tr class="even">
<td></td>
<td>All</td>
<td>Search in all available locations.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

