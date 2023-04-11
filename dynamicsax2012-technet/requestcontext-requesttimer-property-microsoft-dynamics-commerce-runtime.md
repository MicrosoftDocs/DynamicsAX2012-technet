---
title: RequestContext.RequestTimer Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: RequestTimer Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.RequestContext.RequestTimer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.requestcontext.requesttimer(v=AX.60)
ms:contentKeyID: 65321328
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.RequestContext.RequestTimer
dev_langs:
- CSharp
- C++
- VB
---

# RequestTimer Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property RequestTimer As Stopwatch
    Get
    Private Set
'Usage
Dim instance As RequestContext
Dim value As Stopwatch

value = instance.RequestTimer
```

``` csharp
public Stopwatch RequestTimer { get; private set; }
```

``` c++
public:
property Stopwatch^ RequestTimer {
    Stopwatch^ get ();
    private: void set (Stopwatch^ value);
}
```

#### Property Value

Type: [System.Diagnostics.Stopwatch](https://technet.microsoft.com/library/ebf7z0sw\(v=ax.60\))  

## See Also

#### Reference

[RequestContext Class](requestcontext-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

