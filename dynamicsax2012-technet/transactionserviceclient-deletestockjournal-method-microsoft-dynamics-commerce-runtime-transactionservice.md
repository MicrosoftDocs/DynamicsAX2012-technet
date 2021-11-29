---
title: TransactionServiceClient.DeleteStockJournal Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: DeleteStockJournal Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.DeleteStockJournal(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.deletestockjournal(v=AX.60)
ms:contentKeyID: 62210507
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.DeleteStockJournal
dev_langs:
- CSharp
- C++
- VB
---

# DeleteStockJournal Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Deletes stock count journal record and transactions from AX of the specified journalId.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub DeleteStockJournal ( _
    journalId As String _
)
'Usage
Dim instance As TransactionServiceClient
Dim journalId As String

instance.DeleteStockJournal(journalId)
```

``` csharp
public void DeleteStockJournal(
    string journalId
)
```

``` c++
public:
void DeleteStockJournal(
    String^ journalId
)
```

#### Parameters

  - journalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

