---
title: ICommerceRuntimeConfiguration.AggregateCatalog Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: AggregateCatalog Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntimeConfiguration.AggregateCatalog
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.icommerceruntimeconfiguration.aggregatecatalog(v=AX.60)
ms:contentKeyID: 65320269
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntimeConfiguration.AggregateCatalog
dev_langs:
- CSharp
- C++
- VB
---

# AggregateCatalog Property

Gets the aggregate catalog used during service composition.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property AggregateCatalog As ContainerConfiguration
    Get
'Usage
Dim instance As ICommerceRuntimeConfiguration
Dim value As ContainerConfiguration

value = instance.AggregateCatalog
```

``` csharp
ContainerConfiguration AggregateCatalog { get; }
```

``` c++
property ContainerConfiguration^ AggregateCatalog {
    ContainerConfiguration^ get ();
}
```

#### Property Value

Type: ContainerConfiguration  
Returns ContainerConfiguration.  

## See Also

#### Reference

[ICommerceRuntimeConfiguration Interface](icommerceruntimeconfiguration-interface-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

