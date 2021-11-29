---
title: SqliteConnectionStringBuilder.ConnectionString Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite)
TOCTitle: ConnectionString Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteConnectionStringBuilder.ConnectionString
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlite.sqliteconnectionstringbuilder.connectionstring(v=AX.60)
ms:contentKeyID: 65320512
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteConnectionStringBuilder.ConnectionString
dev_langs:
- CSharp
- C++
- VB
---

# ConnectionString Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the connection string.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Property ConnectionString As String
    Get
    Private Set
'Usage
Dim instance As SqliteConnectionStringBuilder
Dim value As String

value = instance.ConnectionString
```

``` csharp
public string ConnectionString { get; private set; }
```

``` c++
public:
property String^ ConnectionString {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SqliteConnectionStringBuilder Class](sqliteconnectionstringbuilder-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite Namespace](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)

