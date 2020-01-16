---
title: SqliteTableColumn.ManagedType Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite)
TOCTitle: ManagedType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteTableColumn.ManagedType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlite.sqlitetablecolumn.managedtype(v=AX.60)
ms:contentKeyID: 65319151
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteTableColumn.ManagedType
dev_langs:
- CSharp
- C++
- VB
---

# ManagedType Property

Gets managed type for this column.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Property ManagedType As Type
    Get
    Private Set
'Usage
Dim instance As SqliteTableColumn
Dim value As Type

value = instance.ManagedType
```

``` csharp
public Type ManagedType { get; private set; }
```

``` c++
public:
property Type^ ManagedType {
    Type^ get ();
    private: void set (Type^ value);
}
```

#### Property Value

Type: [System.Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\))  
Returns [Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\)).  

## See Also

#### Reference

[SqliteTableColumn Class](sqlitetablecolumn-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite Namespace](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)

