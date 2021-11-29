---
title: SqliteDatabaseProvider.GetTableSchemaInfo Method  (Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite)
TOCTitle: GetTableSchemaInfo Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteDatabaseProvider.GetTableSchemaInfo(Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseConnection,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlite.sqlitedatabaseprovider.gettableschemainfo(v=AX.60)
ms:contentKeyID: 65317370
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteDatabaseProvider.GetTableSchemaInfo
dev_langs:
- CSharp
- C++
- VB
---

# GetTableSchemaInfo Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets table schema info for a table in sqlite databases.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Function GetTableSchemaInfo ( _
    connection As IDatabaseConnection, _
    tableName As String _
) As SqliteTableSchema
'Usage
Dim instance As SqliteDatabaseProvider
Dim connection As IDatabaseConnection
Dim tableName As String
Dim returnValue As SqliteTableSchema

returnValue = instance.GetTableSchemaInfo(connection, _
    tableName)
```

``` csharp
public SqliteTableSchema GetTableSchemaInfo(
    IDatabaseConnection connection,
    string tableName
)
```

``` c++
public:
SqliteTableSchema^ GetTableSchemaInfo(
    IDatabaseConnection^ connection, 
    String^ tableName
)
```

#### Parameters

  - connection  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseConnection](idatabaseconnection-interface-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - tableName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteTableSchema](sqlitetableschema-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)  
SqliteTableSchema object.  

## See Also

#### Reference

[SqliteDatabaseProvider Class](sqlitedatabaseprovider-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite Namespace](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)

