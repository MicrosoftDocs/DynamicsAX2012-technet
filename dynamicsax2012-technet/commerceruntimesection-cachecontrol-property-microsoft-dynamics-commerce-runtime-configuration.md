---
title: CommerceRuntimeSection.CacheControl Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: CacheControl Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection.CacheControl
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.commerceruntimesection.cachecontrol(v=AX.60)
ms:contentKeyID: 62203752
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection.CacheControl
dev_langs:
- CSharp
- C++
- VB
---

# CacheControl Property

Gets the cache control element.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders (in Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("cache")> _
Public ReadOnly Property CacheControl As ICacheControlElement
    Get
'Usage
Dim instance As CommerceRuntimeSection
Dim value As ICacheControlElement

value = instance.CacheControl
```

``` csharp
[ConfigurationPropertyAttribute("cache")]
public ICacheControlElement CacheControl { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"cache")]
public:
virtual property ICacheControlElement^ CacheControl {
    ICacheControlElement^ get () sealed;
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Configuration.ICacheControlElement](icachecontrolelement-interface-microsoft-dynamics-commerce-runtime-configuration.md)  
Returns [CacheControlElement](cachecontrolelement-class-microsoft-dynamics-commerce-runtime-configuration.md).  

#### Implements

[ICommerceRuntimeSection.CacheControl](icommerceruntimesection-cachecontrol-property-microsoft-dynamics-commerce-runtime-configuration.md)  

## See Also

#### Reference

[CommerceRuntimeSection Class](commerceruntimesection-class-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

