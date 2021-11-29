---
title: CommerceRuntimeConfiguration.AggregateCatalog Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: AggregateCatalog Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeConfiguration.AggregateCatalog
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.commerceruntimeconfiguration.aggregatecatalog(v=AX.60)
ms:contentKeyID: 49841360
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.CommerceRuntimeConfiguration.AggregateCatalog
dev_langs:
- CSharp
- C++
- VB
---

# AggregateCatalog Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the aggregate catalog used during service composition.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime (in Microsoft.Dynamics.Commerce.Runtime.dll)

## Syntax

``` vb
'Declaration
Public Property AggregateCatalog As ContainerConfiguration
    Get
    Private Set
'Usage
Dim instance As CommerceRuntimeConfiguration
Dim value As ContainerConfiguration

value = instance.AggregateCatalog
```

``` csharp
public ContainerConfiguration AggregateCatalog { get; private set; }
```

``` c++
public:
virtual property ContainerConfiguration^ AggregateCatalog {
    ContainerConfiguration^ get () sealed;
    private: void set (ContainerConfiguration^ value) sealed;
}
```

#### Property Value

Type: ContainerConfiguration  
Returns AggregateCatalog.  

#### Implements

[ICommerceRuntimeConfiguration.AggregateCatalog](icommerceruntimeconfiguration-aggregatecatalog-property-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[CommerceRuntimeConfiguration Class](commerceruntimeconfiguration-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

