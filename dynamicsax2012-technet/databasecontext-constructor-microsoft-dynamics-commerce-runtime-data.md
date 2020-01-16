---
title: DatabaseContext Constructor  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DatabaseContext Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseContext.#ctor(Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.databasecontext.databasecontext(v=AX.60)
ms:contentKeyID: 65323026
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseContext.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# DatabaseContext Constructor

Initializes a new instance of the [DatabaseContext](databasecontext-class-microsoft-dynamics-commerce-runtime-data.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Protected Sub New ( _
    requestContext As RequestContext _
)
'Usage
Dim requestContext As RequestContext

Dim instance As New DatabaseContext(requestContext)
```

``` csharp
protected DatabaseContext(
    RequestContext requestContext
)
```

``` c++
protected:
DatabaseContext(
    RequestContext^ requestContext
)
```

#### Parameters

  - requestContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[DatabaseContext Class](databasecontext-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

