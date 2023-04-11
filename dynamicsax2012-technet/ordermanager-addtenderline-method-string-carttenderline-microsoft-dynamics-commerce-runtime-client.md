---
title: OrderManager.AddTenderLine Method (String, CartTenderLine) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: AddTenderLine Method (String, CartTenderLine)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.AddTenderLine(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.CartTenderLine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.addtenderline(v=AX.60)
ms:contentKeyID: 62208559
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# AddTenderLine Method (String, CartTenderLine)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Adds the specified tender line to the cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function AddTenderLine ( _
    cartId As String, _
    tenderLine As CartTenderLine _
) As Cart
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim tenderLine As CartTenderLine
Dim returnValue As Cart

returnValue = instance.AddTenderLine(cartId, _
    tenderLine)
```

``` csharp
public Cart AddTenderLine(
    string cartId,
    CartTenderLine tenderLine
)
```

``` c++
public:
Cart^ AddTenderLine(
    String^ cartId, 
    CartTenderLine^ tenderLine
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - tenderLine  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CartTenderLine](carttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The updated cart.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[AddTenderLine Overload](ordermanager-addtenderline-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

