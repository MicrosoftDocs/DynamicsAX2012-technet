---
title: CommitStockCountTransactionsServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CommitStockCountTransactionsServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CommitStockCountTransactionsServiceRequest.#ctor(System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.commitstockcounttransactionsservicerequest.commitstockcounttransactionsservicerequest(v=AX.60)
ms:contentKeyID: 65321409
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CommitStockCountTransactionsServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# CommitStockCountTransactionsServiceRequest Constructor

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

Dim instance As New CommitStockCountTransactionsServiceRequest(journalId, _
    stockCountJournalTransactions)
```

``` csharp
public CommitStockCountTransactionsServiceRequest(
    string journalId,
    IEnumerable<StockCountJournalTransaction> stockCountJournalTransactions
)
```

``` c++
public:
CommitStockCountTransactionsServiceRequest(
    String^ journalId, 
    IEnumerable<StockCountJournalTransaction^>^ stockCountJournalTransactions
)
```

#### Parameters

  - journalId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - stockCountJournalTransactions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[StockCountJournalTransaction](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CommitStockCountTransactionsServiceRequest Class](commitstockcounttransactionsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

