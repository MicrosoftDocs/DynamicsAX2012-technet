---
title: CommerceRuntimeSection.Composition Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: Composition Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection.Composition
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.commerceruntimesection.composition(v=AX.60)
ms:contentKeyID: 49820761
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.CommerceRuntimeSection.Composition
dev_langs:
- CSharp
- C++
- VB
---

# Composition Property

Gets the composition collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders (in Microsoft.Dynamics.Commerce.Runtime.ConfigurationProviders.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property Composition As IEnumerable(Of ICompositionElement)
    Get
'Usage
Dim instance As CommerceRuntimeSection
Dim value As IEnumerable(Of ICompositionElement)

value = instance.Composition
```

``` csharp
public IEnumerable<ICompositionElement> Composition { get; }
```

``` c++
public:
virtual property IEnumerable<ICompositionElement^>^ Composition {
    IEnumerable<ICompositionElement^>^ get () sealed;
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ICompositionElement](icompositionelement-interface-microsoft-dynamics-commerce-runtime-configuration.md)\>  
Returns [CompositionElementCollection](compositionelementcollection-class-microsoft-dynamics-commerce-runtime-configuration.md).  

#### Implements

[ICommerceRuntimeSection.Composition](icommerceruntimesection-composition-property-microsoft-dynamics-commerce-runtime-configuration.md)  

## See Also

#### Reference

[CommerceRuntimeSection Class](commerceruntimesection-class-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

