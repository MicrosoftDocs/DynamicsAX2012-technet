---
title: CacheControlElement.ForceCacheLookupHits Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: ForceCacheLookupHits Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.CacheControlElement.ForceCacheLookupHits
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.cachecontrolelement.forcecachelookuphits(v=AX.60)
ms:contentKeyID: 62202458
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.CacheControlElement.ForceCacheLookupHits
dev_langs:
- CSharp
- C++
- VB
---

# ForceCacheLookupHits Property

Gets a value indicating whether cache lookups should always return positive or not.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders (in Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("forceCacheLookupHit", DefaultValue := False)> _
Public ReadOnly Property ForceCacheLookupHits As Boolean
    Get
'Usage
Dim instance As CacheControlElement
Dim value As Boolean

value = instance.ForceCacheLookupHits
```

``` csharp
[ConfigurationPropertyAttribute("forceCacheLookupHit", DefaultValue = false)]
public bool ForceCacheLookupHits { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"forceCacheLookupHit", DefaultValue = false)]
public:
virtual property bool ForceCacheLookupHits {
    bool get () sealed;
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

#### Implements

[ICacheControlElement.ForceCacheLookupHits](icachecontrolelement-forcecachelookuphits-property-microsoft-dynamics-commerce-runtime-configuration.md)  

## See Also

#### Reference

[CacheControlElement Class](cachecontrolelement-class-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

