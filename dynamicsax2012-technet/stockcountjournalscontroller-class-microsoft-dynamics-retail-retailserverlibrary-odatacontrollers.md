---
title: StockCountJournalsController Class (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: StockCountJournalsController Class
ms:assetid: T:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.StockCountJournalsController
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.stockcountjournalscontroller(v=AX.60)
ms:contentKeyID: 62203636
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.StockCountJournalsController
dev_langs:
- CSharp
- C++
- VB
---

# StockCountJournalsController Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The stock count journals controller.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<ComVisibleAttribute(False)> _
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := True,  _
    RetailOperationId := RetailOperation.StockCount)> _
Public Class StockCountJournalsController _
    Inherits CommerceController(Of StockCountJournal, String)
'Usage
Dim instance As StockCountJournalsController
```

``` csharp
[ComVisibleAttribute(false)]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation.StockCount)]
public class StockCountJournalsController : CommerceController<StockCountJournal, string>
```

``` c++
[ComVisibleAttribute(false)]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation::StockCount)]
public ref class StockCountJournalsController : public CommerceController<StockCountJournal^, String^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  ApiController  
    ODataController  
      EntitySetController\<StockCountJournal, [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
        [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CommerceController](commercecontroller-tentity-tkey-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)\<StockCountJournal, [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
          Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.StockCountJournalsController  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

