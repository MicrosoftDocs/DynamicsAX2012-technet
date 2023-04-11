---
title: CommerceRuntime.Execute(TResponse) Method (Request, RequestContext) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Execute(TResponse) Method (Request, RequestContext)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime.Execute``1(Microsoft.Dynamics.Commerce.Runtime.Messages.Request,Microsoft.Dynamics.Commerce.Runtime.RequestContext)
ms:mtpsurl: https://technet.microsoft.com/library/Dn990084(v=AX.60)
ms:contentKeyID: 65320774
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Execute(TResponse) Method (Request, RequestContext)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime (in Microsoft.Dynamics.Commerce.Runtime.dll)

## Syntax

``` vb
'Declaration
Public Function Execute(Of TResponse As Response) ( _
    request As Request, _
    context As RequestContext _
) As TResponse
'Usage
Dim instance As CommerceRuntime
Dim request As Request
Dim context As RequestContext
Dim returnValue As TResponse

returnValue = instance.Execute(request, _
    context)
```

``` csharp
public TResponse Execute<TResponse>(
    Request request,
    RequestContext context
)
where TResponse : Response
```

``` c++
public:
generic<typename TResponse>
where TResponse : Response
virtual TResponse Execute(
    Request^ request, 
    RequestContext^ context
) sealed
```

#### Type Parameters

  - TResponse

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  

<!-- end list -->

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: TResponse  

## See Also

#### Reference

[CommerceRuntime Class](commerceruntime-class-microsoft-dynamics-commerce-runtime.md)

[Execute\<TResponse\> Overload](commerceruntime-execute-tresponse-method-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

