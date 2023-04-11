---
title: CartsController.GetProductsInCart Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetProductsInCart Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CartsController.GetProductsInCart(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.cartscontroller.getproductsincart(v=AX.60)
ms:contentKeyID: 62202488
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CartsController.GetProductsInCart
dev_langs:
- CSharp
- C++
- VB
---

# GetProductsInCart Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the list of product objects used in context of the cart specified by the cart ID.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Overridable Function GetProductsInCart ( _
    key As String _
) As IEnumerable(Of Product)
'Usage
Dim instance As CartsController
Dim key As String
Dim returnValue As IEnumerable(Of Product)

returnValue = instance.GetProductsInCart(key)
```

``` csharp
[HttpPostAttribute]
public virtual IEnumerable<Product> GetProductsInCart(
    string key
)
```

``` c++
[HttpPostAttribute]
public:
virtual IEnumerable<Product^>^ GetProductsInCart(
    String^ key
)
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<Product\>  
The list of product objects.  

## See Also

#### Reference

[CartsController Class](cartscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

