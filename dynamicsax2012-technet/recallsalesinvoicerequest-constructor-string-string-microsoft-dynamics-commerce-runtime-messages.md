---
title: RecallSalesInvoiceRequest Constructor (String, String) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: RecallSalesInvoiceRequest Constructor (String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.RecallSalesInvoiceRequest.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.recallsalesinvoicerequest.recallsalesinvoicerequest(v=AX.60)
ms:contentKeyID: 65320116
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# RecallSalesInvoiceRequest Constructor (String, String)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    transactionId As String, _
    invoiceId As String _
)
'Usage
Dim transactionId As String
Dim invoiceId As String

Dim instance As New RecallSalesInvoiceRequest(transactionId, _
    invoiceId)
```

``` csharp
public RecallSalesInvoiceRequest(
    string transactionId,
    string invoiceId
)
```

``` c++
public:
RecallSalesInvoiceRequest(
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

## See Also

#### Reference

[RecallSalesInvoiceRequest Class](recallsalesinvoicerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[RecallSalesInvoiceRequest Overload](recallsalesinvoicerequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

