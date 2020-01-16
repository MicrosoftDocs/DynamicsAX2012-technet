---
title: ShippingManager.Create Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: Create Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ShippingManager.Create(Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.shippingmanager.create(v=AX.60)
ms:contentKeyID: 62210072
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ShippingManager.Create
dev_langs:
- CSharp
- C++
- VB
---

# Create Method

Creates a new instance of the shipping manager.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Shared Function Create ( _
    runtime As CommerceRuntime _
) As ShippingManager
'Usage
Dim runtime As CommerceRuntime
Dim returnValue As ShippingManager

returnValue = ShippingManager.Create(runtime)
```

``` csharp
public static ShippingManager Create(
    CommerceRuntime runtime
)
```

``` c++
public:
static ShippingManager^ Create(
    CommerceRuntime^ runtime
)
```

#### Parameters

  - runtime  
    Type: [Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime](commerceruntime-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Client.ShippingManager](shippingmanager-class-microsoft-dynamics-commerce-runtime-client.md)  
A new instance of [ProductManager](productmanager-class-microsoft-dynamics-commerce-runtime-client.md).  

## See Also

#### Reference

[ShippingManager Class](shippingmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

