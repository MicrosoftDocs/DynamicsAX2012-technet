---
title: SqliteConnectionStringBuilder Constructor (String, IEnumerable(String)) (Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite)
TOCTitle: SqliteConnectionStringBuilder Constructor (String, IEnumerable(String))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteConnectionStringBuilder.#ctor(System.String,System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.sqlite.sqliteconnectionstringbuilder.sqliteconnectionstringbuilder(v=AX.60)
ms:contentKeyID: 65321991
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SqliteConnectionStringBuilder Constructor (String, IEnumerable(String))

Initializes a new instance of the [SqliteConnectionStringBuilder](sqliteconnectionstringbuilder-class-microsoft-dynamics-commerce-runtime-data-sqlite.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    mainDatabase As String, _
    attachDatabases As IEnumerable(Of String) _
)
'Usage
Dim mainDatabase As String
Dim attachDatabases As IEnumerable(Of String)

Dim instance As New SqliteConnectionStringBuilder(mainDatabase, _
    attachDatabases)
```

``` csharp
public SqliteConnectionStringBuilder(
    string mainDatabase,
    IEnumerable<string> attachDatabases
)
```

``` c++
public:
SqliteConnectionStringBuilder(
    String^ mainDatabase, 
    IEnumerable<String^>^ attachDatabases
)
```

#### Parameters

  - mainDatabase  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - attachDatabases  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[SqliteConnectionStringBuilder Class](sqliteconnectionstringbuilder-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)

[SqliteConnectionStringBuilder Overload](sqliteconnectionstringbuilder-constructor-microsoft-dynamics-commerce-runtime-data-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite Namespace](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)

