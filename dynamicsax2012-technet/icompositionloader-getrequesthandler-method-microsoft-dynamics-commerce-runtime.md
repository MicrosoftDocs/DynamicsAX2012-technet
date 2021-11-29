---
title: ICompositionLoader.GetRequestHandler Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetRequestHandler Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ICompositionLoader.GetRequestHandler(Microsoft.Dynamics.Commerce.Runtime.Messages.Request)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.icompositionloader.getrequesthandler(v=AX.60)
ms:contentKeyID: 65319680
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ICompositionLoader.GetRequestHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetRequestHandler Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the request handler based on the specified request type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function GetRequestHandler ( _
    request As Request _
) As IRequestHandler
'Usage
Dim instance As ICompositionLoader
Dim request As Request
Dim returnValue As IRequestHandler

returnValue = instance.GetRequestHandler(request)
```

``` csharp
IRequestHandler GetRequestHandler(
    Request request
)
```

``` c++
IRequestHandler^ GetRequestHandler(
    Request^ request
)
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Workflow.IRequestHandler](irequesthandler-interface-microsoft-dynamics-commerce-runtime-workflow.md)  
The matching request handler or NULL if no matching handler is found.  

## See Also

#### Reference

[ICompositionLoader Interface](icompositionloader-interface-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

