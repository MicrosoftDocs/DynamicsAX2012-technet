---
title: RequestContext.Runtime Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Runtime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.RequestContext.Runtime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.requestcontext.runtime(v=AX.60)
ms:contentKeyID: 49825259
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.RequestContext.Runtime
dev_langs:
- CSharp
- C++
- VB
---

# Runtime Property

Gets the instance of the runtime.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property Runtime As ICommerceRuntime
    Get
    Private Set
'Usage
Dim instance As RequestContext
Dim value As ICommerceRuntime

value = instance.Runtime
```

``` csharp
public ICommerceRuntime Runtime { get; private set; }
```

``` c++
public:
property ICommerceRuntime^ Runtime {
    ICommerceRuntime^ get ();
    private: void set (ICommerceRuntime^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntime](icommerceruntime-interface-microsoft-dynamics-commerce-runtime.md)  
Returns [CommerceRuntime](commerceruntime-class-microsoft-dynamics-commerce-runtime.md).  

## See Also

#### Reference

[RequestContext Class](requestcontext-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

