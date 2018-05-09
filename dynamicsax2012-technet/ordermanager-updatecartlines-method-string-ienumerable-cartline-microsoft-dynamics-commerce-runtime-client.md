---
title: OrderManager.UpdateCartLines Method (String, IEnumerable(CartLine)) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: UpdateCartLines Method (String, IEnumerable(CartLine))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.UpdateCartLines(System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.ordermanager.updatecartlines(v=AX.60)
ms:contentKeyID: 62214995
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# UpdateCartLines Method (String, IEnumerable(CartLine))

Updates the specified items on the cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function UpdateCartLines ( _
    cartId As String, _
    cartLines As IEnumerable(Of CartLine) _
) As Cart
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim cartLines As IEnumerable(Of CartLine)
Dim returnValue As Cart

returnValue = instance.UpdateCartLines(cartId, _
    cartLines)
```

``` csharp
public Cart UpdateCartLines(
    string cartId,
    IEnumerable<CartLine> cartLines
)
```

``` c++
public:
Cart^ UpdateCartLines(
    String^ cartId, 
    IEnumerable<CartLine^>^ cartLines
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - cartLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[CartLine](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The updated cart.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[UpdateCartLines Overload](ordermanager-updatecartlines-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

