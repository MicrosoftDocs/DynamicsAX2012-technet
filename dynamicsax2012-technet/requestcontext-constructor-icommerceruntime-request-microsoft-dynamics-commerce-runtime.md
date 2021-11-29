---
title: RequestContext Constructor (ICommerceRuntime, Request) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: RequestContext Constructor (ICommerceRuntime, Request)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.RequestContext.#ctor(Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntime,Microsoft.Dynamics.Commerce.Runtime.Messages.Request)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.requestcontext.requestcontext(v=AX.60)
ms:contentKeyID: 65318405
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# RequestContext Constructor (ICommerceRuntime, Request)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    runtime As ICommerceRuntime, _
    request As Request _
)
'Usage
Dim runtime As ICommerceRuntime
Dim request As Request

Dim instance As New RequestContext(runtime, _
    request)
```

``` csharp
public RequestContext(
    ICommerceRuntime runtime,
    Request request
)
```

``` c++
public:
RequestContext(
    ICommerceRuntime^ runtime, 
    Request^ request
)
```

#### Parameters

  - runtime  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntime](icommerceruntime-interface-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  

## See Also

#### Reference

[RequestContext Class](requestcontext-class-microsoft-dynamics-commerce-runtime.md)

[RequestContext Overload](requestcontext-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

