---
title: ShoppingCartController.UpdateItems Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: UpdateItems Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.ShoppingCartController.UpdateItems(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TransactionItem},Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCartDataLevel,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.IProductValidator,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.shoppingcartcontroller.updateitems(v=AX.60)
ms:contentKeyID: 65317792
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.ShoppingCartController.UpdateItems
dev_langs:
- CSharp
- C++
- VB
---

# UpdateItems Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function UpdateItems ( _
    shoppingCartId As String, _
    customerId As String, _
    items As IEnumerable(Of TransactionItem), _
    dataLevel As ShoppingCartDataLevel, _
    productValidator As IProductValidator, _
    searchEngine As ISearchEngine _
) As ShoppingCart
'Usage
Dim instance As ShoppingCartController
Dim shoppingCartId As String
Dim customerId As String
Dim items As IEnumerable(Of TransactionItem)
Dim dataLevel As ShoppingCartDataLevel
Dim productValidator As IProductValidator
Dim searchEngine As ISearchEngine
Dim returnValue As ShoppingCart

returnValue = instance.UpdateItems(shoppingCartId, _
    customerId, items, dataLevel, productValidator, _
    searchEngine)
```

``` csharp
public virtual ShoppingCart UpdateItems(
    string shoppingCartId,
    string customerId,
    IEnumerable<TransactionItem> items,
    ShoppingCartDataLevel dataLevel,
    IProductValidator productValidator,
    ISearchEngine searchEngine
)
```

``` c++
public:
virtual ShoppingCart^ UpdateItems(
    String^ shoppingCartId, 
    String^ customerId, 
    IEnumerable<TransactionItem^>^ items, 
    ShoppingCartDataLevel dataLevel, 
    IProductValidator^ productValidator, 
    ISearchEngine^ searchEngine
)
```

#### Parameters

  - shoppingCartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - items  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[TransactionItem](transactionitem-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

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

