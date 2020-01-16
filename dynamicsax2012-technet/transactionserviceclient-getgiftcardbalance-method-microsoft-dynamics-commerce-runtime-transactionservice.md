---
title: TransactionServiceClient.GetGiftCardBalance Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetGiftCardBalance Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetGiftCardBalance(System.String,System.String@,System.Decimal@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getgiftcardbalance(v=AX.60)
ms:contentKeyID: 62205559
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetGiftCardBalance
dev_langs:
- CSharp
- C++
- VB
---

# GetGiftCardBalance Method

Get the gift card balance.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub GetGiftCardBalance ( _
    giftCardId As String, _
    <OutAttribute> ByRef cardCurrencyCode As String, _
    <OutAttribute> ByRef balance As Decimal _
)
'Usage
Dim instance As TransactionServiceClient
Dim giftCardId As String
Dim cardCurrencyCode As String
Dim balance As Decimal

instance.GetGiftCardBalance(giftCardId, _
    cardCurrencyCode, balance)
```

``` csharp
public void GetGiftCardBalance(
    string giftCardId,
    out string cardCurrencyCode,
    out decimal balance
)
```

``` c++
public:
void GetGiftCardBalance(
    String^ giftCardId, 
    [OutAttribute] String^% cardCurrencyCode, 
    [OutAttribute] Decimal% balance
)
```

#### Parameters

  - giftCardId  
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

