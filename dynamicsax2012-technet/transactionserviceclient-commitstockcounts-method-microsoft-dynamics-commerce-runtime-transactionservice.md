---
title: TransactionServiceClient.CommitStockCounts Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: CommitStockCounts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.CommitStockCounts(Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.commitstockcounts(v=AX.60)
ms:contentKeyID: 62213924
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.CommitStockCounts
dev_langs:
- CSharp
- C++
- VB
---

# CommitStockCounts Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Commits the Stock count journals and transactions to AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function CommitStockCounts ( _
    stockCountJournal As StockCountJournal _
) As StockCountJournal
'Usage
Dim instance As TransactionServiceClient
Dim stockCountJournal As StockCountJournal
Dim returnValue As StockCountJournal

returnValue = instance.CommitStockCounts(stockCountJournal)
```

``` csharp
public StockCountJournal CommitStockCounts(
    StockCountJournal stockCountJournal
)
```

``` c++
public:
StockCountJournal^ CommitStockCounts(
    StockCountJournal^ stockCountJournal
)
```

#### Parameters

  - stockCountJournal  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns the stockcount journal created.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

