---
title: SqlPagedQuery.Select Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Select Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery.Select
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlpagedquery.select(v=AX.60)
ms:contentKeyID: 65322738
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery.Select
dev_langs:
- CSharp
- C++
- VB
---

# Select Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the select clause.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Property Select As ColumnSet
    Get
    Set
'Usage
Dim instance As SqlPagedQuery
Dim value As ColumnSet

value = instance.Select

instance.Select = value
```

``` csharp
public ColumnSet Select { get; set; }
```

``` c++
public:
property ColumnSet^ Select {
    ColumnSet^ get ();
    void set (ColumnSet^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  
The select clause.  

## See Also

#### Reference

[SqlPagedQuery Class](sqlpagedquery-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

