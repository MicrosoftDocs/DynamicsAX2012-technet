---
title: SqlQuery.QueryString Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: QueryString Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.SqlQuery.QueryString
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlquery.querystring(v=AX.60)
ms:contentKeyID: 65321734
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SqlQuery.QueryString
dev_langs:
- CSharp
- C++
- VB
---

# QueryString Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the query string.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Property QueryString As String
    Get
    Set
'Usage
Dim instance As SqlQuery
Dim value As String

value = instance.QueryString

instance.QueryString = value
```

``` csharp
public string QueryString { get; set; }
```

``` c++
public:
property String^ QueryString {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SqlQuery Class](sqlquery-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

