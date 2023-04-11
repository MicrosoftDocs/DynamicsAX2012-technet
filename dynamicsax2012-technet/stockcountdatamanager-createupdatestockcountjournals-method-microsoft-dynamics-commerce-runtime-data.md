---
title: StockCountDataManager.CreateUpdateStockCountJournals Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: CreateUpdateStockCountJournals Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.StockCountDataManager.CreateUpdateStockCountJournals(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.stockcountdatamanager.createupdatestockcountjournals(v=AX.60)
ms:contentKeyID: 62207815
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.StockCountDataManager.CreateUpdateStockCountJournals
dev_langs:
- CSharp
- C++
- VB
---

# CreateUpdateStockCountJournals Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Insert/Update one (or) more of StockCount journals.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub CreateUpdateStockCountJournals ( _
    stockCountJournals As IEnumerable(Of StockCountJournal) _
)
'Usage
Dim instance As StockCountDataManager
Dim stockCountJournals As IEnumerable(Of StockCountJournal)

instance.CreateUpdateStockCountJournals(stockCountJournals)
```

``` csharp
public void CreateUpdateStockCountJournals(
    IEnumerable<StockCountJournal> stockCountJournals
)
```

``` c++
public:
void CreateUpdateStockCountJournals(
    IEnumerable<StockCountJournal^>^ stockCountJournals
)
```

#### Parameters

  - stockCountJournals  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[StockCountDataManager Class](stockcountdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

