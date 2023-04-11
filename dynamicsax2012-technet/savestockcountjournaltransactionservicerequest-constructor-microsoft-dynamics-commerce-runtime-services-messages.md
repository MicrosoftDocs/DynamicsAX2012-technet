---
title: SaveStockCountJournalTransactionServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SaveStockCountJournalTransactionServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveStockCountJournalTransactionServiceRequest.#ctor(System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.savestockcountjournaltransactionservicerequest.savestockcountjournaltransactionservicerequest(v=AX.60)
ms:contentKeyID: 65320653
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveStockCountJournalTransactionServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# SaveStockCountJournalTransactionServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    journalId As String, _
    stockCountJournalTransactions As IEnumerable(Of StockCountJournalTransaction) _
)
'Usage
Dim journalId As String
Dim stockCountJournalTransactions As IEnumerable(Of StockCountJournalTransaction)

Dim instance As New SaveStockCountJournalTransactionServiceRequest(journalId, _
    stockCountJournalTransactions)
```

``` csharp
public SaveStockCountJournalTransactionServiceRequest(
    string journalId,
    IEnumerable<StockCountJournalTransaction> stockCountJournalTransactions
)
```

``` c++
public:
SaveStockCountJournalTransactionServiceRequest(
    String^ journalId, 
    IEnumerable<StockCountJournalTransaction^>^ stockCountJournalTransactions
)
```

#### Parameters

  - journalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - stockCountJournalTransactions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[StockCountJournalTransaction](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[SaveStockCountJournalTransactionServiceRequest Class](savestockcountjournaltransactionservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

