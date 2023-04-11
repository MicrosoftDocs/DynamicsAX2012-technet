---
title: OrderManager.UpdateCartLoyaltyCardId Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: UpdateCartLoyaltyCardId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.UpdateCartLoyaltyCardId(System.String,System.String,System.String,System.Nullable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.updatecartloyaltycardid(v=AX.60)
ms:contentKeyID: 62211333
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.UpdateCartLoyaltyCardId
dev_langs:
- CSharp
- C++
- VB
---

# UpdateCartLoyaltyCardId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Updates the loyalty card number in the cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function UpdateCartLoyaltyCardId ( _
    cartId As String, _
    customerAccountNumber As String, _
    loyaltyCardId As String, _
    modes As Nullable(Of CalculationModes) _
) As Cart
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim customerAccountNumber As String
Dim loyaltyCardId As String
Dim modes As Nullable(Of CalculationModes)
Dim returnValue As Cart

returnValue = instance.UpdateCartLoyaltyCardId(cartId, _
    customerAccountNumber, loyaltyCardId, _
    modes)
```

``` csharp
public Cart UpdateCartLoyaltyCardId(
    string cartId,
    string customerAccountNumber,
    string loyaltyCardId,
    Nullable<CalculationModes> modes
)
```

``` c++
public:
Cart^ UpdateCartLoyaltyCardId(
    String^ cartId, 
    String^ customerAccountNumber, 
    String^ loyaltyCardId, 
    Nullable<CalculationModes> modes
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - loyaltyCardId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - modes  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[CalculationModes](calculationmodes-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The updated cart.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

