---
title: OrderManager.RecallSalesInvoice Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: RecallSalesInvoice Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.RecallSalesInvoice(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.ordermanager.recallsalesinvoice(v=AX.60)
ms:contentKeyID: 65322046
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.RecallSalesInvoice
dev_langs:
- CSharp
- C++
- VB
---

# RecallSalesInvoice Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function RecallSalesInvoice ( _
    transactionId As String, _
    invoiceId As String _
) As Cart
'Usage
Dim instance As OrderManager
Dim transactionId As String
Dim invoiceId As String
Dim returnValue As Cart

returnValue = instance.RecallSalesInvoice(transactionId, _
    invoiceId)
```

``` csharp
public Cart RecallSalesInvoice(
    string transactionId,
    string invoiceId
)
```

``` c++
public:
Cart^ RecallSalesInvoice(
    String^ transactionId, 
    String^ invoiceId
)
```

#### Parameters

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - invoiceId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

