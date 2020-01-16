---
title: GetStockCountResponse Constructor (IEnumerable(StockCountJournalTransaction)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetStockCountResponse Constructor (IEnumerable(StockCountJournalTransaction))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStockCountResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getstockcountresponse.getstockcountresponse(v=AX.60)
ms:contentKeyID: 62214947
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetStockCountResponse Constructor (IEnumerable(StockCountJournalTransaction))

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

Dim instance As New GetStockCountResponse(transactions)
```

``` csharp
public GetStockCountResponse(
    IEnumerable<StockCountJournalTransaction> transactions
)
```

``` c++
public:
GetStockCountResponse(
    IEnumerable<StockCountJournalTransaction^>^ transactions
)
```

#### Parameters

  - transactions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[StockCountJournalTransaction](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetStockCountResponse Class](getstockcountresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetStockCountResponse Overload](getstockcountresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

