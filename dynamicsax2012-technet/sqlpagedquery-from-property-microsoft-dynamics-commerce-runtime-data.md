---
title: SqlPagedQuery.From Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: From Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery.From
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlpagedquery.from(v=AX.60)
ms:contentKeyID: 65320419
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery.From
dev_langs:
- CSharp
- C++
- VB
---

# From Property

Gets or sets from clause.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Property From As String
    Get
    Set
'Usage
Dim instance As SqlPagedQuery
Dim value As String

value = instance.From

instance.From = value
```

``` csharp
public string From { get; set; }
```

``` c++
public:
property String^ From {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The from clause.  

## See Also

#### Reference

[SqlPagedQuery Class](sqlpagedquery-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

