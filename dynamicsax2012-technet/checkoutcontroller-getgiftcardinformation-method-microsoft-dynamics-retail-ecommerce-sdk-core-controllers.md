---
title: CheckoutController.GetGiftCardInformation Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetGiftCardInformation Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.GetGiftCardInformation(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.checkoutcontroller.getgiftcardinformation(v=AX.60)
ms:contentKeyID: 65315861
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.GetGiftCardInformation
dev_langs:
- CSharp
- C++
- VB
---

# GetGiftCardInformation Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetGiftCardInformation ( _
    giftCardNumber As String _
) As GiftCardInformation
'Usage
Dim instance As CheckoutController
Dim giftCardNumber As String
Dim returnValue As GiftCardInformation

returnValue = instance.GetGiftCardInformation(giftCardNumber)
```

``` csharp
public virtual GiftCardInformation GetGiftCardInformation(
    string giftCardNumber
)
```

``` c++
public:
virtual GiftCardInformation^ GetGiftCardInformation(
    String^ giftCardNumber
)
```

#### Parameters

  - giftCardNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.GiftCardInformation](giftcardinformation-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[CheckoutController Class](checkoutcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

