---
title: PurchaseOrdersController Class (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: PurchaseOrdersController Class
ms:assetid: T:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.PurchaseOrdersController
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.purchaseorderscontroller(v=AX.60)
ms:contentKeyID: 62203625
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.PurchaseOrdersController
dev_langs:
- CSharp
- C++
- VB
---

# PurchaseOrdersController Class

The purchase order controller.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<ComVisibleAttribute(False)> _
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
Public Class PurchaseOrdersController _
    Inherits CommerceController(Of PurchaseOrder, String)
'Usage
Dim instance As PurchaseOrdersController
```

``` csharp
[ComVisibleAttribute(false)]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public class PurchaseOrdersController : CommerceController<PurchaseOrder, string>
```

``` c++
[ComVisibleAttribute(false)]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public ref class PurchaseOrdersController : public CommerceController<PurchaseOrder^, String^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  ApiController  
    ODataController  
      EntitySetController\<PurchaseOrder, [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
        [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CommerceController](commercecontroller-tentity-tkey-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)\<PurchaseOrder, [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
          Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.PurchaseOrdersController  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

