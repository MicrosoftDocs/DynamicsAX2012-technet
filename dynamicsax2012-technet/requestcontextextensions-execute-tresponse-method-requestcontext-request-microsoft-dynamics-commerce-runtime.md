---
title: RequestContextExtensions.Execute(TResponse) Method (RequestContext, Request) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Execute(TResponse) Method (RequestContext, Request)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.RequestContextExtensions.Execute``1(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.Messages.Request)
ms:mtpsurl: https://technet.microsoft.com/library/Dn966458(v=AX.60)
ms:contentKeyID: 65316406
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Execute(TResponse) Method (RequestContext, Request)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes the specified request using the specified request context.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function Execute(Of TResponse As Response) ( _
    requestContext As RequestContext, _
    request As Request _
) As TResponse
'Usage
Dim requestContext As RequestContext
Dim request As Request
Dim returnValue As TResponse

returnValue = requestContext.Execute(request)
```

``` csharp
public static TResponse Execute<TResponse>(
    this RequestContext requestContext,
    Request request
)
where TResponse : Response
```

``` c++
[ExtensionAttribute]
public:
generic<typename TResponse>
where TResponse : Response
static TResponse Execute(
    RequestContext^ requestContext, 
    Request^ request
)
```

#### Type Parameters

  - TResponse

#### Parameters

  - requestContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: TResponse  
The response of the request from the request handler.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[RequestContextExtensions Class](requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md)

[Execute\<TResponse\> Overload](requestcontextextensions-execute-tresponse-method-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

