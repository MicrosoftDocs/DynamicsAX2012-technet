---
title: OrderManager.UpdateCartLines Method (String, String, IEnumerable(CartLine)) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: UpdateCartLines Method (String, String, IEnumerable(CartLine))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.UpdateCartLines(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.updatecartlines(v=AX.60)
ms:contentKeyID: 62207262
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# UpdateCartLines Method (String, String, IEnumerable(CartLine))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Updates the specified items on the cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function UpdateCartLines ( _
    cartId As String, _
    customerAccountNumber As String, _
    cartLines As IEnumerable(Of CartLine) _
) As Cart
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim customerAccountNumber As String
Dim cartLines As IEnumerable(Of CartLine)
Dim returnValue As Cart

returnValue = instance.UpdateCartLines(cartId, _
    customerAccountNumber, cartLines)
```

``` csharp
public Cart UpdateCartLines(
    string cartId,
    string customerAccountNumber,
    IEnumerable<CartLine> cartLines
)
```

``` c++
public:
Cart^ UpdateCartLines(
    String^ cartId, 
    String^ customerAccountNumber, 
    IEnumerable<CartLine^>^ cartLines
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - cartLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CartLine](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The updated cart.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[UpdateCartLines Overload](ordermanager-updatecartlines-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

