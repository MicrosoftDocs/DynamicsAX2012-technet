---
title: PayCreditMemoRealtimeRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: PayCreditMemoRealtimeRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PayCreditMemoRealtimeRequest.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.paycreditmemorealtimerequest.paycreditmemorealtimerequest(v=AX.60)
ms:contentKeyID: 65323209
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PayCreditMemoRealtimeRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# PayCreditMemoRealtimeRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    creditMemoId As String, _
    storeId As String, _
    terminalId As String, _
    staffId As String, _
    transactionId As String, _
    receiptId As String, _
    currencyCode As String, _
    amount As Decimal _
)
'Usage
Dim creditMemoId As String
Dim storeId As String
Dim terminalId As String
Dim staffId As String
Dim transactionId As String
Dim receiptId As String
Dim currencyCode As String
Dim amount As Decimal

Dim instance As New PayCreditMemoRealtimeRequest(creditMemoId, _
    storeId, terminalId, staffId, transactionId, _
    receiptId, currencyCode, amount)
```

``` csharp
public PayCreditMemoRealtimeRequest(
    string creditMemoId,
    string storeId,
    string terminalId,
    string staffId,
    string transactionId,
    string receiptId,
    string currencyCode,
    decimal amount
)
```

``` c++
public:
PayCreditMemoRealtimeRequest(
    String^ creditMemoId, 
    String^ storeId, 
    String^ terminalId, 
    String^ staffId, 
    String^ transactionId, 
    String^ receiptId, 
    String^ currencyCode, 
    Decimal amount
)
```

#### Parameters

  - creditMemoId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - storeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - receiptId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[PayCreditMemoRealtimeRequest Class](paycreditmemorealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

