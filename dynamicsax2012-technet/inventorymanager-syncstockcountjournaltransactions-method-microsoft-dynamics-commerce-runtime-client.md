---
title: InventoryManager.SyncStockCountJournalTransactions Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: SyncStockCountJournalTransactions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.SyncStockCountJournalTransactions(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.syncstockcountjournaltransactions(v=AX.60)
ms:contentKeyID: 62211886
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.SyncStockCountJournalTransactions
dev_langs:
- CSharp
- C++
- VB
---

# SyncStockCountJournalTransactions Method

Syncs the Stock Count journal Transactions from AX to RetailServer Db and gets the current list of SC journal transactions from Db.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function SyncStockCountJournalTransactions ( _
    journalId As String _
) As ReadOnlyCollection(Of StockCountJournalTransaction)
'Usage
Dim instance As InventoryManager
Dim journalId As String
Dim returnValue As ReadOnlyCollection(Of StockCountJournalTransaction)

returnValue = instance.SyncStockCountJournalTransactions(journalId)
```

``` csharp
public ReadOnlyCollection<StockCountJournalTransaction> SyncStockCountJournalTransactions(
    string journalId
)
```

``` c++
public:
ReadOnlyCollection<StockCountJournalTransaction^>^ SyncStockCountJournalTransactions(
    String^ journalId
)
```

#### Parameters

  - journalId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[StockCountJournalTransaction](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns the collection of Stock Count journal transactions from RetailServer Db.  

## See Also

#### Reference

[InventoryManager Class](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

