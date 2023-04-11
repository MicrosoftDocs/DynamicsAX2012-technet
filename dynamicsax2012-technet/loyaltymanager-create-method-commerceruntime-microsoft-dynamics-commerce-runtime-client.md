---
title: LoyaltyManager.Create Method (CommerceRuntime) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: Create Method (CommerceRuntime)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.LoyaltyManager.Create(Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.loyaltymanager.create(v=AX.60)
ms:contentKeyID: 62205953
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Create Method (CommerceRuntime)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates a new instance of the [LoyaltyManager](loyaltymanager-class-microsoft-dynamics-commerce-runtime-client.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Shared Function Create ( _
    runtime As CommerceRuntime _
) As LoyaltyManager
'Usage
Dim runtime As CommerceRuntime
Dim returnValue As LoyaltyManager

returnValue = LoyaltyManager.Create(runtime)
```

``` csharp
public static LoyaltyManager Create(
    CommerceRuntime runtime
)
```

``` c++
public:
static LoyaltyManager^ Create(
    CommerceRuntime^ runtime
)
```

#### Parameters

  - runtime  
    Type: [Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime](commerceruntime-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Client.LoyaltyManager](loyaltymanager-class-microsoft-dynamics-commerce-runtime-client.md)  
A new instance of [LoyaltyManager](loyaltymanager-class-microsoft-dynamics-commerce-runtime-client.md) class.  

## See Also

#### Reference

[LoyaltyManager Class](loyaltymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Create Overload](loyaltymanager-create-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

