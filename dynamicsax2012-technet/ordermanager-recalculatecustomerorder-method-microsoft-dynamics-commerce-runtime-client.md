---
title: OrderManager.RecalculateCustomerOrder Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: RecalculateCustomerOrder Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.RecalculateCustomerOrder(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.ordermanager.recalculatecustomerorder(v=AX.60)
ms:contentKeyID: 62203522
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.RecalculateCustomerOrder
dev_langs:
- CSharp
- C++
- VB
---

# RecalculateCustomerOrder Method

Recalculates the prices of a customer order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function RecalculateCustomerOrder ( _
    cartId As String _
) As Cart
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim returnValue As Cart

returnValue = instance.RecalculateCustomerOrder(cartId)
```

``` csharp
public Cart RecalculateCustomerOrder(
    string cartId
)
```

``` c++
public:
Cart^ RecalculateCustomerOrder(
    String^ cartId
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The cart with values recalculated.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

