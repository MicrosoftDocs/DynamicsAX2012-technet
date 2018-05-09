---
title: CheckoutController.SetOrderDeliveryOption Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: SetOrderDeliveryOption Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.SetOrderDeliveryOption(System.String,System.String,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SelectedDeliveryOption,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.IProductValidator,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCartDataLevel)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.checkoutcontroller.setorderdeliveryoption(v=AX.60)
ms:contentKeyID: 65316220
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.SetOrderDeliveryOption
dev_langs:
- CSharp
- C++
- VB
---

# SetOrderDeliveryOption Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function SetOrderDeliveryOption ( _
    shoppingCartId As String, _
    customerId As String, _
    selectedDeliveryOption As SelectedDeliveryOption, _
    productValidator As IProductValidator, _
    searchEngine As ISearchEngine, _
    dataLevel As ShoppingCartDataLevel _
) As ShoppingCart
'Usage
Dim instance As CheckoutController
Dim shoppingCartId As String
Dim customerId As String
Dim selectedDeliveryOption As SelectedDeliveryOption
Dim productValidator As IProductValidator
Dim searchEngine As ISearchEngine
Dim dataLevel As ShoppingCartDataLevel
Dim returnValue As ShoppingCart

returnValue = instance.SetOrderDeliveryOption(shoppingCartId, _
    customerId, selectedDeliveryOption, _
    productValidator, searchEngine, _
    dataLevel)
```

``` csharp
public virtual ShoppingCart SetOrderDeliveryOption(
    string shoppingCartId,
    string customerId,
    SelectedDeliveryOption selectedDeliveryOption,
    IProductValidator productValidator,
    ISearchEngine searchEngine,
    ShoppingCartDataLevel dataLevel
)
```

``` c++
public:
virtual ShoppingCart^ SetOrderDeliveryOption(
    String^ shoppingCartId, 
    String^ customerId, 
    SelectedDeliveryOption^ selectedDeliveryOption, 
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

  - selectedDeliveryOption  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SelectedDeliveryOption](selecteddeliveryoption-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

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

