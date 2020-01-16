---
title: TransactionServiceClient.LockGiftCard Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: LockGiftCard Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.LockGiftCard(System.String,System.Int64,System.String,System.String@,System.Decimal@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.lockgiftcard(v=AX.60)
ms:contentKeyID: 62214159
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.LockGiftCard
dev_langs:
- CSharp
- C++
- VB
---

# LockGiftCard Method

Reserves the gift card so it cannot be used from different terminal.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub LockGiftCard ( _
    giftCardId As String, _
    channelId As Long, _
    terminalId As String, _
    <OutAttribute> ByRef cardCurrencyCode As String, _
    <OutAttribute> ByRef balance As Decimal _
)
'Usage
Dim instance As TransactionServiceClient
Dim giftCardId As String
Dim channelId As Long
Dim terminalId As String
Dim cardCurrencyCode As String
Dim balance As Decimal

instance.LockGiftCard(giftCardId, channelId, _
    terminalId, cardCurrencyCode, balance)
```

``` csharp
public void LockGiftCard(
    string giftCardId,
    long channelId,
    string terminalId,
    out string cardCurrencyCode,
    out decimal balance
)
```

``` c++
public:
void LockGiftCard(
    String^ giftCardId, 
    long long channelId, 
    String^ terminalId, 
    [OutAttribute] String^% cardCurrencyCode, 
    [OutAttribute] Decimal% balance
)
```

#### Parameters

  - giftCardId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - terminalId  
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

