---
title: CommerceRuntime.Create Method (ICommerceRuntimeConfiguration, CommercePrincipal) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Create Method (ICommerceRuntimeConfiguration, CommercePrincipal)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime.Create(Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntimeConfiguration,Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.commerceruntime.create(v=AX.60)
ms:contentKeyID: 65319536
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Create Method (ICommerceRuntimeConfiguration, CommercePrincipal)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime (in Microsoft.Dynamics.Commerce.Runtime.dll)

## Syntax

``` vb
'Declaration
Public Shared Function Create ( _
    configuration As ICommerceRuntimeConfiguration, _
    principal As CommercePrincipal _
) As CommerceRuntime
'Usage
Dim configuration As ICommerceRuntimeConfiguration
Dim principal As CommercePrincipal
Dim returnValue As CommerceRuntime

returnValue = CommerceRuntime.Create(configuration, _
    principal)
```

``` csharp
public static CommerceRuntime Create(
    ICommerceRuntimeConfiguration configuration,
    CommercePrincipal principal
)
```

``` c++
public:
static CommerceRuntime^ Create(
    ICommerceRuntimeConfiguration^ configuration, 
    CommercePrincipal^ principal
)
```

#### Parameters

  - configuration  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntimeConfiguration](icommerceruntimeconfiguration-interface-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - principal  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime](commerceruntime-class-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[CommerceRuntime Class](commerceruntime-class-microsoft-dynamics-commerce-runtime.md)

[Create Overload](commerceruntime-create-method-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

