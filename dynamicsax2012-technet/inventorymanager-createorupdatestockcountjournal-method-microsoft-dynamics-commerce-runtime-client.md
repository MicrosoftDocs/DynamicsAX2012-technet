---
title: InventoryManager.CreateOrUpdateStockCountJournal Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: CreateOrUpdateStockCountJournal Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.CreateOrUpdateStockCountJournal(Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.createorupdatestockcountjournal(v=AX.60)
ms:contentKeyID: 65318863
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.CreateOrUpdateStockCountJournal
dev_langs:
- CSharp
- C++
- VB
---

# CreateOrUpdateStockCountJournal Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function CreateOrUpdateStockCountJournal ( _
    stockCountJournal As StockCountJournal _
) As StockCountJournal
'Usage
Dim instance As InventoryManager
Dim stockCountJournal As StockCountJournal
Dim returnValue As StockCountJournal

returnValue = instance.CreateOrUpdateStockCountJournal(stockCountJournal)
```

``` csharp
public StockCountJournal CreateOrUpdateStockCountJournal(
    StockCountJournal stockCountJournal
)
```

``` c++
public:
StockCountJournal^ CreateOrUpdateStockCountJournal(
    StockCountJournal^ stockCountJournal
)
```

#### Parameters

  - stockCountJournal  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[InventoryManager Class](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

