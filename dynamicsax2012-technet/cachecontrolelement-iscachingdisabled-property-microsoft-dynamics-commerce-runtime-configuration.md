---
title: CacheControlElement.IsCachingDisabled Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: IsCachingDisabled Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.CacheControlElement.IsCachingDisabled
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.cachecontrolelement.iscachingdisabled(v=AX.60)
ms:contentKeyID: 62211252
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.CacheControlElement.IsCachingDisabled
dev_langs:
- CSharp
- C++
- VB
---

# IsCachingDisabled Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether caching is disabled or not.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders (in Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("disableCaching", DefaultValue := False)> _
Public ReadOnly Property IsCachingDisabled As Boolean
    Get
'Usage
Dim instance As CacheControlElement
Dim value As Boolean

value = instance.IsCachingDisabled
```

``` csharp
[ConfigurationPropertyAttribute("disableCaching", DefaultValue = false)]
public bool IsCachingDisabled { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"disableCaching", DefaultValue = false)]
public:
virtual property bool IsCachingDisabled {
    bool get () sealed;
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

#### Implements

[ICacheControlElement.IsCachingDisabled](icachecontrolelement-iscachingdisabled-property-microsoft-dynamics-commerce-runtime-configuration.md)  

## See Also

#### Reference

[CacheControlElement Class](cachecontrolelement-class-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

