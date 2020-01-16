---
title: DatabaseQueryParts.Joins Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Joins Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseQueryParts.Joins
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.databasequeryparts.joins(v=AX.60)
ms:contentKeyID: 65320407
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseQueryParts.Joins
dev_langs:
- CSharp
- C++
- VB
---

# Joins Property

Gets or sets ANSI SQL for inner clauses.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property Joins As String
    Get
    Set
'Usage
Dim instance As DatabaseQueryParts
Dim value As String

value = instance.Joins

instance.Joins = value
```

``` csharp
public string Joins { get; set; }
```

``` c++
public:
property String^ Joins {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[DatabaseQueryParts Class](databasequeryparts-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

