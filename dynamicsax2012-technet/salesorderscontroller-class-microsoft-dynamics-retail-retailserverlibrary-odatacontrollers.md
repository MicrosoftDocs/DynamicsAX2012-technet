---
title: SalesOrdersController Class (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: SalesOrdersController Class
ms:assetid: T:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.SalesOrdersController
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.salesorderscontroller(v=AX.60)
ms:contentKeyID: 62202491
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.SalesOrdersController
dev_langs:
- CSharp
- C++
- VB
---

# SalesOrdersController Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The sales order controller.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<ComVisibleAttribute(False)> _
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
Public Class SalesOrdersController _
    Inherits CommerceController(Of SalesOrder, String)
'Usage
Dim instance As SalesOrdersController
```

``` csharp
[ComVisibleAttribute(false)]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public class SalesOrdersController : CommerceController<SalesOrder, string>
```

``` c++
[ComVisibleAttribute(false)]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public ref class SalesOrdersController : public CommerceController<SalesOrder^, String^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  ApiController  
    ODataController  
      EntitySetController\<SalesOrder, [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
        [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CommerceController](commercecontroller-tentity-tkey-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)\<SalesOrder, [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
          Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.SalesOrdersController  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

