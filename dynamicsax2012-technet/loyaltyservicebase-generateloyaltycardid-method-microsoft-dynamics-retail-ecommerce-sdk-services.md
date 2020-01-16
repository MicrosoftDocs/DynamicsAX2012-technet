---
title: LoyaltyServiceBase.GenerateLoyaltyCardId Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GenerateLoyaltyCardId Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.LoyaltyServiceBase.GenerateLoyaltyCardId(System.Boolean,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCartDataLevel)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.loyaltyservicebase.generateloyaltycardid(v=AX.60)
ms:contentKeyID: 65316084
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.LoyaltyServiceBase.GenerateLoyaltyCardId
dev_langs:
- CSharp
- C++
- VB
---

# GenerateLoyaltyCardId Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GenerateLoyaltyCardId ( _
    isCheckoutSession As Boolean, _
    dataLevel As ShoppingCartDataLevel _
) As ShoppingCartResponse
'Usage
Dim instance As LoyaltyServiceBase
Dim isCheckoutSession As Boolean
Dim dataLevel As ShoppingCartDataLevel
Dim returnValue As ShoppingCartResponse

returnValue = instance.GenerateLoyaltyCardId(isCheckoutSession, _
    dataLevel)
```

``` csharp
public virtual ShoppingCartResponse GenerateLoyaltyCardId(
    bool isCheckoutSession,
    ShoppingCartDataLevel dataLevel
)
```

``` c++
public:
virtual ShoppingCartResponse^ GenerateLoyaltyCardId(
    bool isCheckoutSession, 
    ShoppingCartDataLevel dataLevel
)
```

#### Parameters

  - isCheckoutSession  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - dataLevel  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCartDataLevel](shoppingcartdatalevel-enumeration-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartResponse](shoppingcartresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[ILoyaltyService.GenerateLoyaltyCardId(Boolean, ShoppingCartDataLevel)](iloyaltyservice-generateloyaltycardid-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[LoyaltyServiceBase Class](loyaltyservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

