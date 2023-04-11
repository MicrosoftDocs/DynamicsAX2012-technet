---
title: TransactionServiceClient.GetStockCountJournalsTransaction Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetStockCountJournalsTransaction Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetStockCountJournalsTransaction(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getstockcountjournalstransaction(v=AX.60)
ms:contentKeyID: 62214537
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetStockCountJournalsTransaction
dev_langs:
- CSharp
- C++
- VB
---

# GetStockCountJournalsTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Retrieves Stock Count journal Transactions from AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function GetStockCountJournalsTransaction ( _
    journalId As String, _
    inventLocationId As String _
) As ReadOnlyCollection(Of StockCountJournalTransaction)
'Usage
Dim instance As TransactionServiceClient
Dim journalId As String
Dim inventLocationId As String
Dim returnValue As ReadOnlyCollection(Of StockCountJournalTransaction)

returnValue = instance.GetStockCountJournalsTransaction(journalId, _
    inventLocationId)
```

``` csharp
public ReadOnlyCollection<StockCountJournalTransaction> GetStockCountJournalsTransaction(
    string journalId,
    string inventLocationId
)
```

``` c++
public:
ReadOnlyCollection<StockCountJournalTransaction^>^ GetStockCountJournalsTransaction(
    String^ journalId, 
    String^ inventLocationId
)
```

#### Parameters

  - journalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventLocationId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[StockCountJournalTransaction](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns the StockCount journal Transactions.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

