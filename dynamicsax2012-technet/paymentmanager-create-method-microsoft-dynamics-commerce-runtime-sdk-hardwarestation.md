---
title: PaymentManager.Create Method  (Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation)
TOCTitle: Create Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.PaymentManager.Create(Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.sdk.hardwarestation.paymentmanager.create(v=AX.60)
ms:contentKeyID: 65319628
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.PaymentManager.Create
dev_langs:
- CSharp
- C++
- VB
---

# Create Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates a new instance of the merchandising manager.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation](microsoft-dynamics-commerce-runtime-sdk-hardwarestation-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation (in Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.dll)

## Syntax

``` vb
'Declaration
Public Shared Function Create ( _
    runtime As CommerceRuntime _
) As PaymentManager
'Usage
Dim runtime As CommerceRuntime
Dim returnValue As PaymentManager

returnValue = PaymentManager.Create(runtime)
```

``` csharp
public static PaymentManager Create(
    CommerceRuntime runtime
)
```

``` c++
public:
static PaymentManager^ Create(
    CommerceRuntime^ runtime
)
```

#### Parameters

  - runtime  
    Type: [Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime](commerceruntime-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation.PaymentManager](paymentmanager-class-microsoft-dynamics-commerce-runtime-sdk-hardwarestation.md)  
A new instance of [PaymentManager](paymentmanager-class-microsoft-dynamics-commerce-runtime-sdk-hardwarestation.md).  

## See Also

#### Reference

[PaymentManager Class](paymentmanager-class-microsoft-dynamics-commerce-runtime-sdk-hardwarestation.md)

[Microsoft.Dynamics.Commerce.Runtime.Sdk.HardwareStation Namespace](microsoft-dynamics-commerce-runtime-sdk-hardwarestation-namespace.md)

