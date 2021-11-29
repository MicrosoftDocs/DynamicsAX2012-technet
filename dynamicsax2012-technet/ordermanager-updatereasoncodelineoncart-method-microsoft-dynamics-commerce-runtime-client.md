---
title: OrderManager.UpdateReasonCodeLineOnCart Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: UpdateReasonCodeLineOnCart Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.UpdateReasonCodeLineOnCart(System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.updatereasoncodelineoncart(v=AX.60)
ms:contentKeyID: 62213763
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.UpdateReasonCodeLineOnCart
dev_langs:
- CSharp
- C++
- VB
---

# UpdateReasonCodeLineOnCart Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Updates the reason code line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function UpdateReasonCodeLineOnCart ( _
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

returnValue = instance.UpdateReasonCodeLineOnCart(cartId, _
    customerAccountNumber, reasonCodeLine)
```

``` csharp
public Cart UpdateReasonCodeLineOnCart(
    string cartId,
    string customerAccountNumber,
    ReasonCodeLine reasonCodeLine
)
```

``` c++
public:
Cart^ UpdateReasonCodeLineOnCart(
    String^ cartId, 
    String^ customerAccountNumber, 
    ReasonCodeLine^ reasonCodeLine
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

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

