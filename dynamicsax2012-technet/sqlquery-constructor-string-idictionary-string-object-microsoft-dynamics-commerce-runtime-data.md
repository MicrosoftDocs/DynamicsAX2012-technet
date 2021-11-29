---
title: SqlQuery Constructor (String, IDictionary(String, Object)) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: SqlQuery Constructor (String, IDictionary(String, Object))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SqlQuery.#ctor(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlquery.sqlquery(v=AX.60)
ms:contentKeyID: 65315486
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SqlQuery Constructor (String, IDictionary(String, Object))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [SqlQuery](sqlquery-class-microsoft-dynamics-commerce-runtime-data.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    query As String, _
    parameters As IDictionary(Of String, Object) _
)
'Usage
Dim query As String
Dim parameters As IDictionary(Of String, Object)

Dim instance As New SqlQuery(query, parameters)
```

``` csharp
public SqlQuery(
    string query,
    IDictionary<string, Object> parameters
)
```

``` c++
public:
SqlQuery(
    String^ query, 
    IDictionary<String^, Object^>^ parameters
)
```

#### Parameters

  - query  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - parameters  
    Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\>  

## See Also

#### Reference

[SqlQuery Class](sqlquery-class-microsoft-dynamics-commerce-runtime-data.md)

[SqlQuery Overload](sqlquery-constructor-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

