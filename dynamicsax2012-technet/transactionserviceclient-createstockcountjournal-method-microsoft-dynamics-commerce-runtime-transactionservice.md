---
title: TransactionServiceClient.CreateStockCountJournal Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: CreateStockCountJournal Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.CreateStockCountJournal(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.createstockcountjournal(v=AX.60)
ms:contentKeyID: 62213477
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.CreateStockCountJournal
dev_langs:
- CSharp
- C++
- VB
---

# CreateStockCountJournal Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Create a stock count journal.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function CreateStockCountJournal ( _
    inventoryLocationId As String, _
    description As String _
) As ReadOnlyCollection(Of StockCountJournal)
'Usage
Dim instance As TransactionServiceClient
Dim inventoryLocationId As String
Dim description As String
Dim returnValue As ReadOnlyCollection(Of StockCountJournal)

returnValue = instance.CreateStockCountJournal(inventoryLocationId, _
    description)
```

``` csharp
public ReadOnlyCollection<StockCountJournal> CreateStockCountJournal(
    string inventoryLocationId,
    string description
)
```

``` c++
public:
ReadOnlyCollection<StockCountJournal^>^ CreateStockCountJournal(
    String^ inventoryLocationId, 
    String^ description
)
```

#### Parameters

  - inventoryLocationId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - description  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns the StockCountJournal list from AX.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

