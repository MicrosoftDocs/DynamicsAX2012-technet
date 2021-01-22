---
title: CommerceRuntime.Configuration Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Configuration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime.Configuration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.commerceruntime.configuration(v=AX.60)
ms:contentKeyID: 49849075
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime.Configuration
dev_langs:
- CSharp
- C++
- VB
---

# Configuration Property

Gets the configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime (in Microsoft.Dynamics.Commerce.Runtime.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property Configuration As ICommerceRuntimeConfiguration
    Get
'Usage
Dim instance As CommerceRuntime
Dim value As ICommerceRuntimeConfiguration

value = instance.Configuration
```

``` csharp
public ICommerceRuntimeConfiguration Configuration { get; }
```

``` c++
public:
virtual property ICommerceRuntimeConfiguration^ Configuration {
    ICommerceRuntimeConfiguration^ get () sealed;
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntimeConfiguration](icommerceruntimeconfiguration-interface-microsoft-dynamics-commerce-runtime.md)  
Returns [CommerceRuntimeConfiguration](commerceruntimeconfiguration-class-microsoft-dynamics-commerce-runtime.md).  

#### Implements

[ICommerceRuntime.Configuration](icommerceruntime-configuration-property-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[CommerceRuntime Class](commerceruntime-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

