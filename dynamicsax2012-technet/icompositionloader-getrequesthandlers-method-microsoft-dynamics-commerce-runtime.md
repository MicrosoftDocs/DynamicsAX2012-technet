---
title: ICompositionLoader.GetRequestHandlers Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetRequestHandlers Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ICompositionLoader.GetRequestHandlers(System.Type)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.icompositionloader.getrequesthandlers(v=AX.60)
ms:contentKeyID: 65319207
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ICompositionLoader.GetRequestHandlers
dev_langs:
- CSharp
- C++
- VB
---

# GetRequestHandlers Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets all request handlers that support the specified request type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function GetRequestHandlers ( _
    requestType As Type _
) As IEnumerable(Of IRequestHandler)
'Usage
Dim instance As ICompositionLoader
Dim requestType As Type
Dim returnValue As IEnumerable(Of IRequestHandler)

returnValue = instance.GetRequestHandlers(requestType)
```

``` csharp
IEnumerable<IRequestHandler> GetRequestHandlers(
    Type requestType
)
```

``` c++
IEnumerable<IRequestHandler^>^ GetRequestHandlers(
    Type^ requestType
)
```

#### Parameters

  - requestType  
    Type: [System.Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[IRequestHandler](irequesthandler-interface-microsoft-dynamics-commerce-runtime-workflow.md)\>  
The matching request handlers.  

## See Also

#### Reference

[ICompositionLoader Interface](icompositionloader-interface-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

