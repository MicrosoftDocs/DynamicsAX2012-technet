---
title: SyncStockCountResponse Constructor (IEnumerable(StockCountJournal)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SyncStockCountResponse Constructor (IEnumerable(StockCountJournal))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.SyncStockCountResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.syncstockcountresponse.syncstockcountresponse(v=AX.60)
ms:contentKeyID: 62211583
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SyncStockCountResponse Constructor (IEnumerable(StockCountJournal))

Initializes a new instance of the [SyncStockCountResponse](syncstockcountresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    journals As IEnumerable(Of StockCountJournal) _
)
'Usage
Dim journals As IEnumerable(Of StockCountJournal)

Dim instance As New SyncStockCountResponse(journals)
```

``` csharp
public SyncStockCountResponse(
    IEnumerable<StockCountJournal> journals
)
```

``` c++
public:
SyncStockCountResponse(
    IEnumerable<StockCountJournal^>^ journals
)
```

#### Parameters

  - journals  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[SyncStockCountResponse Class](syncstockcountresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[SyncStockCountResponse Overload](syncstockcountresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

