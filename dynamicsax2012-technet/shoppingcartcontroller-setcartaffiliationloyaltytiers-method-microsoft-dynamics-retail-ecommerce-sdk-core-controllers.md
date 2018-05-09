---
title: ShoppingCartController.SetCartAffiliationLoyaltyTiers Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: SetCartAffiliationLoyaltyTiers Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.ShoppingCartController.SetCartAffiliationLoyaltyTiers(System.String,System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.shoppingcartcontroller.setcartaffiliationloyaltytiers(v=AX.60)
ms:contentKeyID: 65315790
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.ShoppingCartController.SetCartAffiliationLoyaltyTiers
dev_langs:
- CSharp
- C++
- VB
---

# SetCartAffiliationLoyaltyTiers Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Sub SetCartAffiliationLoyaltyTiers ( _
    cartId As String, _
    affiliationLoyaltyTierIds As IEnumerable(Of Long) _
)
'Usage
Dim instance As ShoppingCartController
Dim cartId As String
Dim affiliationLoyaltyTierIds As IEnumerable(Of Long)

instance.SetCartAffiliationLoyaltyTiers(cartId, _
    affiliationLoyaltyTierIds)
```

``` csharp
public virtual void SetCartAffiliationLoyaltyTiers(
    string cartId,
    IEnumerable<long> affiliationLoyaltyTierIds
)
```

``` c++
public:
virtual void SetCartAffiliationLoyaltyTiers(
    String^ cartId, 
    IEnumerable<long long>^ affiliationLoyaltyTierIds
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - affiliationLoyaltyTierIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[ShoppingCartController Class](shoppingcartcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

