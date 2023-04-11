---
title: StockCountJournalsController.RemoveTransaction Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: RemoveTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.StockCountJournalsController.RemoveTransaction(System.String,System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.stockcountjournalscontroller.removetransaction(v=AX.60)
ms:contentKeyID: 62203676
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.StockCountJournalsController.RemoveTransaction
dev_langs:
- CSharp
- C++
- VB
---

# RemoveTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Deletes the stock count journal transaction from local.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Overridable Sub RemoveTransaction ( _
    key As String, _
    parameters As ODataActionParameters _
)
'Usage
Dim instance As StockCountJournalsController
Dim key As String
Dim parameters As ODataActionParameters

instance.RemoveTransaction(key, parameters)
```

``` csharp
[HttpPostAttribute]
public virtual void RemoveTransaction(
    string key,
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
public:
virtual void RemoveTransaction(
    String^ key, 
    ODataActionParameters^ parameters
)
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - parameters  
    Type: ODataActionParameters  

## See Also

#### Reference

[StockCountJournalsController Class](stockcountjournalscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

