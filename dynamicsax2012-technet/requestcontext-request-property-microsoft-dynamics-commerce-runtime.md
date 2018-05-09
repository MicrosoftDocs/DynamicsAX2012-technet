---
title: RequestContext.Request Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Request Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.RequestContext.Request
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.requestcontext.request(v=AX.60)
ms:contentKeyID: 49825749
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.RequestContext.Request
dev_langs:
- CSharp
- C++
- VB
---

# Request Property

Gets the request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property Request As Request
    Get
    Protected Set
'Usage
Dim instance As RequestContext
Dim value As Request

value = instance.Request

instance.Request = value
```

``` csharp
public Request Request { get; protected set; }
```

``` c++
public:
property Request^ Request {
    Request^ get ();
    protected: void set (Request^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
Returns [Request](request-class-microsoft-dynamics-commerce-runtime-messages.md).  

## See Also

#### Reference

[RequestContext Class](requestcontext-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

