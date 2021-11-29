---
title: StockCountJournalsController.UpdateEntity Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: UpdateEntity Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.StockCountJournalsController.UpdateEntity(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.stockcountjournalscontroller.updateentity(v=AX.60)
ms:contentKeyID: 62202166
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.StockCountJournalsController.UpdateEntity
dev_langs:
- CSharp
- C++
- VB
---

# UpdateEntity Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Updates journal entity.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function UpdateEntity ( _
    key As String, _
    update As StockCountJournal _
) As StockCountJournal
'Usage
Dim key As String
Dim update As StockCountJournal
Dim returnValue As StockCountJournal

returnValue = Me.UpdateEntity(key, _
    update)
```

``` csharp
protected override StockCountJournal UpdateEntity(
    string key,
    StockCountJournal update
)
```

``` c++
protected:
virtual StockCountJournal^ UpdateEntity(
    String^ key, 
    StockCountJournal^ update
) override
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - update  
    Type: StockCountJournal  

#### Return Value

Type: StockCountJournal  
The StockCountJournal.  

## See Also

#### Reference

[StockCountJournalsController Class](stockcountjournalscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

