---
title: StockCountJournalsController.Sync Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: Sync Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.StockCountJournalsController.Sync
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.stockcountjournalscontroller.sync(v=AX.60)
ms:contentKeyID: 62203398
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.StockCountJournalsController.Sync
dev_langs:
- CSharp
- C++
- VB
---

# Sync Method

Syncs the Stock Count journal from AX to RetailServer DB and gets the current list of SC journal from DB.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Overridable Function Sync As IEnumerable(Of StockCountJournal)
'Usage
Dim instance As StockCountJournalsController
Dim returnValue As IEnumerable(Of StockCountJournal)

returnValue = instance.Sync()
```

``` csharp
[HttpPostAttribute]
public virtual IEnumerable<StockCountJournal> Sync()
```

``` c++
[HttpPostAttribute]
public:
virtual IEnumerable<StockCountJournal^>^ Sync()
```

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<StockCountJournal\>  
A collection of journal objects.  

## See Also

#### Reference

[StockCountJournalsController Class](stockcountjournalscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

