---
title: ShoppingCartServiceBase.GetPromotions Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetPromotions Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartServiceBase.GetPromotions(System.Boolean,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCartDataLevel)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.shoppingcartservicebase.getpromotions(v=AX.60)
ms:contentKeyID: 65317534
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartServiceBase.GetPromotions
dev_langs:
- CSharp
- C++
- VB
---

# GetPromotions Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetPromotions ( _
    isCheckoutSession As Boolean, _
    dataLevel As ShoppingCartDataLevel _
) As ShoppingCartResponse
'Usage
Dim instance As ShoppingCartServiceBase
Dim isCheckoutSession As Boolean
Dim dataLevel As ShoppingCartDataLevel
Dim returnValue As ShoppingCartResponse

returnValue = instance.GetPromotions(isCheckoutSession, _
    dataLevel)
```

``` csharp
public virtual ShoppingCartResponse GetPromotions(
    bool isCheckoutSession,
    ShoppingCartDataLevel dataLevel
)
```

``` c++
public:
virtual ShoppingCartResponse^ GetPromotions(
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

[IShoppingCartService.GetPromotions(Boolean, ShoppingCartDataLevel)](ishoppingcartservice-getpromotions-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[ShoppingCartServiceBase Class](shoppingcartservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

