---
title: AnsiDatabaseQueryBuilder.BuildWherePart Method  (Microsoft.Dynamics.Commerce.Runtime.Framework.Data.Interfaces)
TOCTitle: BuildWherePart Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Framework.Data.Interfaces.AnsiDatabaseQueryBuilder.BuildWherePart(System.Text.StringBuilder,Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseQueryParts)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.framework.data.interfaces.ansidatabasequerybuilder.buildwherepart(v=AX.60)
ms:contentKeyID: 65323164
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Framework.Data.Interfaces.AnsiDatabaseQueryBuilder.BuildWherePart
dev_langs:
- CSharp
- C++
- VB
---

# BuildWherePart Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Adds WHERE clause to a string builder.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Framework.Data.Interfaces](microsoft-dynamics-commerce-runtime-framework-data-interfaces-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Protected Sub BuildWherePart ( _
    builder As StringBuilder, _
    parts As DatabaseQueryParts _
)
'Usage
Dim builder As StringBuilder
Dim parts As DatabaseQueryParts

Me.BuildWherePart(builder, parts)
```

``` csharp
protected void BuildWherePart(
    StringBuilder builder,
    DatabaseQueryParts parts
)
```

``` c++
protected:
void BuildWherePart(
    StringBuilder^ builder, 
    DatabaseQueryParts^ parts
)
```

#### Parameters

  - builder  
    Type: [System.Text.StringBuilder](https://technet.microsoft.com/library/y9sxk6fy\(v=ax.60\))  

<!-- end list -->

  - parts  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseQueryParts](databasequeryparts-class-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[AnsiDatabaseQueryBuilder Class](ansidatabasequerybuilder-class-microsoft-dynamics-commerce-runtime-framework-data-interfaces.md)

[Microsoft.Dynamics.Commerce.Runtime.Framework.Data.Interfaces Namespace](microsoft-dynamics-commerce-runtime-framework-data-interfaces-namespace.md)

