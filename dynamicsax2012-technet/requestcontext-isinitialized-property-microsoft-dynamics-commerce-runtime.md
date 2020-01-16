---
title: RequestContext.IsInitialized Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: IsInitialized Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.RequestContext.IsInitialized
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.requestcontext.isinitialized(v=AX.60)
ms:contentKeyID: 65318812
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.RequestContext.IsInitialized
dev_langs:
- CSharp
- C++
- VB
---

# IsInitialized Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property IsInitialized As Boolean
    Get
    Private Set
'Usage
Dim instance As RequestContext
Dim value As Boolean

value = instance.IsInitialized
```

``` csharp
public bool IsInitialized { get; private set; }
```

``` c++
public:
property bool IsInitialized {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[RequestContext Class](requestcontext-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

