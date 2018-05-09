---
title: RequestContext.Response Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Response Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.RequestContext.Response
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.requestcontext.response(v=AX.60)
ms:contentKeyID: 49832801
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.RequestContext.Response
dev_langs:
- CSharp
- C++
- VB
---

# Response Property

Gets or sets the response for the request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property Response As Response
    Get
    Set
'Usage
Dim instance As RequestContext
Dim value As Response

value = instance.Response

instance.Response = value
```

``` csharp
public Response Response { get; set; }
```

``` c++
public:
property Response^ Response {
    Response^ get ();
    void set (Response^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)  
Returns [Response](response-class-microsoft-dynamics-commerce-runtime-messages.md).  

## See Also

#### Reference

[RequestContext Class](requestcontext-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

