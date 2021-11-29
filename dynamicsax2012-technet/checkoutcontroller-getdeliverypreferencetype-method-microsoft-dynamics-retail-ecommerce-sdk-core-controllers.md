---
title: CheckoutController.GetDeliveryPreferenceType Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetDeliveryPreferenceType Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.GetDeliveryPreferenceType(Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SelectedDeliveryOption)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.checkoutcontroller.getdeliverypreferencetype(v=AX.60)
ms:contentKeyID: 65318269
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.GetDeliveryPreferenceType
dev_langs:
- CSharp
- C++
- VB
---

# GetDeliveryPreferenceType Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function GetDeliveryPreferenceType ( _
    selectedDeliveryOptions As SelectedDeliveryOption _
) As DeliveryPreferenceType
'Usage
Dim selectedDeliveryOptions As SelectedDeliveryOption
Dim returnValue As DeliveryPreferenceType

returnValue = Me.GetDeliveryPreferenceType(selectedDeliveryOptions)
```

``` csharp
protected virtual DeliveryPreferenceType GetDeliveryPreferenceType(
    SelectedDeliveryOption selectedDeliveryOptions
)
```

``` c++
protected:
virtual DeliveryPreferenceType GetDeliveryPreferenceType(
    SelectedDeliveryOption^ selectedDeliveryOptions
)
```

#### Parameters

  - selectedDeliveryOptions  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.SelectedDeliveryOption](selecteddeliveryoption-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

#### Return Value

Type: DeliveryPreferenceType  

## See Also

#### Reference

[CheckoutController Class](checkoutcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

