---
title: CheckoutController.ValidateGiftCardTenderLines Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: ValidateGiftCardTenderLines Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.ValidateGiftCardTenderLines(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CartTenderLine})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.checkoutcontroller.validategiftcardtenderlines(v=AX.60)
ms:contentKeyID: 65316541
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.ValidateGiftCardTenderLines
dev_langs:
- CSharp
- C++
- VB
---

# ValidateGiftCardTenderLines Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Sub ValidateGiftCardTenderLines ( _
    checkoutCartId As String, _
    channelCurrencyCode As String, _
    cartTenderLines As IEnumerable(Of CartTenderLine) _
)
'Usage
Dim checkoutCartId As String
Dim channelCurrencyCode As String
Dim cartTenderLines As IEnumerable(Of CartTenderLine)

Me.ValidateGiftCardTenderLines(checkoutCartId, _
    channelCurrencyCode, cartTenderLines)
```

``` csharp
protected virtual void ValidateGiftCardTenderLines(
    string checkoutCartId,
    string channelCurrencyCode,
    IEnumerable<CartTenderLine> cartTenderLines
)
```

``` c++
protected:
virtual void ValidateGiftCardTenderLines(
    String^ checkoutCartId, 
    String^ channelCurrencyCode, 
    IEnumerable<CartTenderLine^>^ cartTenderLines
)
```

#### Parameters

  - checkoutCartId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - channelCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - cartTenderLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<CartTenderLine\>  

## See Also

#### Reference

[CheckoutController Class](checkoutcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

