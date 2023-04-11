---
title: StockCountJournalsController.SyncTransactions Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: SyncTransactions Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.StockCountJournalsController.SyncTransactions(System.Void)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.stockcountjournalscontroller.synctransactions(v=AX.60)
ms:contentKeyID: 62202849
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.StockCountJournalsController.SyncTransactions
dev_langs:
- CSharp
- C++
- VB
---

# SyncTransactions Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Overridable Function SyncTransactions ( _
    key As Void _
) As IReadOnlyCollection
'Usage
Dim instance As StockCountJournalsController
Dim key As Void
Dim returnValue As IReadOnlyCollection

returnValue = instance.SyncTransactions(key)
```

``` csharp
[HttpPostAttribute]
public virtual IReadOnlyCollection SyncTransactions(
    void key
)
```

``` c++
[HttpPostAttribute]
public:
virtual IReadOnlyCollection^ SyncTransactions(
    void key
)
```

#### Parameters

  - key  
    Type: [System.Void](https://technet.microsoft.com/library/skf099af\(v=ax.60\))  

#### Return Value

Type: IReadOnlyCollection  
Returns IReadOnlyCollection.  

## See Also

#### Reference

[StockCountJournalsController Class](stockcountjournalscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

