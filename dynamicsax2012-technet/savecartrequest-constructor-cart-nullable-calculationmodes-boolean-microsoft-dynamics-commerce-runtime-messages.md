---
title: SaveCartRequest Constructor (Cart, Nullable(CalculationModes), Boolean) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SaveCartRequest Constructor (Cart, Nullable(CalculationModes), Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCartRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart,System.Nullable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CalculationModes},System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savecartrequest.savecartrequest(v=AX.60)
ms:contentKeyID: 62210225
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SaveCartRequest Constructor (Cart, Nullable(CalculationModes), Boolean)

Initializes a new instance of the [SaveCartRequest](savecartrequest-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    cart As Cart, _
    calculationModes As Nullable(Of CalculationModes), _
    isGiftCardOperation As Boolean _
)
'Usage
Dim cart As Cart
Dim calculationModes As Nullable(Of CalculationModes)
Dim isGiftCardOperation As Boolean

Dim instance As New SaveCartRequest(cart, calculationModes, _
    isGiftCardOperation)
```

``` csharp
public SaveCartRequest(
    Cart cart,
    Nullable<CalculationModes> calculationModes,
    bool isGiftCardOperation
)
```

``` c++
public:
SaveCartRequest(
    Cart^ cart, 
    Nullable<CalculationModes> calculationModes, 
    bool isGiftCardOperation
)
```

#### Parameters

  - cart  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - calculationModes  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[CalculationModes](calculationmodes-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - isGiftCardOperation  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[SaveCartRequest Class](savecartrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[SaveCartRequest Overload](savecartrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

