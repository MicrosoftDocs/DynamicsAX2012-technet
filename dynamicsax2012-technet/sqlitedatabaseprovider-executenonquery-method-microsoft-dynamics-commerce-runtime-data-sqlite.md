---
title: SqliteDatabaseProvider.ExecuteNonQuery Method  (Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite)
TOCTitle: ExecuteNonQuery Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteDatabaseProvider.ExecuteNonQuery(Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseConnection,Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQuery)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlite.sqlitedatabaseprovider.executenonquery(v=AX.60)
ms:contentKeyID: 65321942
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteDatabaseProvider.ExecuteNonQuery
dev_langs:
- CSharp
- C++
- VB
---

# ExecuteNonQuery Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes a command against the database that has no output.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Sub ExecuteNonQuery ( _
    connection As IDatabaseConnection, _
    query As IDatabaseQuery _
)
'Usage
Dim instance As SqliteDatabaseProvider
Dim connection As IDatabaseConnection
Dim query As IDatabaseQuery

instance.ExecuteNonQuery(connection, _
    query)
```

``` csharp
public void ExecuteNonQuery(
    IDatabaseConnection connection,
    IDatabaseQuery query
)
```

``` c++
public:
void ExecuteNonQuery(
    IDatabaseConnection^ connection, 
    IDatabaseQuery^ query
)
```

#### Parameters

  - connection  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseConnection](idatabaseconnection-interface-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - query  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQuery](idatabasequery-interface-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[SqliteDatabaseProvider Class](sqlitedatabaseprovider-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite Namespace](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)

