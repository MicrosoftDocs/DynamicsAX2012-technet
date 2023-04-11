---
title: ShoppingCartController.ClaimAnonymousCart Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: ClaimAnonymousCart Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.ShoppingCartController.ClaimAnonymousCart(System.String,System.String,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCartDataLevel,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.IProductValidator,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.shoppingcartcontroller.claimanonymouscart(v=AX.60)
ms:contentKeyID: 65317108
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.ShoppingCartController.ClaimAnonymousCart
dev_langs:
- CSharp
- C++
- VB
---

# ClaimAnonymousCart Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function ClaimAnonymousCart ( _
    shoppingCartIdToBeClaimed As String, _
    customerId As String, _
    dataLevel As ShoppingCartDataLevel, _
    productValidator As IProductValidator, _
    searchEngine As ISearchEngine _
) As ShoppingCart
'Usage
Dim instance As ShoppingCartController
Dim shoppingCartIdToBeClaimed As String
Dim customerId As String
Dim dataLevel As ShoppingCartDataLevel
Dim productValidator As IProductValidator
Dim searchEngine As ISearchEngine
Dim returnValue As ShoppingCart

returnValue = instance.ClaimAnonymousCart(shoppingCartIdToBeClaimed, _
    customerId, dataLevel, productValidator, _
    searchEngine)
```

``` csharp
public virtual ShoppingCart ClaimAnonymousCart(
    string shoppingCartIdToBeClaimed,
    string customerId,
    ShoppingCartDataLevel dataLevel,
    IProductValidator productValidator,
    ISearchEngine searchEngine
)
```

``` c++
public:
virtual ShoppingCart^ ClaimAnonymousCart(
    String^ shoppingCartIdToBeClaimed, 
    String^ customerId, 
    ShoppingCartDataLevel dataLevel, 
    IProductValidator^ productValidator, 
    ISearchEngine^ searchEngine
)
```

#### Parameters

  - shoppingCartIdToBeClaimed  
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

[ShoppingCartController Class](shoppingcartcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

