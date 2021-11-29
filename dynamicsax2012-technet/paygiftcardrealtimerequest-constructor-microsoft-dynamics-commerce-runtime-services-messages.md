---
title: PayGiftCardRealtimeRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: PayGiftCardRealtimeRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PayGiftCardRealtimeRequest.#ctor(System.String,System.Decimal,System.String,System.Int64,System.String,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.paygiftcardrealtimerequest.paygiftcardrealtimerequest(v=AX.60)
ms:contentKeyID: 65317063
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PayGiftCardRealtimeRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# PayGiftCardRealtimeRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    giftCardId As String, _
    amountInTenderedCurrency As Decimal, _
    paymentCurrencyCode As String, _
    channelId As Long, _
    terminalId As String, _
    staffId As String, _
    transactionId As String, _
    receiptId As String _
)
'Usage
Dim giftCardId As String
Dim amountInTenderedCurrency As Decimal
Dim paymentCurrencyCode As String
Dim channelId As Long
Dim terminalId As String
Dim staffId As String
Dim transactionId As String
Dim receiptId As String

Dim instance As New PayGiftCardRealtimeRequest(giftCardId, _
    amountInTenderedCurrency, paymentCurrencyCode, _
    channelId, terminalId, staffId, transactionId, _
    receiptId)
```

``` csharp
public PayGiftCardRealtimeRequest(
    string giftCardId,
    decimal amountInTenderedCurrency,
    string paymentCurrencyCode,
    long channelId,
    string terminalId,
    string staffId,
    string transactionId,
    string receiptId
)
```

``` c++
public:
PayGiftCardRealtimeRequest(
    String^ giftCardId, 
    Decimal amountInTenderedCurrency, 
    String^ paymentCurrencyCode, 
    long long channelId, 
    String^ terminalId, 
    String^ staffId, 
    String^ transactionId, 
    String^ receiptId
)
```

#### Parameters

  - giftCardId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amountInTenderedCurrency  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - paymentCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

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

## See Also

#### Reference

[PayGiftCardRealtimeRequest Class](paygiftcardrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

