---
title: TransactionServiceClient.PayGiftCard Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: PayGiftCard Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.PayGiftCard(System.String,System.Decimal,System.String,System.Int64,System.String,System.String,System.String,System.String,System.String@,System.Decimal@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.paygiftcard(v=AX.60)
ms:contentKeyID: 62208537
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.PayGiftCard
dev_langs:
- CSharp
- C++
- VB
---

# PayGiftCard Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Charge and unlock gift card.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub PayGiftCard ( _
    giftCardId As String, _
    amount As Decimal, _
    paymentCurrencyCode As String, _
    channelId As Long, _
    terminalId As String, _
    staffId As String, _
    transactionId As String, _
    receiptId As String, _
    <OutAttribute> ByRef cardCurrencyCode As String, _
    <OutAttribute> ByRef balance As Decimal _
)
'Usage
Dim instance As TransactionServiceClient
Dim giftCardId As String
Dim amount As Decimal
Dim paymentCurrencyCode As String
Dim channelId As Long
Dim terminalId As String
Dim staffId As String
Dim transactionId As String
Dim receiptId As String
Dim cardCurrencyCode As String
Dim balance As Decimal

instance.PayGiftCard(giftCardId, amount, _
    paymentCurrencyCode, channelId, _
    terminalId, staffId, transactionId, _
    receiptId, cardCurrencyCode, balance)
```

``` csharp
public void PayGiftCard(
    string giftCardId,
    decimal amount,
    string paymentCurrencyCode,
    long channelId,
    string terminalId,
    string staffId,
    string transactionId,
    string receiptId,
    out string cardCurrencyCode,
    out decimal balance
)
```

``` c++
public:
void PayGiftCard(
    String^ giftCardId, 
    Decimal amount, 
    String^ paymentCurrencyCode, 
    long long channelId, 
    String^ terminalId, 
    String^ staffId, 
    String^ transactionId, 
    String^ receiptId, 
    [OutAttribute] String^% cardCurrencyCode, 
    [OutAttribute] Decimal% balance
)
```

#### Parameters

  - giftCardId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amount  
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

<!-- end list -->

  - cardCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - balance  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

