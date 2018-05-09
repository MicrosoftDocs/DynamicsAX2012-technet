---
title: StoreLocatorManager.Create Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: Create Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.StoreLocatorManager.Create(Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.storelocatormanager.create(v=AX.60)
ms:contentKeyID: 49839145
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.StoreLocatorManager.Create
dev_langs:
- CSharp
- C++
- VB
---

# Create Method

Creates a new instance of the [StoreLocatorManager](storelocatormanager-class-microsoft-dynamics-commerce-runtime-client.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Shared Function Create ( _
    runtime As CommerceRuntime _
) As StoreLocatorManager
'Usage
Dim runtime As CommerceRuntime
Dim returnValue As StoreLocatorManager

returnValue = StoreLocatorManager.Create(runtime)
```

``` csharp
public static StoreLocatorManager Create(
    CommerceRuntime runtime
)
```

``` c++
public:
static StoreLocatorManager^ Create(
    CommerceRuntime^ runtime
)
```

#### Parameters

  - runtime  
    Type: [Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime](commerceruntime-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Client.StoreLocatorManager](storelocatormanager-class-microsoft-dynamics-commerce-runtime-client.md)  
A new instance of the [StoreLocatorManager](storelocatormanager-class-microsoft-dynamics-commerce-runtime-client.md) class.  

## See Also

#### Reference

[StoreLocatorManager Class](storelocatormanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

