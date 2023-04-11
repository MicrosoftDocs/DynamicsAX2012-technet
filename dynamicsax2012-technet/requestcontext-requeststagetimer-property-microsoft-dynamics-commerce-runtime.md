---
title: RequestContext.RequestStageTimer Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: RequestStageTimer Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.RequestContext.RequestStageTimer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.requestcontext.requeststagetimer(v=AX.60)
ms:contentKeyID: 65322264
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.RequestContext.RequestStageTimer
dev_langs:
- CSharp
- C++
- VB
---

# RequestStageTimer Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property RequestStageTimer As Stopwatch
    Get
    Private Set
'Usage
Dim instance As RequestContext
Dim value As Stopwatch

value = instance.RequestStageTimer
```

``` csharp
public Stopwatch RequestStageTimer { get; private set; }
```

``` c++
public:
property Stopwatch^ RequestStageTimer {
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

