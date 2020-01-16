---
title: CompositionManager.CreateContainerConfiguration Method  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: CreateContainerConfiguration Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Configuration.CompositionManager.CreateContainerConfiguration(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.Configuration.ICompositionElement})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.compositionmanager.createcontainerconfiguration(v=AX.60)
ms:contentKeyID: 65319398
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.CompositionManager.CreateContainerConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# CreateContainerConfiguration Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime (in Microsoft.Dynamics.Commerce.Runtime.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateContainerConfiguration ( _
    compositionElementCollection As IEnumerable(Of ICompositionElement) _
) As ContainerConfiguration
'Usage
Dim compositionElementCollection As IEnumerable(Of ICompositionElement)
Dim returnValue As ContainerConfiguration

returnValue = CompositionManager.CreateContainerConfiguration(compositionElementCollection)
```

``` csharp
public static ContainerConfiguration CreateContainerConfiguration(
    IEnumerable<ICompositionElement> compositionElementCollection
)
```

``` c++
public:
static ContainerConfiguration^ CreateContainerConfiguration(
    IEnumerable<ICompositionElement^>^ compositionElementCollection
)
```

#### Parameters

  - compositionElementCollection  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ICompositionElement](icompositionelement-interface-microsoft-dynamics-commerce-runtime-configuration.md)\>  

#### Return Value

Type: ContainerConfiguration  

## See Also

#### Reference

[CompositionManager Class](compositionmanager-class-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

