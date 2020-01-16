---
title: StockCountJournalsController.Commit Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: Commit Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.StockCountJournalsController.Commit(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.stockcountjournalscontroller.commit(v=AX.60)
ms:contentKeyID: 62203079
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.StockCountJournalsController.Commit
dev_langs:
- CSharp
- C++
- VB
---

# Commit Method

Commits the list of Stock journal transactions to AX.

After successful commit, all the journal and transactions are deleted from the RetailServer DB.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Overridable Sub Commit ( _
    key As String _
)
'Usage
Dim instance As StockCountJournalsController
Dim key As String

instance.Commit(key)
```

``` csharp
[HttpPostAttribute]
public virtual void Commit(
    string key
)
```

``` c++
[HttpPostAttribute]
public:
virtual void Commit(
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

