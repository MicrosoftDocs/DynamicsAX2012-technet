---
title: ICommerceRuntimeSection.CacheControl Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: CacheControl Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.ICommerceRuntimeSection.CacheControl
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.configuration.icommerceruntimesection.cachecontrol(v=AX.60)
ms:contentKeyID: 65322405
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.ICommerceRuntimeSection.CacheControl
dev_langs:
- CSharp
- C++
- VB
---

# CacheControl Property

Gets the cache control element.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property CacheControl As ICacheControlElement
    Get
'Usage
Dim instance As ICommerceRuntimeSection
Dim value As ICacheControlElement

value = instance.CacheControl
```

``` csharp
ICacheControlElement CacheControl { get; }
```

``` c++
property ICacheControlElement^ CacheControl {
    ICacheControlElement^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Configuration.ICacheControlElement](icachecontrolelement-interface-microsoft-dynamics-commerce-runtime-configuration.md)  
Returns [ICacheControlElement](icachecontrolelement-interface-microsoft-dynamics-commerce-runtime-configuration.md).  

## See Also

#### Reference

[ICommerceRuntimeSection Interface](icommerceruntimesection-interface-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

