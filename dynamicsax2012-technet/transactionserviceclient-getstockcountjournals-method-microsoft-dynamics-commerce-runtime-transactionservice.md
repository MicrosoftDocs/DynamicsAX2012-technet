---
title: TransactionServiceClient.GetStockCountJournals Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetStockCountJournals Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetStockCountJournals(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getstockcountjournals(v=AX.60)
ms:contentKeyID: 62206294
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetStockCountJournals
dev_langs:
- CSharp
- C++
- VB
---

# GetStockCountJournals Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Retrieves the Stock Count Journals from AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function GetStockCountJournals ( _
    inventLocationId As String _
) As ReadOnlyCollection(Of StockCountJournal)
'Usage
Dim instance As TransactionServiceClient
Dim inventLocationId As String
Dim returnValue As ReadOnlyCollection(Of StockCountJournal)

returnValue = instance.GetStockCountJournals(inventLocationId)
```

``` csharp
public ReadOnlyCollection<StockCountJournal> GetStockCountJournals(
    string inventLocationId
)
```

``` c++
public:
ReadOnlyCollection<StockCountJournal^>^ GetStockCountJournals(
    String^ inventLocationId
)
```

#### Parameters

  - inventLocationId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns the StockCountJournal list from AX.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

