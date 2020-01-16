---
title: TransactionServiceClient.IssueGiftCard Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: IssueGiftCard Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.IssueGiftCard(System.String,System.Decimal,System.String,System.Int64,System.String,System.String,System.String,System.String,System.String@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.issuegiftcard(v=AX.60)
ms:contentKeyID: 62203940
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.IssueGiftCard
dev_langs:
- CSharp
- C++
- VB
---

# IssueGiftCard Method

Issue new gift card.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub IssueGiftCard ( _
    requestedGiftCardId As String, _
    amount As Decimal, _
    depositCurrencyCode As String, _
    channelId As Long, _
    terminalId As String, _
    staffId As String, _
    transactionId As String, _
    receiptId As String, _
    <OutAttribute> ByRef newGiftCardId As String _
)
'Usage
Dim instance As TransactionServiceClient
Dim requestedGiftCardId As String
Dim amount As Decimal
Dim depositCurrencyCode As String
Dim channelId As Long
Dim terminalId As String
Dim staffId As String
Dim transactionId As String
Dim receiptId As String
Dim newGiftCardId As String

instance.IssueGiftCard(requestedGiftCardId, _
    amount, depositCurrencyCode, channelId, _
    terminalId, staffId, transactionId, _
    receiptId, newGiftCardId)
```

``` csharp
public void IssueGiftCard(
    string requestedGiftCardId,
    decimal amount,
    string depositCurrencyCode,
    long channelId,
    string terminalId,
    string staffId,
    string transactionId,
    string receiptId,
    out string newGiftCardId
)
```

``` c++
public:
void IssueGiftCard(
    String^ requestedGiftCardId, 
    Decimal amount, 
    String^ depositCurrencyCode, 
    long long channelId, 
    String^ terminalId, 
    String^ staffId, 
    String^ transactionId, 
    String^ receiptId, 
    [OutAttribute] String^% newGiftCardId
)
```

#### Parameters

  - requestedGiftCardId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - depositCurrencyCode  
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

  - newGiftCardId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

