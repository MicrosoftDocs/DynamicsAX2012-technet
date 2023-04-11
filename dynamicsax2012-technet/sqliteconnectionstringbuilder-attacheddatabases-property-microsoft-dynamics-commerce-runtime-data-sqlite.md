---
title: SqliteConnectionStringBuilder.AttachedDatabases Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite)
TOCTitle: AttachedDatabases Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteConnectionStringBuilder.AttachedDatabases
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlite.sqliteconnectionstringbuilder.attacheddatabases(v=AX.60)
ms:contentKeyID: 65317265
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteConnectionStringBuilder.AttachedDatabases
dev_langs:
- CSharp
- C++
- VB
---

# AttachedDatabases Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of attached databases' path.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Property AttachedDatabases As IEnumerable(Of String)
    Get
    Private Set
'Usage
Dim instance As SqliteConnectionStringBuilder
Dim value As IEnumerable(Of String)

value = instance.AttachedDatabases
```

``` csharp
public IEnumerable<string> AttachedDatabases { get; private set; }
```

``` c++
public:
property IEnumerable<String^>^ AttachedDatabases {
    IEnumerable<String^>^ get ();
    private: void set (IEnumerable<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[SqliteConnectionStringBuilder Class](sqliteconnectionstringbuilder-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite Namespace](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)

