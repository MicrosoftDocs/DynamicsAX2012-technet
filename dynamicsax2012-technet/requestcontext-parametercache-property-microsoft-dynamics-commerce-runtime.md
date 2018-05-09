---
title: RequestContext.ParameterCache Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: ParameterCache Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.RequestContext.ParameterCache
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.requestcontext.parametercache(v=AX.60)
ms:contentKeyID: 49842385
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.RequestContext.ParameterCache
dev_langs:
- CSharp
- C++
- VB
---

# ParameterCache Property

Gets a collection object used to cache data within the lifetime of a request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property ParameterCache As ParameterSet
    Get
    Private Set
'Usage
Dim instance As RequestContext
Dim value As ParameterSet

value = instance.ParameterCache
```

``` csharp
public ParameterSet ParameterCache { get; private set; }
```

``` c++
public:
property ParameterSet^ ParameterCache {
    ParameterSet^ get ();
    private: void set (ParameterSet^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.ParameterSet](parameterset-class-microsoft-dynamics-commerce-runtime.md)  
Returns [ParameterSet](parameterset-class-microsoft-dynamics-commerce-runtime.md).  

## See Also

#### Reference

[RequestContext Class](requestcontext-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

