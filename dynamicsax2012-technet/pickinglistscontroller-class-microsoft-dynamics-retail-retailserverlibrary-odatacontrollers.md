---
title: PickingListsController Class (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: PickingListsController Class
ms:assetid: T:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.PickingListsController
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.pickinglistscontroller(v=AX.60)
ms:contentKeyID: 62201755
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.PickingListsController
dev_langs:
- CSharp
- C++
- VB
---

# PickingListsController Class

The controller for the picking list entity.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
<ComVisibleAttribute(False)> _
Public Class PickingListsController _
    Inherits CommerceController(Of PickingList, String)
'Usage
Dim instance As PickingListsController
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[ComVisibleAttribute(false)]
public class PickingListsController : CommerceController<PickingList, string>
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[ComVisibleAttribute(false)]
public ref class PickingListsController : public CommerceController<PickingList^, String^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  ApiController  
    ODataController  
      EntitySetController\<PickingList, [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
        [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CommerceController](commercecontroller-tentity-tkey-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)\<PickingList, [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
          Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.PickingListsController  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

