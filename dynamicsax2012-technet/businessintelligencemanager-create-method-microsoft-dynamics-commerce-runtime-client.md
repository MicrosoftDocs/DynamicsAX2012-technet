---
title: BusinessIntelligenceManager.Create Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: Create Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.BusinessIntelligenceManager.Create(Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.businessintelligencemanager.create(v=AX.60)
ms:contentKeyID: 62210993
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.BusinessIntelligenceManager.Create
dev_langs:
- CSharp
- C++
- VB
---

# Create Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates a new instance of the [BusinessIntelligenceManager](businessintelligencemanager-class-microsoft-dynamics-commerce-runtime-client.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Shared Function Create ( _
    runtime As CommerceRuntime _
) As BusinessIntelligenceManager
'Usage
Dim runtime As CommerceRuntime
Dim returnValue As BusinessIntelligenceManager

returnValue = BusinessIntelligenceManager.Create(runtime)
```

``` csharp
public static BusinessIntelligenceManager Create(
    CommerceRuntime runtime
)
```

``` c++
public:
static BusinessIntelligenceManager^ Create(
    CommerceRuntime^ runtime
)
```

#### Parameters

  - runtime  
    Type: [Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime](commerceruntime-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Client.BusinessIntelligenceManager](businessintelligencemanager-class-microsoft-dynamics-commerce-runtime-client.md)  
A new instance of the [BusinessIntelligenceManager](businessintelligencemanager-class-microsoft-dynamics-commerce-runtime-client.md) class.  

## See Also

#### Reference

[BusinessIntelligenceManager Class](businessintelligencemanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

