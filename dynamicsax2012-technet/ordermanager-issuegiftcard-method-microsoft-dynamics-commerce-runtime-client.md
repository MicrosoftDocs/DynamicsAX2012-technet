---
title: OrderManager.IssueGiftCard Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: IssueGiftCard Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.IssueGiftCard(System.String,System.String,System.Decimal,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.issuegiftcard(v=AX.60)
ms:contentKeyID: 65320173
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.IssueGiftCard
dev_langs:
- CSharp
- C++
- VB
---

# IssueGiftCard Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function IssueGiftCard ( _
    cartId As String, _
    giftCartId As String, _
    amount As Decimal, _
    currencyCode As String, _
    cartLineDescription As String _
) As Cart
'Usage
Dim instance As OrderManager
Dim cartId As String
Dim giftCartId As String
Dim amount As Decimal
Dim currencyCode As String
Dim cartLineDescription As String
Dim returnValue As Cart

returnValue = instance.IssueGiftCard(cartId, _
    giftCartId, amount, currencyCode, _
    cartLineDescription)
```

``` csharp
public Cart IssueGiftCard(
    string cartId,
    string giftCartId,
    decimal amount,
    string currencyCode,
    string cartLineDescription
)
```

``` c++
public:
Cart^ IssueGiftCard(
    String^ cartId, 
    String^ giftCartId, 
    Decimal amount, 
    String^ currencyCode, 
    String^ cartLineDescription
)
```

#### Parameters

  - cartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - giftCartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - cartLineDescription  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

