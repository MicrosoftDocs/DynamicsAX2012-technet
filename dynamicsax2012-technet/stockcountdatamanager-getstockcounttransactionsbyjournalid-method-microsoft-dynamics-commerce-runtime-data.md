---
title: StockCountDataManager.GetStockCountTransactionsByJournalId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetStockCountTransactionsByJournalId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.StockCountDataManager.GetStockCountTransactionsByJournalId(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.stockcountdatamanager.getstockcounttransactionsbyjournalid(v=AX.60)
ms:contentKeyID: 65315513
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.StockCountDataManager.GetStockCountTransactionsByJournalId
dev_langs:
- CSharp
- C++
- VB
---

# GetStockCountTransactionsByJournalId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetStockCountTransactionsByJournalId ( _
    journalId As String, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of StockCountJournalTransaction)
'Usage
Dim instance As StockCountDataManager
Dim journalId As String
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of StockCountJournalTransaction)

returnValue = instance.GetStockCountTransactionsByJournalId(journalId, _
    settings)
```

``` csharp
public ReadOnlyCollection<StockCountJournalTransaction> GetStockCountTransactionsByJournalId(
    string journalId,
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<StockCountJournalTransaction^>^ GetStockCountTransactionsByJournalId(
    String^ journalId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - journalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[StockCountJournalTransaction](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[StockCountDataManager Class](stockcountdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

