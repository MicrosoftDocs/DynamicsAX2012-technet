---
title: DataStoreType Enumeration (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DataStoreType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.datastoretype(v=AX.60)
ms:contentKeyID: 62209785
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreType.Database
- Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreType
- Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreType.OutputRequestCache
- Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreType.L1Cache
- Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreType.InputRequestCache
- Microsoft.Dynamics.Commerce.Runtime.Data.DataStoreType.L2Cache
dev_langs:
- CSharp
- C++
- VB
---

# DataStoreType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Types of data stores.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Enumeration DataStoreType
'Usage
Dim instance As DataStoreType
```

``` csharp
public enum DataStoreType
```

``` c++
public enum class DataStoreType
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
<td>Database</td>
<td>Identifies a database-type of data store.</td>
</tr>
<tr class="even">
<td></td>
<td>L1Cache</td>
<td>Identifies a level-1 type of cache, first level from the persistent data store.</td>
</tr>
<tr class="odd">
<td></td>
<td>L2Cache</td>
<td>Identifies a level-2 type of cache, second level from the persistent data store.</td>
</tr>
<tr class="even">
<td></td>
<td>InputRequestCache</td>
<td>Identifies a type of cache used to accelerate the processing of incoming requests.
<p>This would be typically a cache implemented/used at the higher level of CRT (workflow/API surface).</p></td>
</tr>
<tr class="odd">
<td></td>
<td>OutputRequestCache</td>
<td>Identifies a type of cache used to accelerate the response to client requests.
<p>This would be typically the IIS output request cache.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

