---
title: ICommerceRuntime.Execute(TResponse) Method (Request, RequestContext, IRequestHandler) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Execute(TResponse) Method (Request, RequestContext, IRequestHandler)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntime.Execute``1(Microsoft.Dynamics.Commerce.Runtime.Messages.Request,Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.Workflow.IRequestHandler)
ms:mtpsurl: https://technet.microsoft.com/library/Dn967927(v=AX.60)
ms:contentKeyID: 65319786
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Execute(TResponse) Method (Request, RequestContext, IRequestHandler)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes the specified request using the specified request context and handler.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function Execute(Of TResponse As Response) ( _
    request As Request, _
    context As RequestContext, _
    handler As IRequestHandler _
) As TResponse
'Usage
Dim instance As ICommerceRuntime
Dim request As Request
Dim context As RequestContext
Dim handler As IRequestHandler
Dim returnValue As TResponse

returnValue = instance.Execute(request, _
    context, handler)
```

``` csharp
TResponse Execute<TResponse>(
    Request request,
    RequestContext context,
    IRequestHandler handler
)
where TResponse : Response
```

``` c++
generic<typename TResponse>
where TResponse : Response
TResponse Execute(
    Request^ request, 
    RequestContext^ context, 
    IRequestHandler^ handler
)
```

#### Type Parameters

  - TResponse

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  

<!-- end list -->

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - handler  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Workflow.IRequestHandler](irequesthandler-interface-microsoft-dynamics-commerce-runtime-workflow.md)  

#### Return Value

Type: TResponse  
The response of the request from the request handler.  

## See Also

#### Reference

[ICommerceRuntime Interface](icommerceruntime-interface-microsoft-dynamics-commerce-runtime.md)

[Execute\<TResponse\> Overload](icommerceruntime-execute-tresponse-method-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

