---
title: ICheckoutService.SetOrderDeliveryOption Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: SetOrderDeliveryOption Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ICheckoutService.SetOrderDeliveryOption(Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SelectedDeliveryOption,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCartDataLevel)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.icheckoutservice.setorderdeliveryoption(v=AX.60)
ms:contentKeyID: 65316239
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ICheckoutService.SetOrderDeliveryOption
dev_langs:
- CSharp
- C++
- VB
---

# SetOrderDeliveryOption Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function SetOrderDeliveryOption ( _
    selectedDeliveryOption As SelectedDeliveryOption, _
    dataLevel As ShoppingCartDataLevel _
) As ShoppingCartResponse
'Usage
Dim instance As ICheckoutService
Dim selectedDeliveryOption As SelectedDeliveryOption
Dim dataLevel As ShoppingCartDataLevel
Dim returnValue As ShoppingCartResponse

returnValue = instance.SetOrderDeliveryOption(selectedDeliveryOption, _
    dataLevel)
```

``` csharp
[OperationContractAttribute]
ShoppingCartResponse SetOrderDeliveryOption(
    SelectedDeliveryOption selectedDeliveryOption,
    ShoppingCartDataLevel dataLevel
)
```

``` c++
[OperationContractAttribute]
ShoppingCartResponse^ SetOrderDeliveryOption(
    SelectedDeliveryOption^ selectedDeliveryOption, 
    ShoppingCartDataLevel dataLevel
)
```

#### Parameters

  - selectedDeliveryOption  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SelectedDeliveryOption](selecteddeliveryoption-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

<!-- end list -->

  - dataLevel  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.ShoppingCartDataLevel](shoppingcartdatalevel-enumeration-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.ShoppingCartResponse](shoppingcartresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[ICheckoutService Interface](icheckoutservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

