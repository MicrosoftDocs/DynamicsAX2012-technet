---
title: ShoppingCartController.GetCartAffiliationLoyaltyTiers Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetCartAffiliationLoyaltyTiers Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.ShoppingCartController.GetCartAffiliationLoyaltyTiers(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.shoppingcartcontroller.getcartaffiliationloyaltytiers(v=AX.60)
ms:contentKeyID: 65318240
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.ShoppingCartController.GetCartAffiliationLoyaltyTiers
dev_langs:
- CSharp
- C++
- VB
---

# GetCartAffiliationLoyaltyTiers Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetCartAffiliationLoyaltyTiers ( _
    cartId As String _
) As IEnumerable(Of Long)
'Usage
Dim instance As ShoppingCartController
Dim cartId As String
Dim returnValue As IEnumerable(Of Long)

returnValue = instance.GetCartAffiliationLoyaltyTiers(cartId)
```

``` csharp
public virtual IEnumerable<long> GetCartAffiliationLoyaltyTiers(
    string cartId
)
```

``` c++
public:
virtual IEnumerable<long long>^ GetCartAffiliationLoyaltyTiers(
    String^ cartId
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[ShoppingCartController Class](shoppingcartcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

