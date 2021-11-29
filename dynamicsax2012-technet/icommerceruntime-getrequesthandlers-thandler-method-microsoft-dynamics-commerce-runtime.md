---
title: ICommerceRuntime.GetRequestHandlers(THandler) Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetRequestHandlers(THandler) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntime.GetRequestHandlers``1(System.Type)
ms:mtpsurl: https://technet.microsoft.com/library/Dn988376(v=AX.60)
ms:contentKeyID: 65317930
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntime.GetRequestHandlers``1
dev_langs:
- CSharp
- C++
- VB
---

# GetRequestHandlers(THandler) Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets all request handlers of type that support the requestType request type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function GetRequestHandlers(Of THandler As IRequestHandler) ( _
    requestType As Type _
) As IEnumerable(Of THandler)
'Usage
Dim instance As ICommerceRuntime
Dim requestType As Type
Dim returnValue As IEnumerable(Of THandler)

returnValue = instance.GetRequestHandlers(requestType)
```

``` csharp
IEnumerable<THandler> GetRequestHandlers<THandler>(
    Type requestType
)
where THandler : IRequestHandler
```

``` c++
generic<typename THandler>
where THandler : IRequestHandler
IEnumerable<THandler>^ GetRequestHandlers(
    Type^ requestType
)
```

#### Type Parameters

  - THandler

#### Parameters

  - requestType  
    Type: [System.Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<THandler\>  
The matching request handlers.  

## See Also

#### Reference

[ICommerceRuntime Interface](icommerceruntime-interface-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

