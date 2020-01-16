---
title: TransactionServiceClient.UnlockGiftCard Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: UnlockGiftCard Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.UnlockGiftCard(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.unlockgiftcard(v=AX.60)
ms:contentKeyID: 62209044
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.UnlockGiftCard
dev_langs:
- CSharp
- C++
- VB
---

# UnlockGiftCard Method

Unlocks/Releases an issued gift card so that it can now be used.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub UnlockGiftCard ( _
    giftCardId As String _
)
'Usage
Dim instance As TransactionServiceClient
Dim giftCardId As String

instance.UnlockGiftCard(giftCardId)
```

``` csharp
public void UnlockGiftCard(
    string giftCardId
)
```

``` c++
public:
void UnlockGiftCard(
    String^ giftCardId
)
```

#### Parameters

  - giftCardId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

