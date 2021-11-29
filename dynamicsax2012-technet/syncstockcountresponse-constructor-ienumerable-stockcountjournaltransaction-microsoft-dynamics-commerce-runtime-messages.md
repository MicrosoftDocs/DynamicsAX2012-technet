---
title: SyncStockCountResponse Constructor (IEnumerable(StockCountJournalTransaction)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SyncStockCountResponse Constructor (IEnumerable(StockCountJournalTransaction))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.SyncStockCountResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.syncstockcountresponse.syncstockcountresponse(v=AX.60)
ms:contentKeyID: 62211329
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SyncStockCountResponse Constructor (IEnumerable(StockCountJournalTransaction))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [SyncStockCountResponse](syncstockcountresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    transactions As IEnumerable(Of StockCountJournalTransaction) _
)
'Usage
Dim transactions As IEnumerable(Of StockCountJournalTransaction)

Dim instance As New SyncStockCountResponse(transactions)
```

``` csharp
public SyncStockCountResponse(
    IEnumerable<StockCountJournalTransaction> transactions
)
```

``` c++
public:
SyncStockCountResponse(
    IEnumerable<StockCountJournalTransaction^>^ transactions
)
```

#### Parameters

  - transactions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[StockCountJournalTransaction](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[SyncStockCountResponse Class](syncstockcountresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[SyncStockCountResponse Overload](syncstockcountresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

