---
title: TaxCode.RequestContext Property  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: RequestContext Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.RequestContext
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.taxcode.requestcontext(v=AX.60)
ms:contentKeyID: 49851974
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.TaxCode.RequestContext
dev_langs:
- CSharp
- C++
- VB
---

# RequestContext Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the context.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Protected Property RequestContext As RequestContext
    Get
    Private Set
'Usage
Dim value As RequestContext

value = Me.RequestContext
```

``` csharp
protected RequestContext RequestContext { get; private set; }
```

``` c++
protected:
property RequestContext^ RequestContext {
    RequestContext^ get ();
    private: void set (RequestContext^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  
Returns [RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md).  

## See Also

#### Reference

[TaxCode Class](taxcode-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

