---
title: SqlPagedQuery.GetTotalNumberOfRecordsQuery Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetTotalNumberOfRecordsQuery Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery.GetTotalNumberOfRecordsQuery(Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQueryBuilder)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.sqlpagedquery.gettotalnumberofrecordsquery(v=AX.60)
ms:contentKeyID: 65319059
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SqlPagedQuery.GetTotalNumberOfRecordsQuery
dev_langs:
- CSharp
- C++
- VB
---

# GetTotalNumberOfRecordsQuery Method

Gets a query which computes the total number of records.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Function GetTotalNumberOfRecordsQuery ( _
    builder As IDatabaseQueryBuilder _
) As String
'Usage
Dim instance As SqlPagedQuery
Dim builder As IDatabaseQueryBuilder
Dim returnValue As String

returnValue = instance.GetTotalNumberOfRecordsQuery(builder)
```

``` csharp
public string GetTotalNumberOfRecordsQuery(
    IDatabaseQueryBuilder builder
)
```

``` c++
public:
String^ GetTotalNumberOfRecordsQuery(
    IDatabaseQueryBuilder^ builder
)
```

#### Parameters

  - builder  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQueryBuilder](idatabasequerybuilder-interface-microsoft-dynamics-commerce-runtime-data.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
A counting query.  

## See Also

#### Reference

[SqlPagedQuery Class](sqlpagedquery-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

