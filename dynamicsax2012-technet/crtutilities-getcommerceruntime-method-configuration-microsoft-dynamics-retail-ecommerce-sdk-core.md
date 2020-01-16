---
title: CrtUtilities.GetCommerceRuntime Method (Configuration) (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core)
TOCTitle: GetCommerceRuntime Method (Configuration)
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.CrtUtilities.GetCommerceRuntime(System.Configuration.Configuration)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.crtutilities.getcommerceruntime(v=AX.60)
ms:contentKeyID: 65318089
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCommerceRuntime Method (Configuration)

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core](microsoft-dynamics-retail-ecommerce-sdk-core-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetCommerceRuntime ( _
    appConfiguration As Configuration _
) As CommerceRuntime
'Usage
Dim appConfiguration As Configuration
Dim returnValue As CommerceRuntime

returnValue = CrtUtilities.GetCommerceRuntime(appConfiguration)
```

``` csharp
public static CommerceRuntime GetCommerceRuntime(
    Configuration appConfiguration
)
```

``` c++
public:
static CommerceRuntime^ GetCommerceRuntime(
    Configuration^ appConfiguration
)
```

#### Parameters

  - appConfiguration  
    Type: [System.Configuration.Configuration](https://technet.microsoft.com/library/s7kc101z\(v=ax.60\))  

#### Return Value

Type: CommerceRuntime  

## See Also

#### Reference

[CrtUtilities Class](crtutilities-class-microsoft-dynamics-retail-ecommerce-sdk-core.md)

[GetCommerceRuntime Overload](crtutilities-getcommerceruntime-method-microsoft-dynamics-retail-ecommerce-sdk-core.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-namespace.md)

