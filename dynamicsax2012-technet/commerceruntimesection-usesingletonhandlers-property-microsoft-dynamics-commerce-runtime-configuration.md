---
title: CommerceRuntimeSection.UseSingletonHandlers Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: UseSingletonHandlers Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection.UseSingletonHandlers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.commerceruntimesection.usesingletonhandlers(v=AX.60)
ms:contentKeyID: 65320405
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection.UseSingletonHandlers
dev_langs:
- CSharp
- C++
- VB
---

# UseSingletonHandlers Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders (in Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("useSingletonHandlers", DefaultValue := "false",  _
    IsRequired := False)> _
Public ReadOnly Property UseSingletonHandlers As Boolean
    Get
'Usage
Dim instance As CommerceRuntimeSection
Dim value As Boolean

value = instance.UseSingletonHandlers
```

``` csharp
[ConfigurationPropertyAttribute("useSingletonHandlers", DefaultValue = "false", IsRequired = false)]
public bool UseSingletonHandlers { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"useSingletonHandlers", DefaultValue = L"false", 
    IsRequired = false)]
public:
virtual property bool UseSingletonHandlers {
    bool get () sealed;
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Implements

[ICommerceRuntimeSection.UseSingletonHandlers](icommerceruntimesection-usesingletonhandlers-property-microsoft-dynamics-commerce-runtime-configuration.md)  

## See Also

#### Reference

[CommerceRuntimeSection Class](commerceruntimesection-class-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

