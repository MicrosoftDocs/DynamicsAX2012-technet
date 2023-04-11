---
title: InventoryManager.GetStockCountJournalById Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetStockCountJournalById Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.GetStockCountJournalById(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.getstockcountjournalbyid(v=AX.60)
ms:contentKeyID: 62205737
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.GetStockCountJournalById
dev_langs:
- CSharp
- C++
- VB
---

# GetStockCountJournalById Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the StockCount journal from AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetStockCountJournalById ( _
    journalId As String _
) As StockCountJournal
'Usage
Dim instance As InventoryManager
Dim journalId As String
Dim returnValue As StockCountJournal

returnValue = instance.GetStockCountJournalById(journalId)
```

``` csharp
public StockCountJournal GetStockCountJournalById(
    string journalId
)
```

``` c++
public:
StockCountJournal^ GetStockCountJournalById(
    String^ journalId
)
```

#### Parameters

  - journalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns the collection of StockCount Journal.  

## See Also

#### Reference

[InventoryManager Class](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

