---
title: CacheControlElement.IsCacheUpdatingDisabled Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: IsCacheUpdatingDisabled Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.CacheControlElement.IsCacheUpdatingDisabled
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.configuration.cachecontrolelement.iscacheupdatingdisabled(v=AX.60)
ms:contentKeyID: 62214775
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.CacheControlElement.IsCacheUpdatingDisabled
dev_langs:
- CSharp
- C++
- VB
---

# IsCacheUpdatingDisabled Property

Gets a value indicating whether cache updates are allowed or not.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders (in Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("disableCacheUpdates", DefaultValue := False)> _
Public ReadOnly Property IsCacheUpdatingDisabled As Boolean
    Get
'Usage
Dim instance As CacheControlElement
Dim value As Boolean

value = instance.IsCacheUpdatingDisabled
```

``` csharp
[ConfigurationPropertyAttribute("disableCacheUpdates", DefaultValue = false)]
public bool IsCacheUpdatingDisabled { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"disableCacheUpdates", DefaultValue = false)]
public:
virtual property bool IsCacheUpdatingDisabled {
    bool get () sealed;
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

#### Implements

[ICacheControlElement.IsCacheUpdatingDisabled](icachecontrolelement-iscacheupdatingdisabled-property-microsoft-dynamics-commerce-runtime-configuration.md)  

## See Also

#### Reference

[CacheControlElement Class](cachecontrolelement-class-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

