---
title: CartsController.Checkout Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: Checkout Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CartsController.Checkout(System.String,System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.cartscontroller.checkout(v=AX.60)
ms:contentKeyID: 62202150
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CartsController.Checkout
dev_langs:
- CSharp
- C++
- VB
---

# Checkout Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Checkouts the sales cart.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Overridable Function Checkout ( _
    key As String, _
    parameters As ODataActionParameters _
) As SalesOrder
'Usage
Dim instance As CartsController
Dim key As String
Dim parameters As ODataActionParameters
Dim returnValue As SalesOrder

returnValue = instance.Checkout(key, parameters)
```

``` csharp
[HttpPostAttribute]
public virtual SalesOrder Checkout(
    string key,
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
public:
virtual SalesOrder^ Checkout(
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

Type: SalesOrder  
The sales order object.  

## See Also

#### Reference

[CartsController Class](cartscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

