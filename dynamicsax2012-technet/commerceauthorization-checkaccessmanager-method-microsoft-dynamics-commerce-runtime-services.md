---
title: CommerceAuthorization.CheckAccessManager Method  (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: CheckAccessManager Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.CommerceAuthorization.CheckAccessManager(Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.commerceauthorization.checkaccessmanager(v=AX.60)
ms:contentKeyID: 62208112
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.CommerceAuthorization.CheckAccessManager
dev_langs:
- CSharp
- C++
- VB
---

# CheckAccessManager Method

Method to check if the principal has manager permission.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub CheckAccessManager ( _
    principal As CommercePrincipal _
)
'Usage
Dim principal As CommercePrincipal

CommerceAuthorization.CheckAccessManager(principal)
```

``` csharp
public static void CheckAccessManager(
    CommercePrincipal principal
)
```

``` c++
public:
static void CheckAccessManager(
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

