---
title: CommerceRuntimeConfiguration.Composition Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Composition Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeConfiguration.Composition
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.commerceruntimeconfiguration.composition(v=AX.60)
ms:contentKeyID: 65323206
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeConfiguration.Composition
dev_langs:
- CSharp
- C++
- VB
---

# Composition Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime (in Microsoft.Dynamics.Commerce.Runtime.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property Composition As ICompositionLoader
    Get
'Usage
Dim instance As CommerceRuntimeConfiguration
Dim value As ICompositionLoader

value = instance.Composition
```

``` csharp
public ICompositionLoader Composition { get; }
```

``` c++
public:
virtual property ICompositionLoader^ Composition {
    ICompositionLoader^ get () sealed;
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.ICompositionLoader](icompositionloader-interface-microsoft-dynamics-commerce-runtime.md)  

#### Implements

[ICommerceRuntimeConfiguration.Composition](icommerceruntimeconfiguration-composition-property-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[CommerceRuntimeConfiguration Class](commerceruntimeconfiguration-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

