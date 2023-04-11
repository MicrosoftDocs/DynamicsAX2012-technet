---
title: TransactionServiceClient.UnlockCreditMemo Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: UnlockCreditMemo Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.UnlockCreditMemo(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.unlockcreditmemo(v=AX.60)
ms:contentKeyID: 62202094
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.UnlockCreditMemo
dev_langs:
- CSharp
- C++
- VB
---

# UnlockCreditMemo Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Unlock credit memo.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub UnlockCreditMemo ( _
    creditMemoId As String, _
    storeId As String, _
    terminalId As String _
)
'Usage
Dim instance As TransactionServiceClient
Dim creditMemoId As String
Dim storeId As String
Dim terminalId As String

instance.UnlockCreditMemo(creditMemoId, _
    storeId, terminalId)
```

``` csharp
public void UnlockCreditMemo(
    string creditMemoId,
    string storeId,
    string terminalId
)
```

``` c++
public:
void UnlockCreditMemo(
    String^ creditMemoId, 
    String^ storeId, 
    String^ terminalId
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

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

