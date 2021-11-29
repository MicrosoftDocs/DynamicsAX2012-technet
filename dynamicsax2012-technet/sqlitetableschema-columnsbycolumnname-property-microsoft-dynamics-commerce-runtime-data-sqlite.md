---
title: SqliteTableSchema.ColumnsByColumnName Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite)
TOCTitle: ColumnsByColumnName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteTableSchema.ColumnsByColumnName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlite.sqlitetableschema.columnsbycolumnname(v=AX.60)
ms:contentKeyID: 65321048
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteTableSchema.ColumnsByColumnName
dev_langs:
- CSharp
- C++
- VB
---

# ColumnsByColumnName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets column dictionary. Key is column name, value is table column.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Property ColumnsByColumnName As IDictionary(Of String, SqliteTableColumn)
    Get
    Private Set
'Usage
Dim instance As SqliteTableSchema
Dim value As IDictionary(Of String, SqliteTableColumn)

value = instance.ColumnsByColumnName
```

``` csharp
public IDictionary<string, SqliteTableColumn> ColumnsByColumnName { get; private set; }
```

``` c++
public:
property IDictionary<String^, SqliteTableColumn^>^ ColumnsByColumnName {
    IDictionary<String^, SqliteTableColumn^>^ get ();
    private: void set (IDictionary<String^, SqliteTableColumn^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [SqliteTableColumn](sqlitetablecolumn-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)\>  
Returns [IDictionary\<TKey, TValue\>](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\)).  

## See Also

#### Reference

[SqliteTableSchema Class](sqlitetableschema-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite Namespace](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)

