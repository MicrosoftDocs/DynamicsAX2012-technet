---
title: SqliteDatabaseProvider.ExecuteScalar Method  (Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite)
TOCTitle: ExecuteScalar Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteDatabaseProvider.ExecuteScalar(Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseConnection,Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQuery,System.Type)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlite.sqlitedatabaseprovider.executescalar(v=AX.60)
ms:contentKeyID: 65320180
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteDatabaseProvider.ExecuteScalar
dev_langs:
- CSharp
- C++
- VB
---

# ExecuteScalar Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes a command against the database that returns a single result.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Function ExecuteScalar ( _
    connection As IDatabaseConnection, _
    query As IDatabaseQuery, _
    managedType As Type _
) As Object
'Usage
Dim instance As SqliteDatabaseProvider
Dim connection As IDatabaseConnection
Dim query As IDatabaseQuery
Dim managedType As Type
Dim returnValue As Object

returnValue = instance.ExecuteScalar(connection, _
    query, managedType)
```

``` csharp
public Object ExecuteScalar(
    IDatabaseConnection connection,
    IDatabaseQuery query,
    Type managedType
)
```

``` c++
public:
Object^ ExecuteScalar(
    IDatabaseConnection^ connection, 
    IDatabaseQuery^ query, 
    Type^ managedType
)
```

#### Parameters

  - connection  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseConnection](idatabaseconnection-interface-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - query  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQuery](idatabasequery-interface-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - managedType  
    Type: [System.Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\))  

#### Return Value

Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
The first column of the first row in the result set, or a null reference if the result set is empty.  

## See Also

#### Reference

[SqliteDatabaseProvider Class](sqlitedatabaseprovider-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite Namespace](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)

