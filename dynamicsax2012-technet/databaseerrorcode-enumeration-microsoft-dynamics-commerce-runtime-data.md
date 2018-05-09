---
title: DatabaseErrorCode Enumeration (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DatabaseErrorCode Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseErrorCode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.databaseerrorcode(v=AX.60)
ms:contentKeyID: 65319394
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseErrorCode
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseErrorCode.ConnectionError
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseErrorCode.Deadlock
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseErrorCode.OperationNotValid
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseErrorCode.ParameterNotValid
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseErrorCode.Unknown
dev_langs:
- CSharp
- C++
- VB
---

# DatabaseErrorCode Enumeration

Represents the possible errors that can happen during database operation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Enumeration DatabaseErrorCode
'Usage
Dim instance As DatabaseErrorCode
```

``` csharp
public enum DatabaseErrorCode
```

``` c++
public enum class DatabaseErrorCode
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
<td>An unknown error.</td>
</tr>
<tr class="even">
<td></td>
<td>ParameterNotValid</td>
<td>One more more parameters for the command execution are not valid.</td>
</tr>
<tr class="odd">
<td></td>
<td>OperationNotValid</td>
<td>The operation being performed is currently not valid.</td>
</tr>
<tr class="even">
<td></td>
<td>ConnectionError</td>
<td>The target database connection failed.</td>
</tr>
<tr class="odd">
<td></td>
<td>Deadlock</td>
<td>The operation being performed could not be completed because the shared resource was in used by another connection.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

