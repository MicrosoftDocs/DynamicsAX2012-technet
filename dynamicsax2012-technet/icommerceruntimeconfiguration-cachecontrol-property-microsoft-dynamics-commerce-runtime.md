---
title: ICommerceRuntimeConfiguration.CacheControl Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: CacheControl Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntimeConfiguration.CacheControl
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.icommerceruntimeconfiguration.cachecontrol(v=AX.60)
ms:contentKeyID: 65321203
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntimeConfiguration.CacheControl
dev_langs:
- CSharp
- C++
- VB
---

# CacheControl Property

Gets or sets the flags controlling caching behavior.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Property CacheControl As ICacheControlElement
    Get
    Set
'Usage
Dim instance As ICommerceRuntimeConfiguration
Dim value As ICacheControlElement

value = instance.CacheControl

instance.CacheControl = value
```

``` csharp
ICacheControlElement CacheControl { get; set; }
```

``` c++
property ICacheControlElement^ CacheControl {
    ICacheControlElement^ get ();
    void set (ICacheControlElement^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Configuration.ICacheControlElement](icachecontrolelement-interface-microsoft-dynamics-commerce-runtime-configuration.md)  
The cache control element of the configuration, which contains the flags controlling the caching behavior. See the config file for examples.  

## See Also

#### Reference

[ICommerceRuntimeConfiguration Interface](icommerceruntimeconfiguration-interface-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

