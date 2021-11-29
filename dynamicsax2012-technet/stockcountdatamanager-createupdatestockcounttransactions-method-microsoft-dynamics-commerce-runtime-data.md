---
title: StockCountDataManager.CreateUpdateStockCountTransactions Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: CreateUpdateStockCountTransactions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.StockCountDataManager.CreateUpdateStockCountTransactions(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.stockcountdatamanager.createupdatestockcounttransactions(v=AX.60)
ms:contentKeyID: 62210564
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.StockCountDataManager.CreateUpdateStockCountTransactions
dev_langs:
- CSharp
- C++
- VB
---

# CreateUpdateStockCountTransactions Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Insert/ Update one (or) more Stock Count Journal Transactions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub CreateUpdateStockCountTransactions ( _
    journalTrans As IEnumerable(Of StockCountJournalTransaction) _
)
'Usage
Dim instance As StockCountDataManager
Dim journalTrans As IEnumerable(Of StockCountJournalTransaction)

instance.CreateUpdateStockCountTransactions(journalTrans)
```

``` csharp
public void CreateUpdateStockCountTransactions(
    IEnumerable<StockCountJournalTransaction> journalTrans
)
```

``` c++
public:
void CreateUpdateStockCountTransactions(
    IEnumerable<StockCountJournalTransaction^>^ journalTrans
)
```

#### Parameters

  - journalTrans  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[StockCountJournalTransaction](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[StockCountDataManager Class](stockcountdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

