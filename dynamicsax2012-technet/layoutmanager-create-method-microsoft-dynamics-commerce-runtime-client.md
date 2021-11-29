---
title: LayoutManager.Create Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: Create Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.LayoutManager.Create(Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.layoutmanager.create(v=AX.60)
ms:contentKeyID: 62209649
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.LayoutManager.Create
dev_langs:
- CSharp
- C++
- VB
---

# Create Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates a new instance of the buttongrid manager.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Shared Function Create ( _
    runtime As CommerceRuntime _
) As LayoutManager
'Usage
Dim runtime As CommerceRuntime
Dim returnValue As LayoutManager

returnValue = LayoutManager.Create(runtime)
```

``` csharp
public static LayoutManager Create(
    CommerceRuntime runtime
)
```

``` c++
public:
static LayoutManager^ Create(
    CommerceRuntime^ runtime
)
```

#### Parameters

  - runtime  
    Type: [Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime](commerceruntime-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Client.LayoutManager](layoutmanager-class-microsoft-dynamics-commerce-runtime-client.md)  
A new instance of [LayoutManager](layoutmanager-class-microsoft-dynamics-commerce-runtime-client.md).  

## See Also

#### Reference

[LayoutManager Class](layoutmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

