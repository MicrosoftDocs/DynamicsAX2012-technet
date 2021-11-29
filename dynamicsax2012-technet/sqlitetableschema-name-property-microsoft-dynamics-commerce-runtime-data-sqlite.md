---
title: SqliteTableSchema.Name Property  (Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite)
TOCTitle: Name Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteTableSchema.Name
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlite.sqlitetableschema.name(v=AX.60)
ms:contentKeyID: 65320790
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite.SqliteTableSchema.Name
dev_langs:
- CSharp
- C++
- VB
---

# Name Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets table name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite (in Microsoft.Dynamics.Commerce.Runtime.DataAccess.Sqlite.dll)

## Syntax

``` vb
'Declaration
Public Property Name As String
    Get
    Private Set
'Usage
Dim instance As SqliteTableSchema
Dim value As String

value = instance.Name
```

``` csharp
public string Name { get; private set; }
```

``` c++
public:
property String^ Name {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SqliteTableSchema Class](sqlitetableschema-class-microsoft-dynamics-commerce-runtime-data-sqlite.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Sqlite Namespace](microsoft-dynamics-commerce-runtime-data-sqlite-namespace.md)

