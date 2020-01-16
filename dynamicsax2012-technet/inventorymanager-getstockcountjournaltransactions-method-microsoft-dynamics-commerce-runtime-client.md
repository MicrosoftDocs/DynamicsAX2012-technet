---
title: InventoryManager.GetStockCountJournalTransactions Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetStockCountJournalTransactions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.GetStockCountJournalTransactions(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.getstockcountjournaltransactions(v=AX.60)
ms:contentKeyID: 62206308
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.GetStockCountJournalTransactions
dev_langs:
- CSharp
- C++
- VB
---

# GetStockCountJournalTransactions Method

Gets the Stock Count journal transactions from AX for the given journalId.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetStockCountJournalTransactions ( _
    journalId As String _
) As ReadOnlyCollection(Of StockCountJournalTransaction)
'Usage
Dim instance As InventoryManager
Dim journalId As String
Dim returnValue As ReadOnlyCollection(Of StockCountJournalTransaction)

returnValue = instance.GetStockCountJournalTransactions(journalId)
```

``` csharp
public ReadOnlyCollection<StockCountJournalTransaction> GetStockCountJournalTransactions(
    string journalId
)
```

``` c++
public:
ReadOnlyCollection<StockCountJournalTransaction^>^ GetStockCountJournalTransactions(
    String^ journalId
)
```

#### Parameters

  - journalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[StockCountJournalTransaction](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns the StockCount journal transaction list.  

## See Also

#### Reference

[InventoryManager Class](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

