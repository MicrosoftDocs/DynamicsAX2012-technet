---
title: AnsiDatabaseQueryBuilder.BuildOrderByPart Method  (Microsoft.Dynamics.Commerce.Runtime.Framework.Data.Interfaces)
TOCTitle: BuildOrderByPart Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Framework.Data.Interfaces.AnsiDatabaseQueryBuilder.BuildOrderByPart(System.Text.StringBuilder,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.framework.data.interfaces.ansidatabasequerybuilder.buildorderbypart(v=AX.60)
ms:contentKeyID: 65323010
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Framework.Data.Interfaces.AnsiDatabaseQueryBuilder.BuildOrderByPart
dev_langs:
- CSharp
- C++
- VB
---

# BuildOrderByPart Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Adds FROM and JOIN's clauses to a string builder.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Framework.Data.Interfaces](microsoft-dynamics-commerce-runtime-framework-data-interfaces-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Protected Sub BuildOrderByPart ( _
    builder As StringBuilder, _
    orderBy As String _
)
'Usage
Dim builder As StringBuilder
Dim orderBy As String

Me.BuildOrderByPart(builder, orderBy)
```

``` csharp
protected void BuildOrderByPart(
    StringBuilder builder,
    string orderBy
)
```

``` c++
protected:
void BuildOrderByPart(
    StringBuilder^ builder, 
    String^ orderBy
)
```

#### Parameters

  - builder  
    Type: [System.Text.StringBuilder](https://technet.microsoft.com/library/y9sxk6fy\(v=ax.60\))  

<!-- end list -->

  - orderBy  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[AnsiDatabaseQueryBuilder Class](ansidatabasequerybuilder-class-microsoft-dynamics-commerce-runtime-framework-data-interfaces.md)

[Microsoft.Dynamics.Commerce.Runtime.Framework.Data.Interfaces Namespace](microsoft-dynamics-commerce-runtime-framework-data-interfaces-namespace.md)

