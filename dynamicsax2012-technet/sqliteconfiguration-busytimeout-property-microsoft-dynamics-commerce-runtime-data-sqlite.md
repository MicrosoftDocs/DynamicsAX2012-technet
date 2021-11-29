---
title: SqliteConfiguration.BusyTimeout Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite)
TOCTitle: BusyTimeout Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteConfiguration.BusyTimeout
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlite.sqliteconfiguration.busytimeout(v=AX.60)
ms:contentKeyID: 65322978
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteConfiguration.BusyTimeout
dev_langs:
- CSharp
- C++
- VB
---

# BusyTimeout Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the timeout in milliseconds for waiting on a statement execution that needs to acquire a lock on a database element.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Property BusyTimeout As Integer
    Get
    Set
'Usage
Dim instance As SqliteConfiguration
Dim value As Integer

value = instance.BusyTimeout

instance.BusyTimeout = value
```

``` csharp
public int BusyTimeout { get; set; }
```

``` c++
public:
property int BusyTimeout {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Busy timeout in milliseconds.  

## See Also

#### Reference

[SqliteConfiguration Class](sqliteconfiguration-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite Namespace](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)

