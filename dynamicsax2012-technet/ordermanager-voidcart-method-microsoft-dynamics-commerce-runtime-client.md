---
title: OrderManager.VoidCart Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: VoidCart Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.VoidCart(System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.voidcart(v=AX.60)
ms:contentKeyID: 62209677
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.VoidCart
dev_langs:
- CSharp
- C++
- VB
---

# VoidCart Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Voids the Transactions in Cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function VoidCart ( _
    cartId As String, _
    reasonCodeLines As IEnumerable(Of ReasonCodeLine) _
) As SalesOrder
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim reasonCodeLines As IEnumerable(Of ReasonCodeLine)
Dim returnValue As SalesOrder

returnValue = instance.VoidCart(cartId, _
    reasonCodeLines)
```

``` csharp
public SalesOrder VoidCart(
    string cartId,
    IEnumerable<ReasonCodeLine> reasonCodeLines
)
```

``` c++
public:
SalesOrder^ VoidCart(
    String^ cartId, 
    IEnumerable<ReasonCodeLine^>^ reasonCodeLines
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - reasonCodeLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ReasonCodeLine](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Details of the order that was successfully created from the cart.  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

