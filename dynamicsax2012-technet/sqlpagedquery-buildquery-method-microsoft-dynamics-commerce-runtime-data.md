---
title: SqlPagedQuery.BuildQuery Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: BuildQuery Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery.BuildQuery(Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQueryBuilder)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlpagedquery.buildquery(v=AX.60)
ms:contentKeyID: 65315582
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery.BuildQuery
dev_langs:
- CSharp
- C++
- VB
---

# BuildQuery Method

Builds a query using the specified builder.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Overrides Function BuildQuery ( _
    queryBuilder As IDatabaseQueryBuilder _
) As String
'Usage
Dim instance As SqlPagedQuery
Dim queryBuilder As IDatabaseQueryBuilder
Dim returnValue As String

returnValue = instance.BuildQuery(queryBuilder)
```

``` csharp
public override string BuildQuery(
    IDatabaseQueryBuilder queryBuilder
)
```

``` c++
public:
virtual String^ BuildQuery(
    IDatabaseQueryBuilder^ queryBuilder
) override
```

#### Parameters

  - queryBuilder  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQueryBuilder](idatabasequerybuilder-interface-microsoft-dynamics-commerce-runtime-data.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The query.  

#### Implements

[IDatabaseQuery.BuildQuery(IDatabaseQueryBuilder)](idatabasequery-buildquery-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[SqlPagedQuery Class](sqlpagedquery-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

