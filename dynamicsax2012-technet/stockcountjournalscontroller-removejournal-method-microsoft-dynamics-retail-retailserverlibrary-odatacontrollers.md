---
title: StockCountJournalsController.RemoveJournal Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: RemoveJournal Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.StockCountJournalsController.RemoveJournal(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.stockcountjournalscontroller.removejournal(v=AX.60)
ms:contentKeyID: 62203375
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.StockCountJournalsController.RemoveJournal
dev_langs:
- CSharp
- C++
- VB
---

# RemoveJournal Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Deletes the stock count journals from local.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Overridable Sub RemoveJournal ( _
    key As String _
)
'Usage
Dim instance As StockCountJournalsController
Dim key As String

instance.RemoveJournal(key)
```

``` csharp
[HttpPostAttribute]
public virtual void RemoveJournal(
    string key
)
```

``` c++
[HttpPostAttribute]
public:
virtual void RemoveJournal(
    String^ key
)
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[StockCountJournalsController Class](stockcountjournalscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

