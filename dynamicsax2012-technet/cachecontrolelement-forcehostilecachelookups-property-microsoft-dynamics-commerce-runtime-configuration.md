---
title: CacheControlElement.ForceHostileCacheLookups Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: ForceHostileCacheLookups Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.CacheControlElement.ForceHostileCacheLookups
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.cachecontrolelement.forcehostilecachelookups(v=AX.60)
ms:contentKeyID: 62209048
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.CacheControlElement.ForceHostileCacheLookups
dev_langs:
- CSharp
- C++
- VB
---

# ForceHostileCacheLookups Property

Gets a value indicating whether cache lookups should return the opposite of reality or not.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders (in Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("forceCacheLookupHostile", DefaultValue := False)> _
Public ReadOnly Property ForceHostileCacheLookups As Boolean
    Get
'Usage
Dim instance As CacheControlElement
Dim value As Boolean

value = instance.ForceHostileCacheLookups
```

``` csharp
[ConfigurationPropertyAttribute("forceCacheLookupHostile", DefaultValue = false)]
public bool ForceHostileCacheLookups { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"forceCacheLookupHostile", DefaultValue = false)]
public:
virtual property bool ForceHostileCacheLookups {
    bool get () sealed;
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

#### Implements

[ICacheControlElement.ForceHostileCacheLookups](icachecontrolelement-forcehostilecachelookups-property-microsoft-dynamics-commerce-runtime-configuration.md)  

## See Also

#### Reference

[CacheControlElement Class](cachecontrolelement-class-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

