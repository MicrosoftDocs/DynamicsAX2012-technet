---
title: AnsiDatabaseQueryBuilder.Build Method  (Microsoft.Dynamics.Commerce.Runtime.Framework.Data.Interfaces)
TOCTitle: Build Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Framework.Data.Interfaces.AnsiDatabaseQueryBuilder.Build(Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseQueryParts)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.framework.data.interfaces.ansidatabasequerybuilder.build(v=AX.60)
ms:contentKeyID: 65319312
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Framework.Data.Interfaces.AnsiDatabaseQueryBuilder.Build
dev_langs:
- CSharp
- C++
- VB
---

# Build Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Build SQL query from parts.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Framework.Data.Interfaces](microsoft-dynamics-commerce-runtime-framework-data-interfaces-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function Build ( _
    parts As DatabaseQueryParts _
) As String
'Usage
Dim instance As AnsiDatabaseQueryBuilder
Dim parts As DatabaseQueryParts
Dim returnValue As String

returnValue = instance.Build(parts)
```

``` csharp
public string Build(
    DatabaseQueryParts parts
)
```

``` c++
public:
virtual String^ Build(
    DatabaseQueryParts^ parts
) sealed
```

#### Parameters

  - parts  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseQueryParts](databasequeryparts-class-microsoft-dynamics-commerce-runtime-data.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Final SQL statement.  

#### Implements

[IDatabaseQueryBuilder.Build(DatabaseQueryParts)](idatabasequerybuilder-build-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[AnsiDatabaseQueryBuilder Class](ansidatabasequerybuilder-class-microsoft-dynamics-commerce-runtime-framework-data-interfaces.md)

[Microsoft.Dynamics.Commerce.Runtime.Framework.Data.Interfaces Namespace](microsoft-dynamics-commerce-runtime-framework-data-interfaces-namespace.md)

