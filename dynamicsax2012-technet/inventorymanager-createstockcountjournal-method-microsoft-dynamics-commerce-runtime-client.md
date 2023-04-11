---
title: InventoryManager.CreateStockCountJournal Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: CreateStockCountJournal Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.CreateStockCountJournal(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.inventorymanager.createstockcountjournal(v=AX.60)
ms:contentKeyID: 62212734
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.InventoryManager.CreateStockCountJournal
dev_langs:
- CSharp
- C++
- VB
---

# CreateStockCountJournal Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates the StockCount Journal and retuns the created journal.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function CreateStockCountJournal ( _
    description As String _
) As StockCountJournal
'Usage
Dim instance As InventoryManager
Dim description As String
Dim returnValue As StockCountJournal

returnValue = instance.CreateStockCountJournal(description)
```

``` csharp
public StockCountJournal CreateStockCountJournal(
    string description
)
```

``` c++
public:
StockCountJournal^ CreateStockCountJournal(
    String^ description
)
```

#### Parameters

  - description  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns the StockCount journal created.  

## See Also

#### Reference

[InventoryManager Class](inventorymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

