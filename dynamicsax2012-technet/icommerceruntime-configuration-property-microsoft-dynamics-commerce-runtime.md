---
title: ICommerceRuntime.Configuration Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Configuration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntime.Configuration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.icommerceruntime.configuration(v=AX.60)
ms:contentKeyID: 65318346
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntime.Configuration
dev_langs:
- CSharp
- C++
- VB
---

# Configuration Property

Gets the instance of the commerce runtime configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property Configuration As ICommerceRuntimeConfiguration
    Get
'Usage
Dim instance As ICommerceRuntime
Dim value As ICommerceRuntimeConfiguration

value = instance.Configuration
```

``` csharp
ICommerceRuntimeConfiguration Configuration { get; }
```

``` c++
property ICommerceRuntimeConfiguration^ Configuration {
    ICommerceRuntimeConfiguration^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntimeConfiguration](icommerceruntimeconfiguration-interface-microsoft-dynamics-commerce-runtime.md)  
Returns [ICommerceRuntimeConfiguration](icommerceruntimeconfiguration-interface-microsoft-dynamics-commerce-runtime.md).  

## See Also

#### Reference

[ICommerceRuntime Interface](icommerceruntime-interface-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

