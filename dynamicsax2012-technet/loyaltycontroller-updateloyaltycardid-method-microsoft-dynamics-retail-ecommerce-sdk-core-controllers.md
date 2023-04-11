---
title: LoyaltyController.UpdateLoyaltyCardId Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: UpdateLoyaltyCardId Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.LoyaltyController.UpdateLoyaltyCardId(System.String,System.String,System.String,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCartDataLevel,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.IProductValidator,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.loyaltycontroller.updateloyaltycardid(v=AX.60)
ms:contentKeyID: 65316395
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.LoyaltyController.UpdateLoyaltyCardId
dev_langs:
- CSharp
- C++
- VB
---

# UpdateLoyaltyCardId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function UpdateLoyaltyCardId ( _
    shoppingCartId As String, _
    loyaltyCardId As String, _
    customerId As String, _
    dataLevel As ShoppingCartDataLevel, _
    productValidator As IProductValidator, _
    searchEngine As ISearchEngine _
) As ShoppingCart
'Usage
Dim instance As LoyaltyController
Dim shoppingCartId As String
Dim loyaltyCardId As String
Dim customerId As String
Dim dataLevel As ShoppingCartDataLevel
Dim productValidator As IProductValidator
Dim searchEngine As ISearchEngine
Dim returnValue As ShoppingCart

returnValue = instance.UpdateLoyaltyCardId(shoppingCartId, _
    loyaltyCardId, customerId, dataLevel, _
    productValidator, searchEngine)
```

``` csharp
public virtual ShoppingCart UpdateLoyaltyCardId(
    string shoppingCartId,
    string loyaltyCardId,
    string customerId,
    ShoppingCartDataLevel dataLevel,
    IProductValidator productValidator,
    ISearchEngine searchEngine
)
```

``` c++
public:
virtual ShoppingCart^ UpdateLoyaltyCardId(
    String^ shoppingCartId, 
    String^ loyaltyCardId, 
    String^ customerId, 
    ShoppingCartDataLevel dataLevel, 
    IProductValidator^ productValidator, 
    ISearchEngine^ searchEngine
)
```

#### Parameters

  - shoppingCartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - loyaltyCardId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - dataLevel  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCartDataLevel](shoppingcartdatalevel-enumeration-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

<!-- end list -->

  - productValidator  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.IProductValidator](iproductvalidator-interface-microsoft-dynamics-retail-ecommerce-sdk-core.md)  

<!-- end list -->

  - searchEngine  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine](isearchengine-interface-microsoft-dynamics-retail-ecommerce-sdk-core.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCart](shoppingcart-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[LoyaltyController Class](loyaltycontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

