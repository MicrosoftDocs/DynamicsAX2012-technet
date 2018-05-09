---
title: InventoryManager.GetStockCountJournals Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetStockCountJournals Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.GetStockCountJournals(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.getstockcountjournals(v=AX.60)
ms:contentKeyID: 65321225
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.GetStockCountJournals
dev_langs:
- CSharp
- C++
- VB
---

# GetStockCountJournals Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetStockCountJournals ( _
    settings As QueryResultSettings _
) As PagedResult(Of StockCountJournal)
'Usage
Dim instance As InventoryManager
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of StockCountJournal)

returnValue = instance.GetStockCountJournals(settings)
```

``` csharp
public PagedResult<StockCountJournal> GetStockCountJournals(
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<StockCountJournal^>^ GetStockCountJournals(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[InventoryManager Class](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

