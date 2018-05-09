---
title: CommerceRuntimeSection.CompositionElement Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: CompositionElement Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection.CompositionElement
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.configuration.commerceruntimesection.compositionelement(v=AX.60)
ms:contentKeyID: 65321181
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection.CompositionElement
dev_langs:
- CSharp
- C++
- VB
---

# CompositionElement Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders (in Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll)

## Syntax

``` vb
'Declaration
<ConfigurationPropertyAttribute("composition")> _
Public ReadOnly Property CompositionElement As CompositionElementCollection
    Get
'Usage
Dim instance As CommerceRuntimeSection
Dim value As CompositionElementCollection

value = instance.CompositionElement
```

``` csharp
[ConfigurationPropertyAttribute("composition")]
public CompositionElementCollection CompositionElement { get; }
```

``` c++
[ConfigurationPropertyAttribute(L"composition")]
public:
property CompositionElementCollection^ CompositionElement {
    CompositionElementCollection^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Configuration.CompositionElementCollection](compositionelementcollection-class-microsoft-dynamics-commerce-runtime-configuration.md)  

## See Also

#### Reference

[CommerceRuntimeSection Class](commerceruntimesection-class-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

