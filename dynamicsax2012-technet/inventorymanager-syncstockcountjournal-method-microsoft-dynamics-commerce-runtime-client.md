---
title: InventoryManager.SyncStockCountJournal Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: SyncStockCountJournal Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.SyncStockCountJournal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.syncstockcountjournal(v=AX.60)
ms:contentKeyID: 62206193
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.SyncStockCountJournal
dev_langs:
- CSharp
- C++
- VB
---

# SyncStockCountJournal Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Syncs the Stock Count journal from AX to RetailServer Db and gets the current list of SC journal from Db.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function SyncStockCountJournal As ReadOnlyCollection(Of StockCountJournal)
'Usage
Dim instance As InventoryManager
Dim returnValue As ReadOnlyCollection(Of StockCountJournal)

returnValue = instance.SyncStockCountJournal()
```

``` csharp
public ReadOnlyCollection<StockCountJournal> SyncStockCountJournal()
```

``` c++
public:
ReadOnlyCollection<StockCountJournal^>^ SyncStockCountJournal()
```

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns the collection of Stock Count journal from RetailServer Db.  

## See Also

#### Reference

[InventoryManager Class](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

