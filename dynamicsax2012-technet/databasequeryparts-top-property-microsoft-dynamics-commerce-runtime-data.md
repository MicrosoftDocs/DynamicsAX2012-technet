---
title: DatabaseQueryParts.Top Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Top Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseQueryParts.Top
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.databasequeryparts.top(v=AX.60)
ms:contentKeyID: 65317722
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseQueryParts.Top
dev_langs:
- CSharp
- C++
- VB
---

# Top Property

Gets or sets amount of records to select.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property Top As Nullable(Of Integer)
    Get
    Set
'Usage
Dim instance As DatabaseQueryParts
Dim value As Nullable(Of Integer)

value = instance.Top

instance.Top = value
```

``` csharp
public Nullable<int> Top { get; set; }
```

``` c++
public:
property Nullable<int> Top {
    Nullable<int> get ();
    void set (Nullable<int> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[DatabaseQueryParts Class](databasequeryparts-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

