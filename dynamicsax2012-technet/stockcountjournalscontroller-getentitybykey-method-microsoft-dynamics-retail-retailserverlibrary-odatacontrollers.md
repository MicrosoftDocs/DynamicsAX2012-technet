---
title: StockCountJournalsController.GetEntityByKey Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetEntityByKey Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.StockCountJournalsController.GetEntityByKey(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.stockcountjournalscontroller.getentitybykey(v=AX.60)
ms:contentKeyID: 62203094
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.StockCountJournalsController.GetEntityByKey
dev_langs:
- CSharp
- C++
- VB
---

# GetEntityByKey Method

Gets journal entity by key.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Protected Overrides Function GetEntityByKey ( _
    key As String _
) As StockCountJournal
'Usage
Dim key As String
Dim returnValue As StockCountJournal

returnValue = Me.GetEntityByKey(key)
```

``` csharp
protected override StockCountJournal GetEntityByKey(
    string key
)
```

``` c++
protected:
virtual StockCountJournal^ GetEntityByKey(
    String^ key
) override
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: StockCountJournal  
The StockCountJournal entity.  

## See Also

#### Reference

[StockCountJournalsController Class](stockcountjournalscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

