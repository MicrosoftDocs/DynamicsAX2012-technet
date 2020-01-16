---
title: SqlQuery.BuildQuery Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: BuildQuery Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SqlQuery.BuildQuery(Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQueryBuilder)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlquery.buildquery(v=AX.60)
ms:contentKeyID: 65322394
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SqlQuery.BuildQuery
dev_langs:
- CSharp
- C++
- VB
---

# BuildQuery Method

Builds the query to be executed against the database.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function BuildQuery ( _
    queryBuilder As IDatabaseQueryBuilder _
) As String
'Usage
Dim instance As SqlQuery
Dim queryBuilder As IDatabaseQueryBuilder
Dim returnValue As String

returnValue = instance.BuildQuery(queryBuilder)
```

``` csharp
public virtual string BuildQuery(
    IDatabaseQueryBuilder queryBuilder
)
```

``` c++
public:
virtual String^ BuildQuery(
    IDatabaseQueryBuilder^ queryBuilder
)
```

#### Parameters

  - queryBuilder  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQueryBuilder](idatabasequerybuilder-interface-microsoft-dynamics-commerce-runtime-data.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The query to be executed against the database.  

#### Implements

[IDatabaseQuery.BuildQuery(IDatabaseQueryBuilder)](idatabasequery-buildquery-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[SqlQuery Class](sqlquery-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

