---
title: SqliteConfiguration.ConnectionPoolSize Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite)
TOCTitle: ConnectionPoolSize Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteConfiguration.ConnectionPoolSize
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlite.sqliteconfiguration.connectionpoolsize(v=AX.60)
ms:contentKeyID: 65316295
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteConfiguration.ConnectionPoolSize
dev_langs:
- CSharp
- C++
- VB
---

# ConnectionPoolSize Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the limit size of the connection pool.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Property ConnectionPoolSize As Integer
    Get
    Set
'Usage
Dim instance As SqliteConfiguration
Dim value As Integer

value = instance.ConnectionPoolSize

instance.ConnectionPoolSize = value
```

``` csharp
public int ConnectionPoolSize { get; set; }
```

``` c++
public:
property int ConnectionPoolSize {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
This limits the number of concurrent connections opened against the database.  

## Remarks

The connection pool allows connections to be reused.

## See Also

#### Reference

[SqliteConfiguration Class](sqliteconfiguration-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite Namespace](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)

