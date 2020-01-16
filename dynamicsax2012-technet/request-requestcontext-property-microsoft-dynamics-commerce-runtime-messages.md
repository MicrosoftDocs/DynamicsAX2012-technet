---
title: Request.RequestContext Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: RequestContext Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.Request.RequestContext
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.request.requestcontext(v=AX.60)
ms:contentKeyID: 65321607
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.Request.RequestContext
dev_langs:
- CSharp
- C++
- VB
---

# RequestContext Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property RequestContext As RequestContext
    Get
    Friend Set
'Usage
Dim instance As Request
Dim value As RequestContext

value = instance.RequestContext
```

``` csharp
public RequestContext RequestContext { get; internal set; }
```

``` c++
public:
property RequestContext^ RequestContext {
    RequestContext^ get ();
    internal: void set (RequestContext^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[Request Class](request-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

