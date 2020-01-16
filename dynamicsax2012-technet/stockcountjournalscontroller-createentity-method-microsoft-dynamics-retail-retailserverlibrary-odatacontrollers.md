---
title: StockCountJournalsController.CreateEntity Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: CreateEntity Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.StockCountJournalsController.CreateEntity(Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.stockcountjournalscontroller.createentity(v=AX.60)
ms:contentKeyID: 62202218
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.StockCountJournalsController.CreateEntity
dev_langs:
- CSharp
- C++
- VB
---

# CreateEntity Method

Creates journal entity.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function CreateEntity ( _
    entity As StockCountJournal _
) As StockCountJournal
'Usage
Dim entity As StockCountJournal
Dim returnValue As StockCountJournal

returnValue = Me.CreateEntity(entity)
```

``` csharp
protected override StockCountJournal CreateEntity(
    StockCountJournal entity
)
```

``` c++
protected:
virtual StockCountJournal^ CreateEntity(
    StockCountJournal^ entity
) override
```

#### Parameters

  - entity  
    Type: StockCountJournal  

#### Return Value

Type: StockCountJournal  
The StockCountJournal created item.  

## See Also

#### Reference

[StockCountJournalsController Class](stockcountjournalscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

