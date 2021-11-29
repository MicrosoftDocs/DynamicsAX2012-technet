---
title: CartsController.GetSuspended Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetSuspended Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CartsController.GetSuspended
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.cartscontroller.getsuspended(v=AX.60)
ms:contentKeyID: 62202528
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CartsController.GetSuspended
dev_langs:
- CSharp
- C++
- VB
---

# GetSuspended Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets all suspended carts.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Overridable Function GetSuspended As IEnumerable(Of Cart)
'Usage
Dim instance As CartsController
Dim returnValue As IEnumerable(Of Cart)

returnValue = instance.GetSuspended()
```

``` csharp
[HttpPostAttribute]
public virtual IEnumerable<Cart> GetSuspended()
```

``` c++
[HttpPostAttribute]
public:
virtual IEnumerable<Cart^>^ GetSuspended()
```

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<Cart\>  
A collection of suspended carts.  

## See Also

#### Reference

[CartsController Class](cartscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

