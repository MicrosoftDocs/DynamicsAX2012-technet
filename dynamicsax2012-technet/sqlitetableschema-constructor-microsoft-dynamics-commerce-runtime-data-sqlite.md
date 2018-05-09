---
title: SqliteTableSchema Constructor  (Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite)
TOCTitle: SqliteTableSchema Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteTableSchema.#ctor(System.String,System.Collections.Generic.IDictionary{System.String,Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteTableColumn})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.sqlite.sqlitetableschema.sqlitetableschema(v=AX.60)
ms:contentKeyID: 65321972
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteTableSchema.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# SqliteTableSchema Constructor

Initializes a new instance of the [SqliteTableSchema](sqlitetableschema-class-microsoft-dynamics-commerce-runtime-data-sqlite.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    tableName As String, _
    columnsByColumnName As IDictionary(Of String, SqliteTableColumn) _
)
'Usage
Dim tableName As String
Dim columnsByColumnName As IDictionary(Of String, SqliteTableColumn)

Dim instance As New SqliteTableSchema(tableName, _
    columnsByColumnName)
```

``` csharp
public SqliteTableSchema(
    string tableName,
    IDictionary<string, SqliteTableColumn> columnsByColumnName
)
```

``` c++
public:
SqliteTableSchema(
    String^ tableName, 
    IDictionary<String^, SqliteTableColumn^>^ columnsByColumnName
)
```

#### Parameters

  - tableName  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columnsByColumnName  
    Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/en-us/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)), [SqliteTableColumn](sqlitetablecolumn-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)\>  

## See Also

#### Reference

[SqliteTableSchema Class](sqlitetableschema-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite Namespace](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)

