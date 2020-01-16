---
title: RequestContext.RequestId Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: RequestId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.RequestContext.RequestId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.requestcontext.requestid(v=AX.60)
ms:contentKeyID: 49839923
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.RequestContext.RequestId
dev_langs:
- CSharp
- C++
- VB
---

# RequestId Property

Gets the unique identifier for this request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property RequestId As Guid
    Get
    Private Set
'Usage
Dim instance As RequestContext
Dim value As Guid

value = instance.RequestId
```

``` csharp
public Guid RequestId { get; private set; }
```

``` c++
public:
property Guid RequestId {
    Guid get ();
    private: void set (Guid value);
}
```

#### Property Value

Type: [System.Guid](https://technet.microsoft.com/library/cey1zx63\(v=ax.60\))  
Returns [Guid](https://technet.microsoft.com/library/cey1zx63\(v=ax.60\)).  

## See Also

#### Reference

[RequestContext Class](requestcontext-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

