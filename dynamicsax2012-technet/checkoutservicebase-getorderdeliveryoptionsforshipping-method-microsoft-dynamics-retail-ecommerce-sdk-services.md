---
title: CheckoutServiceBase.GetOrderDeliveryOptionsForShipping Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetOrderDeliveryOptionsForShipping Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CheckoutServiceBase.GetOrderDeliveryOptionsForShipping(Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Address)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.checkoutservicebase.getorderdeliveryoptionsforshipping(v=AX.60)
ms:contentKeyID: 65317087
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.CheckoutServiceBase.GetOrderDeliveryOptionsForShipping
dev_langs:
- CSharp
- C++
- VB
---

# GetOrderDeliveryOptionsForShipping Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetOrderDeliveryOptionsForShipping ( _
    shipToAddress As Address _
) As DeliveryOptionsResponse
'Usage
Dim instance As CheckoutServiceBase
Dim shipToAddress As Address
Dim returnValue As DeliveryOptionsResponse

returnValue = instance.GetOrderDeliveryOptionsForShipping(shipToAddress)
```

``` csharp
public virtual DeliveryOptionsResponse GetOrderDeliveryOptionsForShipping(
    Address shipToAddress
)
```

``` c++
public:
virtual DeliveryOptionsResponse^ GetOrderDeliveryOptionsForShipping(
    Address^ shipToAddress
)
```

#### Parameters

  - shipToAddress  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Address](address-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.DeliveryOptionsResponse](deliveryoptionsresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[ICheckoutService.GetOrderDeliveryOptionsForShipping(Address)](icheckoutservice-getorderdeliveryoptionsforshipping-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[CheckoutServiceBase Class](checkoutservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

