---
title: SaveTenderLineRequest.ValidatePaymentCard Method  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ValidatePaymentCard Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveTenderLineRequest.ValidatePaymentCard(Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savetenderlinerequest.validatepaymentcard(v=AX.60)
ms:contentKeyID: 65319080
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveTenderLineRequest.ValidatePaymentCard
dev_langs:
- CSharp
- C++
- VB
---

# ValidatePaymentCard Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ValidatePaymentCard ( _
    paymentCard As PaymentCard _
) As IEnumerable(Of DataValidationFailure)
'Usage
Dim paymentCard As PaymentCard
Dim returnValue As IEnumerable(Of DataValidationFailure)

returnValue = SaveTenderLineRequest.ValidatePaymentCard(paymentCard)
```

``` csharp
public static IEnumerable<DataValidationFailure> ValidatePaymentCard(
    PaymentCard paymentCard
)
```

``` c++
public:
static IEnumerable<DataValidationFailure^>^ ValidatePaymentCard(
    PaymentCard^ paymentCard
)
```

#### Parameters

  - paymentCard  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard](paymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[DataValidationFailure](datavalidationfailure-class-microsoft-dynamics-commerce-runtime.md)\>  

## See Also

#### Reference

[SaveTenderLineRequest Class](savetenderlinerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

