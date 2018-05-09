---
title: SqliteConfiguration Constructor (IDictionary(String, String)) (Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite)
TOCTitle: SqliteConfiguration Constructor (IDictionary(String, String))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteConfiguration.#ctor(System.Collections.Generic.IDictionary{System.String,System.String})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.sqlite.sqliteconfiguration.sqliteconfiguration(v=AX.60)
ms:contentKeyID: 65321891
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SqliteConfiguration Constructor (IDictionary(String, String))

Initializes a new instance of the [SqliteConfiguration](sqliteconfiguration-class-microsoft-dynamics-commerce-runtime-data-sqlite.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    configurationValues As IDictionary(Of String, String) _
)
'Usage
Dim configurationValues As IDictionary(Of String, String)

Dim instance As New SqliteConfiguration(configurationValues)
```

``` csharp
public SqliteConfiguration(
    IDictionary<string, string> configurationValues
)
```

``` c++
public:
SqliteConfiguration(
    IDictionary<String^, String^>^ configurationValues
)
```

#### Parameters

  - configurationValues  
    Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/en-us/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)), [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[SqliteConfiguration Class](sqliteconfiguration-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)

[SqliteConfiguration Overload](sqliteconfiguration-constructor-microsoft-dynamics-commerce-runtime-data-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite Namespace](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)

