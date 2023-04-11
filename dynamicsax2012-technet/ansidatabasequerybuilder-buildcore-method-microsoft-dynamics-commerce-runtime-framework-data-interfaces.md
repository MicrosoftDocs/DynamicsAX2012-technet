---
title: AnsiDatabaseQueryBuilder.BuildCore Method  (Microsoft.Dynamics.Commerce.Runtime.Framework.Data.Interfaces)
TOCTitle: BuildCore Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Framework.Data.Interfaces.AnsiDatabaseQueryBuilder.BuildCore(System.Text.StringBuilder,Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseQueryParts,System.Globalization.CultureInfo)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.framework.data.interfaces.ansidatabasequerybuilder.buildcore(v=AX.60)
ms:contentKeyID: 65319543
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Framework.Data.Interfaces.AnsiDatabaseQueryBuilder.BuildCore
dev_langs:
- CSharp
- C++
- VB
---

# BuildCore Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Writes parts to a builder based on a specified culture.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Framework.Data.Interfaces](microsoft-dynamics-commerce-runtime-framework-data-interfaces-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Protected MustOverride Sub BuildCore ( _
    builder As StringBuilder, _
    parts As DatabaseQueryParts, _
    builderCulture As CultureInfo _
)
'Usage
Dim builder As StringBuilder
Dim parts As DatabaseQueryParts
Dim builderCulture As CultureInfo

Me.BuildCore(builder, parts, builderCulture)
```

``` csharp
protected abstract void BuildCore(
    StringBuilder builder,
    DatabaseQueryParts parts,
    CultureInfo builderCulture
)
```

``` c++
protected:
virtual void BuildCore(
    StringBuilder^ builder, 
    DatabaseQueryParts^ parts, 
    CultureInfo^ builderCulture
) abstract
```

#### Parameters

  - builder  
    Type: [System.Text.StringBuilder](https://technet.microsoft.com/library/y9sxk6fy\(v=ax.60\))  

<!-- end list -->

  - parts  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseQueryParts](databasequeryparts-class-microsoft-dynamics-commerce-runtime-data.md)  

<!-- end list -->

  - builderCulture  
    Type: [System.Globalization.CultureInfo](https://technet.microsoft.com/library/kx54z3k7\(v=ax.60\))  

## See Also

#### Reference

[AnsiDatabaseQueryBuilder Class](ansidatabasequerybuilder-class-microsoft-dynamics-commerce-runtime-framework-data-interfaces.md)

[Microsoft.Dynamics.Commerce.Runtime.Framework.Data.Interfaces Namespace](microsoft-dynamics-commerce-runtime-framework-data-interfaces-namespace.md)

