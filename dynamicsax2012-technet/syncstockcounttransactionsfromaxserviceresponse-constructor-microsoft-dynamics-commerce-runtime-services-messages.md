---
title: SyncStockCountTransactionsFromAxServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SyncStockCountTransactionsFromAxServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SyncStockCountTransactionsFromAxServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.syncstockcounttransactionsfromaxserviceresponse.syncstockcounttransactionsfromaxserviceresponse(v=AX.60)
ms:contentKeyID: 62212456
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SyncStockCountTransactionsFromAxServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# SyncStockCountTransactionsFromAxServiceResponse Constructor

Initializes a new instance of the [SyncStockCountTransactionsFromAxServiceResponse](syncstockcounttransactionsfromaxserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    transactions As IEnumerable(Of StockCountJournalTransaction) _
)
'Usage
Dim transactions As IEnumerable(Of StockCountJournalTransaction)

Dim instance As New SyncStockCountTransactionsFromAxServiceResponse(transactions)
```

``` csharp
public SyncStockCountTransactionsFromAxServiceResponse(
    IEnumerable<StockCountJournalTransaction> transactions
)
```

``` c++
public:
SyncStockCountTransactionsFromAxServiceResponse(
    IEnumerable<StockCountJournalTransaction^>^ transactions
)
```

#### Parameters

  - transactions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[StockCountJournalTransaction](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[SyncStockCountTransactionsFromAxServiceResponse Class](syncstockcounttransactionsfromaxserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

