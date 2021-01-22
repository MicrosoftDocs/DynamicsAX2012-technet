---
title: CommerceRuntimeSection.CacheControlElement Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: CacheControlElement Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection.CacheControlElement
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.commerceruntimesection.cachecontrolelement(v=AX.60)
ms:contentKeyID: 65316257
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection.CacheControlElement
dev_langs:
- CSharp
- C++
- VB
---

# CacheControlElement Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders (in Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("cache")> _
Public ReadOnly Property CacheControlElement As CacheControlElement
    Get
'Usage
Dim instance As CommerceRuntimeSection
Dim value As CacheControlElement

value = instance.CacheControlElement
```

``` csharp
[ConfigurationPropertyAttribute("cache")]
public CacheControlElement CacheControlElement { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"cache")]
public:
property CacheControlElement^ CacheControlElement {
    CacheControlElement^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Configuration.CacheControlElement](cachecontrolelement-class-microsoft-dynamics-commerce-runtime-configuration.md)  

## See Also

#### Reference

[CommerceRuntimeSection Class](commerceruntimesection-class-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

