---
title: CreateOrderFromCartRequest Constructor (IEnumerable(CartTenderLine)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CreateOrderFromCartRequest Constructor (IEnumerable(CartTenderLine))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.CreateOrderFromCartRequest.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CartTenderLine})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.createorderfromcartrequest.createorderfromcartrequest(v=AX.60)
ms:contentKeyID: 62213340
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CreateOrderFromCartRequest Constructor (IEnumerable(CartTenderLine))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [CreateOrderFromCartRequest](createorderfromcartrequest-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    cartTenderLines As IEnumerable(Of CartTenderLine) _
)
'Usage
Dim cartTenderLines As IEnumerable(Of CartTenderLine)

Dim instance As New CreateOrderFromCartRequest(cartTenderLines)
```

``` csharp
public CreateOrderFromCartRequest(
    IEnumerable<CartTenderLine> cartTenderLines
)
```

``` c++
public:
CreateOrderFromCartRequest(
    IEnumerable<CartTenderLine^>^ cartTenderLines
)
```

#### Parameters

  - cartTenderLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CartTenderLine](carttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CreateOrderFromCartRequest Class](createorderfromcartrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[CreateOrderFromCartRequest Overload](createorderfromcartrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

