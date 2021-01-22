---
title: CheckoutController.GetPaymentCardTypes Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetPaymentCardTypes Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.GetPaymentCardTypes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.checkoutcontroller.getpaymentcardtypes(v=AX.60)
ms:contentKeyID: 65316655
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.GetPaymentCardTypes
dev_langs:
- CSharp
- C++
- VB
---

# GetPaymentCardTypes Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetPaymentCardTypes As Collection(Of PaymentCardType)
'Usage
Dim instance As CheckoutController
Dim returnValue As Collection(Of PaymentCardType)

returnValue = instance.GetPaymentCardTypes()
```

``` csharp
public virtual Collection<PaymentCardType> GetPaymentCardTypes()
```

``` c++
public:
virtual Collection<PaymentCardType^>^ GetPaymentCardTypes()
```

#### Return Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[PaymentCardType](paymentcardtype-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[CheckoutController Class](checkoutcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

