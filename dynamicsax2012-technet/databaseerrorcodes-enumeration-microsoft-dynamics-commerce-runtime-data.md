---
title: DatabaseErrorCodes Enumeration (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DatabaseErrorCodes Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseErrorCodes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.databaseerrorcodes(v=AX.60)
ms:contentKeyID: 65323149
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseErrorCodes
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseErrorCodes.AuthorizationError
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseErrorCodes.BaseErrorOffset
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseErrorCodes.CriticalError
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseErrorCodes.ItemOutOfStock
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseErrorCodes.Success
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseErrorCodes.VersionMismatchError
dev_langs:
- CSharp
- C++
- VB
---

# DatabaseErrorCodes Enumeration

Database error codes returned from stored procedures.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Enumeration DatabaseErrorCodes
'Usage
Dim instance As DatabaseErrorCodes
```

``` csharp
public enum DatabaseErrorCodes
```

``` c++
public enum class DatabaseErrorCodes
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
<td>Success</td>
<td>No errors occurred.</td>
</tr>
<tr class="even">
<td></td>
<td>BaseErrorOffset</td>
<td>Base error is offset by the standard error category range.
<p>Not an error code by itself.</p></td>
</tr>
<tr class="odd">
<td></td>
<td>CriticalError</td>
<td>Critical error.</td>
</tr>
<tr class="even">
<td></td>
<td>ItemOutOfStock</td>
<td>Item out of stock error.</td>
</tr>
<tr class="odd">
<td></td>
<td>AuthorizationError</td>
<td>Access denied.</td>
</tr>
<tr class="even">
<td></td>
<td>VersionMismatchError</td>
<td>Version mismatch.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

