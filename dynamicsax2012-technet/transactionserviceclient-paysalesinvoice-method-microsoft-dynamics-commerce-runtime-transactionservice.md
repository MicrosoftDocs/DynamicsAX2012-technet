---
title: TransactionServiceClient.PaySalesInvoice Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: PaySalesInvoice Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.PaySalesInvoice(System.String,System.Decimal,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.paysalesinvoice(v=AX.60)
ms:contentKeyID: 62214669
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.PaySalesInvoice
dev_langs:
- CSharp
- C++
- VB
---

# PaySalesInvoice Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Settle payment against an existing open sales invoice.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function PaySalesInvoice ( _
    invoiceId As String, _
    paymentAmount As Decimal, _
    terminalId As String, _
    storeId As String, _
    transactionId As String _
) As ReadOnlyCollection(Of Object)
'Usage
Dim instance As TransactionServiceClient
Dim invoiceId As String
Dim paymentAmount As Decimal
Dim terminalId As String
Dim storeId As String
Dim transactionId As String
Dim returnValue As ReadOnlyCollection(Of Object)

returnValue = instance.PaySalesInvoice(invoiceId, _
    paymentAmount, terminalId, storeId, _
    transactionId)
```

``` csharp
public ReadOnlyCollection<Object> PaySalesInvoice(
    string invoiceId,
    decimal paymentAmount,
    string terminalId,
    string storeId,
    string transactionId
)
```

``` c++
public:
ReadOnlyCollection<Object^>^ PaySalesInvoice(
    String^ invoiceId, 
    Decimal paymentAmount, 
    String^ terminalId, 
    String^ storeId, 
    String^ transactionId
)
```

#### Parameters

  - invoiceId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - paymentAmount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - storeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\>  
The collection results from the transaction service call.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

