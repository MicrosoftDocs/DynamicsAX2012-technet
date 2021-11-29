---
title: TransactionServiceClient.VoidGiftCardPayment Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: VoidGiftCardPayment Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.VoidGiftCardPayment(System.String,System.Int64,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.voidgiftcardpayment(v=AX.60)
ms:contentKeyID: 62208358
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.VoidGiftCardPayment
dev_langs:
- CSharp
- C++
- VB
---

# VoidGiftCardPayment Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Void gift card payment.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub VoidGiftCardPayment ( _
    giftCardId As String, _
    channelId As Long, _
    terminalId As String _
)
'Usage
Dim instance As TransactionServiceClient
Dim giftCardId As String
Dim channelId As Long
Dim terminalId As String

instance.VoidGiftCardPayment(giftCardId, _
    channelId, terminalId)
```

``` csharp
public void VoidGiftCardPayment(
    string giftCardId,
    long channelId,
    string terminalId
)
```

``` c++
public:
void VoidGiftCardPayment(
    String^ giftCardId, 
    long long channelId, 
    String^ terminalId
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

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

