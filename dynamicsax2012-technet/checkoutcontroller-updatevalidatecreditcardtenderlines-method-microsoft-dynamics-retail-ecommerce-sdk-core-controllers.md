---
title: CheckoutController.UpdateValidateCreditCardTenderLines Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: UpdateValidateCreditCardTenderLines Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.UpdateValidateCreditCardTenderLines(System.Decimal,System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CartTenderLine})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.checkoutcontroller.updatevalidatecreditcardtenderlines(v=AX.60)
ms:contentKeyID: 65318397
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.UpdateValidateCreditCardTenderLines
dev_langs:
- CSharp
- C++
- VB
---

# UpdateValidateCreditCardTenderLines Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Sub UpdateValidateCreditCardTenderLines ( _
    cartTotalAmount As Decimal, _
    checkoutCartId As String, _
    cartTenderLines As IEnumerable(Of CartTenderLine) _
)
'Usage
Dim cartTotalAmount As Decimal
Dim checkoutCartId As String
Dim cartTenderLines As IEnumerable(Of CartTenderLine)

Me.UpdateValidateCreditCardTenderLines(cartTotalAmount, _
    checkoutCartId, cartTenderLines)
```

``` csharp
protected virtual void UpdateValidateCreditCardTenderLines(
    decimal cartTotalAmount,
    string checkoutCartId,
    IEnumerable<CartTenderLine> cartTenderLines
)
```

``` c++
protected:
virtual void UpdateValidateCreditCardTenderLines(
    Decimal cartTotalAmount, 
    String^ checkoutCartId, 
    IEnumerable<CartTenderLine^>^ cartTenderLines
)
```

#### Parameters

  - cartTotalAmount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - checkoutCartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - cartTenderLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<CartTenderLine\>  

## See Also

#### Reference

[CheckoutController Class](checkoutcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

