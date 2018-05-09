---
title: OrderManager.AddReasonCodeLineToCart Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: AddReasonCodeLineToCart Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.AddReasonCodeLineToCart(System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.ordermanager.addreasoncodelinetocart(v=AX.60)
ms:contentKeyID: 62209830
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.AddReasonCodeLineToCart
dev_langs:
- CSharp
- C++
- VB
---

# AddReasonCodeLineToCart Method

Adds the reason code line to cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function AddReasonCodeLineToCart ( _
    cartId As String, _
    customerAccountNumber As String, _
    reasonCodeLine As ReasonCodeLine _
) As Cart
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim customerAccountNumber As String
Dim reasonCodeLine As ReasonCodeLine
Dim returnValue As Cart

returnValue = instance.AddReasonCodeLineToCart(cartId, _
    customerAccountNumber, reasonCodeLine)
```

``` csharp
public Cart AddReasonCodeLineToCart(
    string cartId,
    string customerAccountNumber,
    ReasonCodeLine reasonCodeLine
)
```

``` c++
public:
Cart^ AddReasonCodeLineToCart(
    String^ cartId, 
    String^ customerAccountNumber, 
    ReasonCodeLine^ reasonCodeLine
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - reasonCodeLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The updated cart.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

