---
title: OrderManager.RemoveDiscountCodesFromCart Method (String, IEnumerable(String)) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: RemoveDiscountCodesFromCart Method (String, IEnumerable(String))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.RemoveDiscountCodesFromCart(System.String,System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.ordermanager.removediscountcodesfromcart(v=AX.60)
ms:contentKeyID: 65319509
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# RemoveDiscountCodesFromCart Method (String, IEnumerable(String))

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function RemoveDiscountCodesFromCart ( _
    cartId As String, _
    discountCodes As IEnumerable(Of String) _
) As Cart
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim discountCodes As IEnumerable(Of String)
Dim returnValue As Cart

returnValue = instance.RemoveDiscountCodesFromCart(cartId, _
    discountCodes)
```

``` csharp
public Cart RemoveDiscountCodesFromCart(
    string cartId,
    IEnumerable<string> discountCodes
)
```

``` c++
public:
Cart^ RemoveDiscountCodesFromCart(
    String^ cartId, 
    IEnumerable<String^>^ discountCodes
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - discountCodes  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[RemoveDiscountCodesFromCart Overload](ordermanager-removediscountcodesfromcart-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

