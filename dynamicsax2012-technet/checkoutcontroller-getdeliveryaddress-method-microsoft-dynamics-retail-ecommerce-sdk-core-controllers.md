---
title: CheckoutController.GetDeliveryAddress Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetDeliveryAddress Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.GetDeliveryAddress(Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SelectedDeliveryOption)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.checkoutcontroller.getdeliveryaddress(v=AX.60)
ms:contentKeyID: 65317892
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.GetDeliveryAddress
dev_langs:
- CSharp
- C++
- VB
---

# GetDeliveryAddress Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function GetDeliveryAddress ( _
    selectedDeliveryOption As SelectedDeliveryOption _
) As Address
'Usage
Dim selectedDeliveryOption As SelectedDeliveryOption
Dim returnValue As Address

returnValue = Me.GetDeliveryAddress(selectedDeliveryOption)
```

``` csharp
protected virtual Address GetDeliveryAddress(
    SelectedDeliveryOption selectedDeliveryOption
)
```

``` c++
protected:
virtual Address^ GetDeliveryAddress(
    SelectedDeliveryOption^ selectedDeliveryOption
)
```

#### Parameters

  - selectedDeliveryOption  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SelectedDeliveryOption](selecteddeliveryoption-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

#### Return Value

Type: Address  

## See Also

#### Reference

[CheckoutController Class](checkoutcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

