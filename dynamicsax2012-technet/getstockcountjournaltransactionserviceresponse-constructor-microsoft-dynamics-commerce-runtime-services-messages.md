---
title: GetStockCountJournalTransactionServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetStockCountJournalTransactionServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStockCountJournalTransactionServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getstockcountjournaltransactionserviceresponse.getstockcountjournaltransactionserviceresponse(v=AX.60)
ms:contentKeyID: 62205156
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStockCountJournalTransactionServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetStockCountJournalTransactionServiceResponse Constructor

Initializes a new instance of the [GetStockCountJournalTransactionServiceResponse](getstockcountjournaltransactionserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    journalTransactions As IEnumerable(Of StockCountJournalTransaction) _
)
'Usage
Dim journalTransactions As IEnumerable(Of StockCountJournalTransaction)

Dim instance As New GetStockCountJournalTransactionServiceResponse(journalTransactions)
```

``` csharp
public GetStockCountJournalTransactionServiceResponse(
    IEnumerable<StockCountJournalTransaction> journalTransactions
)
```

``` c++
public:
GetStockCountJournalTransactionServiceResponse(
    IEnumerable<StockCountJournalTransaction^>^ journalTransactions
)
```

#### Parameters

  - journalTransactions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[StockCountJournalTransaction](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetStockCountJournalTransactionServiceResponse Class](getstockcountjournaltransactionserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

