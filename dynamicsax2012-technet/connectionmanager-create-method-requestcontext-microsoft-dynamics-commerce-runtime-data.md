---
title: ConnectionManager.Create Method (RequestContext) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Create Method (RequestContext)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ConnectionManager.Create(Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.connectionmanager.create(v=AX.60)
ms:contentKeyID: 65319950
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Create Method (RequestContext)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Shared Function Create ( _
    requestContext As RequestContext _
) As ConnectionManager
'Usage
Dim requestContext As RequestContext
Dim returnValue As ConnectionManager

returnValue = ConnectionManager.Create(requestContext)
```

``` csharp
public static ConnectionManager Create(
    RequestContext requestContext
)
```

``` c++
public:
static ConnectionManager^ Create(
    RequestContext^ requestContext
)
```

#### Parameters

  - requestContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.ConnectionManager](connectionmanager-class-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ConnectionManager Class](connectionmanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Create Overload](connectionmanager-create-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

