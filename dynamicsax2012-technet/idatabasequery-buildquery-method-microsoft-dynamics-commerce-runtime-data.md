---
title: IDatabaseQuery.BuildQuery Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: BuildQuery Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQuery.BuildQuery(Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQueryBuilder)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.idatabasequery.buildquery(v=AX.60)
ms:contentKeyID: 65319385
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQuery.BuildQuery
dev_langs:
- CSharp
- C++
- VB
---

# BuildQuery Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Builds the query string for this command.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function BuildQuery ( _
    queryBuilder As IDatabaseQueryBuilder _
) As String
'Usage
Dim instance As IDatabaseQuery
Dim queryBuilder As IDatabaseQueryBuilder
Dim returnValue As String

returnValue = instance.BuildQuery(queryBuilder)
```

``` csharp
string BuildQuery(
    IDatabaseQueryBuilder queryBuilder
)
```

``` c++
String^ BuildQuery(
    IDatabaseQueryBuilder^ queryBuilder
)
```

#### Parameters

  - queryBuilder  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQueryBuilder](idatabasequerybuilder-interface-microsoft-dynamics-commerce-runtime-data.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
A string representing the command to be executed against the database.  

## See Also

#### Reference

[IDatabaseQuery Interface](idatabasequery-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

