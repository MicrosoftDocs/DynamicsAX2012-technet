---
title: CreateUpdateStockCountJournalTransactionDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: CreateUpdateStockCountJournalTransactionDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreateUpdateStockCountJournalTransactionDataRequest.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.createupdatestockcountjournaltransactiondatarequest.createupdatestockcountjournaltransactiondatarequest(v=AX.60)
ms:contentKeyID: 65318389
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CreateUpdateStockCountJournalTransactionDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# CreateUpdateStockCountJournalTransactionDataRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [CreateUpdateStockCountJournalTransactionDataRequest](createupdatestockcountjournaltransactiondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    journalTransactions As IEnumerable(Of StockCountJournalTransaction) _
)
'Usage
Dim journalTransactions As IEnumerable(Of StockCountJournalTransaction)

Dim instance As New CreateUpdateStockCountJournalTransactionDataRequest(journalTransactions)
```

``` csharp
public CreateUpdateStockCountJournalTransactionDataRequest(
    IEnumerable<StockCountJournalTransaction> journalTransactions
)
```

``` c++
public:
CreateUpdateStockCountJournalTransactionDataRequest(
    IEnumerable<StockCountJournalTransaction^>^ journalTransactions
)
```

#### Parameters

  - journalTransactions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[StockCountJournalTransaction](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CreateUpdateStockCountJournalTransactionDataRequest Class](createupdatestockcountjournaltransactiondatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

