---
title: CheckoutController.GetOrderDeliveryOptionsForShipping Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetOrderDeliveryOptionsForShipping Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.GetOrderDeliveryOptionsForShipping(System.String,System.String,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Address)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.checkoutcontroller.getorderdeliveryoptionsforshipping(v=AX.60)
ms:contentKeyID: 65318782
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.GetOrderDeliveryOptionsForShipping
dev_langs:
- CSharp
- C++
- VB
---

# GetOrderDeliveryOptionsForShipping Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetOrderDeliveryOptionsForShipping ( _
    shoppingCartId As String, _
    customerId As String, _
    shipToaddress As Address _
) As Collection(Of DeliveryOption)
'Usage
Dim instance As CheckoutController
Dim shoppingCartId As String
Dim customerId As String
Dim shipToaddress As Address
Dim returnValue As Collection(Of DeliveryOption)

returnValue = instance.GetOrderDeliveryOptionsForShipping(shoppingCartId, _
    customerId, shipToaddress)
```

``` csharp
public virtual Collection<DeliveryOption> GetOrderDeliveryOptionsForShipping(
    string shoppingCartId,
    string customerId,
    Address shipToaddress
)
```

``` c++
public:
virtual Collection<DeliveryOption^>^ GetOrderDeliveryOptionsForShipping(
    String^ shoppingCartId, 
    String^ customerId, 
    Address^ shipToaddress
)
```

#### Parameters

  - shoppingCartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - shipToaddress  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Address](address-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

#### Return Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[DeliveryOption](deliveryoption-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[CheckoutController Class](checkoutcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

