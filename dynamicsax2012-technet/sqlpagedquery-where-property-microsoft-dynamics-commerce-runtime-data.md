---
title: SqlPagedQuery.Where Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Where Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery.Where
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.sqlpagedquery.where(v=AX.60)
ms:contentKeyID: 65319773
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery.Where
dev_langs:
- CSharp
- C++
- VB
---

# Where Property

Gets or sets the where clause.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Property Where As String
    Get
    Set
'Usage
Dim instance As SqlPagedQuery
Dim value As String

value = instance.Where

instance.Where = value
```

``` csharp
public string Where { get; set; }
```

``` c++
public:
property String^ Where {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The where.  

## See Also

#### Reference

[SqlPagedQuery Class](sqlpagedquery-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

