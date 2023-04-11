---
title: InventoryManager.Create Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: Create Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.Create(Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.create(v=AX.60)
ms:contentKeyID: 49849026
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.Create
dev_langs:
- CSharp
- C++
- VB
---

# Create Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates a new instance of the [InventoryManager](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Shared Function Create ( _
    runtime As CommerceRuntime _
) As InventoryManager
'Usage
Dim runtime As CommerceRuntime
Dim returnValue As InventoryManager

returnValue = InventoryManager.Create(runtime)
```

``` csharp
public static InventoryManager Create(
    CommerceRuntime runtime
)
```

``` c++
public:
static InventoryManager^ Create(
    CommerceRuntime^ runtime
)
```

#### Parameters

  - runtime  
    Type: [Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime](commerceruntime-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)  
A new instance of [InventoryManager](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md).  

## See Also

#### Reference

[InventoryManager Class](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

