---
title: SqlPagedQuery.OrderBy Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: OrderBy Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery.OrderBy
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlpagedquery.orderby(v=AX.60)
ms:contentKeyID: 65316782
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery.OrderBy
dev_langs:
- CSharp
- C++
- VB
---

# OrderBy Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the order by clause.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Property OrderBy As String
    Get
    Set
'Usage
Dim instance As SqlPagedQuery
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
The order by clause.  

## See Also

#### Reference

[SqlPagedQuery Class](sqlpagedquery-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

