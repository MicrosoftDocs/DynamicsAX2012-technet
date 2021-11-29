---
title: DatabaseQueryParts.OrderBy Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: OrderBy Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseQueryParts.OrderBy
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.databasequeryparts.orderby(v=AX.60)
ms:contentKeyID: 65321830
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseQueryParts.OrderBy
dev_langs:
- CSharp
- C++
- VB
---

# OrderBy Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets ANSI SQL for order by clause (w/o ORDER BY keyword).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property OrderBy As String
    Get
    Set
'Usage
Dim instance As DatabaseQueryParts
Dim value As String

value = instance.OrderBy

instance.OrderBy = value
```

``` csharp
public string OrderBy { get; set; }
```

``` c++
public:
property String^ OrderBy {
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

