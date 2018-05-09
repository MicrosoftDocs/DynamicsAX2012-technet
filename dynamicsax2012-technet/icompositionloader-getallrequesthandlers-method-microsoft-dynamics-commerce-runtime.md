---
title: ICompositionLoader.GetAllRequestHandlers Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetAllRequestHandlers Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ICompositionLoader.GetAllRequestHandlers
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.icompositionloader.getallrequesthandlers(v=AX.60)
ms:contentKeyID: 65316060
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ICompositionLoader.GetAllRequestHandlers
dev_langs:
- CSharp
- C++
- VB
---

# GetAllRequestHandlers Method

Gets all request handlers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function GetAllRequestHandlers As IEnumerable(Of IRequestHandler)
'Usage
Dim instance As ICompositionLoader
Dim returnValue As IEnumerable(Of IRequestHandler)

returnValue = instance.GetAllRequestHandlers()
```

``` csharp
IEnumerable<IRequestHandler> GetAllRequestHandlers()
```

``` c++
IEnumerable<IRequestHandler^>^ GetAllRequestHandlers()
```

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[IRequestHandler](irequesthandler-interface-microsoft-dynamics-commerce-runtime-workflow.md)\>  
The matching request handlers.  

## See Also

#### Reference

[ICompositionLoader Interface](icompositionloader-interface-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

