---
title: CommerceAuthorization.CheckAccessHasShift Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: CheckAccessHasShift Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.CommerceAuthorization.CheckAccessHasShift(Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.commerceauthorization.checkaccesshasshift(v=AX.60)
ms:contentKeyID: 62208236
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CommerceAuthorization.CheckAccessHasShift
dev_langs:
- CSharp
- C++
- VB
---

# CheckAccessHasShift Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Method to check if the principal has a shift.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub CheckAccessHasShift ( _
    principal As CommercePrincipal _
)
'Usage
Dim principal As CommercePrincipal

CommerceAuthorization.CheckAccessHasShift(principal)
```

``` csharp
public static void CheckAccessHasShift(
    CommercePrincipal principal
)
```

``` c++
public:
static void CheckAccessHasShift(
    CommercePrincipal^ principal
)
```

#### Parameters

  - principal  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[CommerceAuthorization Class](commerceauthorization-class-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

