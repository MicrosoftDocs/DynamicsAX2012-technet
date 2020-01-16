---
title: InventoryManager.SaveStockCountJournalTransactions Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: SaveStockCountJournalTransactions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.SaveStockCountJournalTransactions(System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.savestockcountjournaltransactions(v=AX.60)
ms:contentKeyID: 62212037
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.SaveStockCountJournalTransactions
dev_langs:
- CSharp
- C++
- VB
---

# SaveStockCountJournalTransactions Method

Saves the list of StockCount journal transactions for the corresponding Journal in RetailServer DB.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function SaveStockCountJournalTransactions ( _
    journalId As String, _
    transactions As IEnumerable(Of StockCountJournalTransaction) _
) As StockCountJournal
'Usage
Dim instance As InventoryManager
Dim journalId As String
Dim transactions As IEnumerable(Of StockCountJournalTransaction)
Dim returnValue As StockCountJournal

returnValue = instance.SaveStockCountJournalTransactions(journalId, _
    transactions)
```

``` csharp
public StockCountJournal SaveStockCountJournalTransactions(
    string journalId,
    IEnumerable<StockCountJournalTransaction> transactions
)
```

``` c++
public:
StockCountJournal^ SaveStockCountJournalTransactions(
    String^ journalId, 
    IEnumerable<StockCountJournalTransaction^>^ transactions
)
```

#### Parameters

  - journalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - transactions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[StockCountJournalTransaction](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The journal transactions that havebeen saved.  

## See Also

#### Reference

[InventoryManager Class](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

