---
title: SqliteConfiguration.StatementCachingPoolSize Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite)
TOCTitle: StatementCachingPoolSize Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteConfiguration.StatementCachingPoolSize
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlite.sqliteconfiguration.statementcachingpoolsize(v=AX.60)
ms:contentKeyID: 65318446
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteConfiguration.StatementCachingPoolSize
dev_langs:
- CSharp
- C++
- VB
---

# StatementCachingPoolSize Property

Gets or sets the limit size, per database connection, of the statement caching pool.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Property StatementCachingPoolSize As Integer
    Get
    Set
'Usage
Dim instance As SqliteConfiguration
Dim value As Integer

value = instance.StatementCachingPoolSize

instance.StatementCachingPoolSize = value
```

``` csharp
public int StatementCachingPoolSize { get; set; }
```

``` c++
public:
property int StatementCachingPoolSize {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
This limits the size of the statement caching pool.  

## Remarks

The statement cache allows statements to be reused, reducing the statement compilation overhead during runtime.

## See Also

#### Reference

[SqliteConfiguration Class](sqliteconfiguration-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite Namespace](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)

