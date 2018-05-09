---
title: CheckoutController.SetLineDeliveryOptions Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: SetLineDeliveryOptions Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.SetLineDeliveryOptions(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SelectedLineDeliveryOption},Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.IProductValidator,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCartDataLevel)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.checkoutcontroller.setlinedeliveryoptions(v=AX.60)
ms:contentKeyID: 65317193
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.SetLineDeliveryOptions
dev_langs:
- CSharp
- C++
- VB
---

# SetLineDeliveryOptions Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function SetLineDeliveryOptions ( _
    shoppingCartId As String, _
    customerId As String, _
    lineDeliveryOptions As IEnumerable(Of SelectedLineDeliveryOption), _
    productValidator As IProductValidator, _
    searchEngine As ISearchEngine, _
    dataLevel As ShoppingCartDataLevel _
) As ShoppingCart
'Usage
Dim instance As CheckoutController
Dim shoppingCartId As String
Dim customerId As String
Dim lineDeliveryOptions As IEnumerable(Of SelectedLineDeliveryOption)
Dim productValidator As IProductValidator
Dim searchEngine As ISearchEngine
Dim dataLevel As ShoppingCartDataLevel
Dim returnValue As ShoppingCart

returnValue = instance.SetLineDeliveryOptions(shoppingCartId, _
    customerId, lineDeliveryOptions, _
    productValidator, searchEngine, _
    dataLevel)
```

``` csharp
public virtual ShoppingCart SetLineDeliveryOptions(
    string shoppingCartId,
    string customerId,
    IEnumerable<SelectedLineDeliveryOption> lineDeliveryOptions,
    IProductValidator productValidator,
    ISearchEngine searchEngine,
    ShoppingCartDataLevel dataLevel
)
```

``` c++
public:
virtual ShoppingCart^ SetLineDeliveryOptions(
    String^ shoppingCartId, 
    String^ customerId, 
    IEnumerable<SelectedLineDeliveryOption^>^ lineDeliveryOptions, 
    IProductValidator^ productValidator, 
    ISearchEngine^ searchEngine, 
    ShoppingCartDataLevel dataLevel
)
```

#### Parameters

  - shoppingCartId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - lineDeliveryOptions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[SelectedLineDeliveryOption](selectedlinedeliveryoption-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

<!-- end list -->

  - productValidator  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.IProductValidator](iproductvalidator-interface-microsoft-dynamics-retail-ecommerce-sdk-core.md)  

<!-- end list -->

  - searchEngine  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine](isearchengine-interface-microsoft-dynamics-retail-ecommerce-sdk-core.md)  

<!-- end list -->

  - dataLevel  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCartDataLevel](shoppingcartdatalevel-enumeration-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCart](shoppingcart-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[CheckoutController Class](checkoutcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

