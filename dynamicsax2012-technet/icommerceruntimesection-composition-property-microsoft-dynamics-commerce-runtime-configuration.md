---
title: ICommerceRuntimeSection.Composition Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: Composition Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.ICommerceRuntimeSection.Composition
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.icommerceruntimesection.composition(v=AX.60)
ms:contentKeyID: 65321054
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.ICommerceRuntimeSection.Composition
dev_langs:
- CSharp
- C++
- VB
---

# Composition Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the composition collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property Composition As IEnumerable(Of ICompositionElement)
    Get
'Usage
Dim instance As ICommerceRuntimeSection
Dim value As IEnumerable(Of ICompositionElement)

value = instance.Composition
```

``` csharp
IEnumerable<ICompositionElement> Composition { get; }
```

``` c++
property IEnumerable<ICompositionElement^>^ Composition {
    IEnumerable<ICompositionElement^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ICompositionElement](icompositionelement-interface-microsoft-dynamics-commerce-runtime-configuration.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ICommerceRuntimeSection Interface](icommerceruntimesection-interface-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

