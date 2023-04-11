---
title: CartsController.UpdateCartLines Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: UpdateCartLines Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CartsController.UpdateCartLines(System.String,System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.cartscontroller.updatecartlines(v=AX.60)
ms:contentKeyID: 62202684
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CartsController.UpdateCartLines
dev_langs:
- CSharp
- C++
- VB
---

# UpdateCartLines Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Updates the cart lines in the cart.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Overridable Function UpdateCartLines ( _
    key As String, _
    parameters As ODataActionParameters _
) As Cart
'Usage
Dim instance As CartsController
Dim key As String
Dim parameters As ODataActionParameters
Dim returnValue As Cart

returnValue = instance.UpdateCartLines(key, _
    parameters)
```

``` csharp
[HttpPostAttribute]
public virtual Cart UpdateCartLines(
    string key,
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
public:
virtual Cart^ UpdateCartLines(
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

#### Return Value

Type: Cart  
The cart object.  

## See Also

#### Reference

[CartsController Class](cartscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

