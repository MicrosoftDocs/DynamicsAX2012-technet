---
title: CommerceRuntimeConfiguration.CacheControl Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: CacheControl Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeConfiguration.CacheControl
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.commerceruntimeconfiguration.cachecontrol(v=AX.60)
ms:contentKeyID: 62211636
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeConfiguration.CacheControl
dev_langs:
- CSharp
- C++
- VB
---

# CacheControl Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the flags controlling caching behavior.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime (in Microsoft.Dynamics.Commerce.Runtime.dll)

## Syntax

``` vb
'Declaration
Public Property CacheControl As ICacheControlElement
    Get
    Set
'Usage
Dim instance As CommerceRuntimeConfiguration
Dim value As ICacheControlElement

value = instance.CacheControl

instance.CacheControl = value
```

``` csharp
public ICacheControlElement CacheControl { get; set; }
```

``` c++
public:
virtual property ICacheControlElement^ CacheControl {
    ICacheControlElement^ get () sealed;
    void set (ICacheControlElement^ value) sealed;
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Configuration.ICacheControlElement](icachecontrolelement-interface-microsoft-dynamics-commerce-runtime-configuration.md)  
The cache control element of the configuration, which contains the flags controlling the caching behavior. See the config file for examples.  

#### Implements

[ICommerceRuntimeConfiguration.CacheControl](icommerceruntimeconfiguration-cachecontrol-property-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[CommerceRuntimeConfiguration Class](commerceruntimeconfiguration-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

