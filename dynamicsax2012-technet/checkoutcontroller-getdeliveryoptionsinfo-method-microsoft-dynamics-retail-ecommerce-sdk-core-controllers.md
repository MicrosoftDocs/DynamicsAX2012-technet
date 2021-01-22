---
title: CheckoutController.GetDeliveryOptionsInfo Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetDeliveryOptionsInfo Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.GetDeliveryOptionsInfo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.checkoutcontroller.getdeliveryoptionsinfo(v=AX.60)
ms:contentKeyID: 65316294
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.GetDeliveryOptionsInfo
dev_langs:
- CSharp
- C++
- VB
---

# GetDeliveryOptionsInfo Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetDeliveryOptionsInfo As Collection(Of DeliveryOption)
'Usage
Dim instance As CheckoutController
Dim returnValue As Collection(Of DeliveryOption)

returnValue = instance.GetDeliveryOptionsInfo()
```

``` csharp
public virtual Collection<DeliveryOption> GetDeliveryOptionsInfo()
```

``` c++
public:
virtual Collection<DeliveryOption^>^ GetDeliveryOptionsInfo()
```

#### Return Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[DeliveryOption](deliveryoption-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[CheckoutController Class](checkoutcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

