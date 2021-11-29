---
title: OrderManager.RecallCustomerQuote Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: RecallCustomerQuote Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.RecallCustomerQuote(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.recallcustomerquote(v=AX.60)
ms:contentKeyID: 65322151
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.RecallCustomerQuote
dev_langs:
- CSharp
- C++
- VB
---

# RecallCustomerQuote Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function RecallCustomerQuote ( _
    transactionId As String, _
    id As String _
) As Cart
'Usage
Dim instance As OrderManager
Dim transactionId As String
Dim id As String
Dim returnValue As Cart

returnValue = instance.RecallCustomerQuote(transactionId, _
    id)
```

``` csharp
public Cart RecallCustomerQuote(
    string transactionId,
    string id
)
```

``` c++
public:
Cart^ RecallCustomerQuote(
    String^ transactionId, 
    String^ id
)
```

#### Parameters

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - id  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

