---
title: SqlQuery Constructor (String, Object ) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: SqlQuery Constructor (String, Object )
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SqlQuery.#ctor(System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.sqlquery.sqlquery(v=AX.60)
ms:contentKeyID: 65316908
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SqlQuery Constructor (String, Object )[AX 2012]

Initializes a new instance of the [SqlQuery](sqlquery-class-microsoft-dynamics-commerce-runtime-data.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    query As String, _
    ParamArray arguments As Object() _
)
'Usage
Dim query As String
Dim arguments As Object()

Dim instance As New SqlQuery(query, arguments)
```

``` csharp
public SqlQuery(
    string query,
    params Object[] arguments
)
```

``` c++
public:
SqlQuery(
    String^ query, 
    ... array<Object^>^ arguments
)
```

#### Parameters

  - query  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - arguments  
    Type: [System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))\[\]  

## See Also

#### Reference

[SqlQuery Class](sqlquery-class-microsoft-dynamics-commerce-runtime-data.md)

[SqlQuery Overload](sqlquery-constructor-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

