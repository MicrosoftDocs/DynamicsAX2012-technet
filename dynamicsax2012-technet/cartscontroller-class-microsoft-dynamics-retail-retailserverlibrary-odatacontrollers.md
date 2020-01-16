---
title: CartsController Class (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: CartsController Class
ms:assetid: T:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CartsController
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.cartscontroller(v=AX.60)
ms:contentKeyID: 62202720
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CartsController
dev_langs:
- CSharp
- C++
- VB
---

# CartsController Class

The carts controller.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
<ComVisibleAttribute(False)> _
Public Class CartsController _
    Inherits CommerceController(Of Cart, String)
'Usage
Dim instance As CartsController
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[ComVisibleAttribute(false)]
public class CartsController : CommerceController<Cart, string>
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
[ComVisibleAttribute(false)]
public ref class CartsController : public CommerceController<Cart^, String^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  ApiController  
    ODataController  
      EntitySetController\<Cart, [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
        [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CommerceController](commercecontroller-tentity-tkey-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)\<Cart, [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
          Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CartsController  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

