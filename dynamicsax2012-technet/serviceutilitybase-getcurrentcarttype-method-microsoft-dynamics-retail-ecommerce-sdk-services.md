---
title: ServiceUtilityBase.GetCurrentCartType Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetCurrentCartType Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceUtilityBase.GetCurrentCartType(System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.serviceutilitybase.getcurrentcarttype(v=AX.60)
ms:contentKeyID: 65317665
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ServiceUtilityBase.GetCurrentCartType
dev_langs:
- CSharp
- C++
- VB
---

# GetCurrentCartType Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetCurrentCartType ( _
    isCheckoutSession As Boolean _
) As CartType
'Usage
Dim instance As ServiceUtilityBase
Dim isCheckoutSession As Boolean
Dim returnValue As CartType

returnValue = instance.GetCurrentCartType(isCheckoutSession)
```

``` csharp
public virtual CartType GetCurrentCartType(
    bool isCheckoutSession
)
```

``` c++
public:
virtual CartType GetCurrentCartType(
    bool isCheckoutSession
)
```

#### Parameters

  - isCheckoutSession  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.CartType](carttype-enumeration-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[ServiceUtilityBase Class](serviceutilitybase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

