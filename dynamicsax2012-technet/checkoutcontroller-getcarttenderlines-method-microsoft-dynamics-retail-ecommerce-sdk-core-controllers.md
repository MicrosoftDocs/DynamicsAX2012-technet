---
title: CheckoutController.GetCartTenderLines Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetCartTenderLines Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.GetCartTenderLines(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.TenderDataLine},System.Decimal,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.checkoutcontroller.getcarttenderlines(v=AX.60)
ms:contentKeyID: 65316692
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.CheckoutController.GetCartTenderLines
dev_langs:
- CSharp
- C++
- VB
---

# GetCartTenderLines Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function GetCartTenderLines ( _
    tenderDataLines As IEnumerable(Of TenderDataLine), _
    cartTotalAmount As Decimal, _
    checkoutCartId As String _
) As ICollection(Of CartTenderLine)
'Usage
Dim tenderDataLines As IEnumerable(Of TenderDataLine)
Dim cartTotalAmount As Decimal
Dim checkoutCartId As String
Dim returnValue As ICollection(Of CartTenderLine)

returnValue = Me.GetCartTenderLines(tenderDataLines, _
    cartTotalAmount, checkoutCartId)
```

``` csharp
protected virtual ICollection<CartTenderLine> GetCartTenderLines(
    IEnumerable<TenderDataLine> tenderDataLines,
    decimal cartTotalAmount,
    string checkoutCartId
)
```

``` c++
protected:
virtual ICollection<CartTenderLine^>^ GetCartTenderLines(
    IEnumerable<TenderDataLine^>^ tenderDataLines, 
    Decimal cartTotalAmount, 
    String^ checkoutCartId
)
```

#### Parameters

  - tenderDataLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[TenderDataLine](tenderdataline-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

<!-- end list -->

  - cartTotalAmount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - checkoutCartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<CartTenderLine\>  

## See Also

#### Reference

[CheckoutController Class](checkoutcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

