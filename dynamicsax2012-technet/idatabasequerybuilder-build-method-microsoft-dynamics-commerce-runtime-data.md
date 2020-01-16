---
title: IDatabaseQueryBuilder.Build Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Build Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQueryBuilder.Build(Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseQueryParts)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.idatabasequerybuilder.build(v=AX.60)
ms:contentKeyID: 65317007
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseQueryBuilder.Build
dev_langs:
- CSharp
- C++
- VB
---

# Build Method

Build SQL query from parts.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function Build ( _
    parts As DatabaseQueryParts _
) As String
'Usage
Dim instance As IDatabaseQueryBuilder
Dim parts As DatabaseQueryParts
Dim returnValue As String

returnValue = instance.Build(parts)
```

``` csharp
string Build(
    DatabaseQueryParts parts
)
```

``` c++
String^ Build(
    DatabaseQueryParts^ parts
)
```

#### Parameters

  - parts  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseQueryParts](databasequeryparts-class-microsoft-dynamics-commerce-runtime-data.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Final SQL statement.  

## See Also

#### Reference

[IDatabaseQueryBuilder Interface](idatabasequerybuilder-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

