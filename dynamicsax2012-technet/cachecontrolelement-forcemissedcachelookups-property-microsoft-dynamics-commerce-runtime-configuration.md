---
title: CacheControlElement.ForceMissedCacheLookups Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: ForceMissedCacheLookups Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.CacheControlElement.ForceMissedCacheLookups
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.cachecontrolelement.forcemissedcachelookups(v=AX.60)
ms:contentKeyID: 62209061
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.CacheControlElement.ForceMissedCacheLookups
dev_langs:
- CSharp
- C++
- VB
---

# ForceMissedCacheLookups Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether cache lookups should always fail or not.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders (in Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("forceCacheLookupMiss", DefaultValue := False)> _
Public ReadOnly Property ForceMissedCacheLookups As Boolean
    Get
'Usage
Dim instance As CacheControlElement
Dim value As Boolean

value = instance.ForceMissedCacheLookups
```

``` csharp
[ConfigurationPropertyAttribute("forceCacheLookupMiss", DefaultValue = false)]
public bool ForceMissedCacheLookups { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"forceCacheLookupMiss", DefaultValue = false)]
public:
virtual property bool ForceMissedCacheLookups {
    bool get () sealed;
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

#### Implements

[ICacheControlElement.ForceMissedCacheLookups](icachecontrolelement-forcemissedcachelookups-property-microsoft-dynamics-commerce-runtime-configuration.md)  

## See Also

#### Reference

[CacheControlElement Class](cachecontrolelement-class-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

