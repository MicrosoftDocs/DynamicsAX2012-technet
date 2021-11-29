---
title: CommerceRuntimeConfigurationManager.CachedConfiguration Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: CachedConfiguration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeConfigurationManager.CachedConfiguration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.commerceruntimeconfigurationmanager.cachedconfiguration(v=AX.60)
ms:contentKeyID: 65317690
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeConfigurationManager.CachedConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# CachedConfiguration Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the cached configuration object.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders (in Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll)

## Syntax

``` vb
'Declaration
Public Shared Property CachedConfiguration As CommerceRuntimeSection
    Get
    Private Set
'Usage
Dim value As CommerceRuntimeSection

value = CommerceRuntimeConfigurationManager.CachedConfiguration
```

``` csharp
public static CommerceRuntimeSection CachedConfiguration { get; private set; }
```

``` c++
public:
static property CommerceRuntimeSection^ CachedConfiguration {
    CommerceRuntimeSection^ get ();
    private: void set (CommerceRuntimeSection^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection](commerceruntimesection-class-microsoft-dynamics-commerce-runtime-configuration.md)  
Returns [CommerceRuntimeSection](commerceruntimesection-class-microsoft-dynamics-commerce-runtime-configuration.md).  

## See Also

#### Reference

[CommerceRuntimeConfigurationManager Class](commerceruntimeconfigurationmanager-class-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

