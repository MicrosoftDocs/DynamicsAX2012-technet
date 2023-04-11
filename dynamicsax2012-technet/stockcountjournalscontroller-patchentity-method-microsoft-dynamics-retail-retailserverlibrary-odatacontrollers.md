---
title: StockCountJournalsController.PatchEntity Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: PatchEntity Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.StockCountJournalsController.PatchEntity(System.String,System.Web.Http.OData.Delta{Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.stockcountjournalscontroller.patchentity(v=AX.60)
ms:contentKeyID: 62201994
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.StockCountJournalsController.PatchEntity
dev_langs:
- CSharp
- C++
- VB
---

# PatchEntity Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Partially updates journal entity.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function PatchEntity ( _
    key As String, _
    patch As Delta(Of StockCountJournal) _
) As StockCountJournal
'Usage
Dim key As String
Dim patch As Delta(Of StockCountJournal)
Dim returnValue As StockCountJournal

returnValue = Me.PatchEntity(key, _
    patch)
```

``` csharp
protected override StockCountJournal PatchEntity(
    string key,
    Delta<StockCountJournal> patch
)
```

``` c++
protected:
virtual StockCountJournal^ PatchEntity(
    String^ key, 
    Delta<StockCountJournal^>^ patch
) override
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - patch  
    Type: Delta\<StockCountJournal\>  

#### Return Value

Type: StockCountJournal  
The StockCountJournal.  

## See Also

[StockCountJournalsController Class](stockcountjournalscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

Delta

