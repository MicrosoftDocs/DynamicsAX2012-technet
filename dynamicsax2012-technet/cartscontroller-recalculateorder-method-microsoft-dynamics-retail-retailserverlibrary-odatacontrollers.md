---
title: CartsController.RecalculateOrder Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: RecalculateOrder Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CartsController.RecalculateOrder(System.String,System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.cartscontroller.recalculateorder(v=AX.60)
ms:contentKeyID: 62201806
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CartsController.RecalculateOrder
dev_langs:
- CSharp
- C++
- VB
---

# RecalculateOrder Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Recalculates a customer order.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Overridable Function RecalculateOrder ( _
    key As String, _
    parameters As ODataActionParameters _
) As Cart
'Usage
Dim instance As CartsController
Dim key As String
Dim parameters As ODataActionParameters
Dim returnValue As Cart

returnValue = instance.RecalculateOrder(key, _
    parameters)
```

``` csharp
[HttpPostAttribute]
public virtual Cart RecalculateOrder(
    string key,
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
public:
virtual Cart^ RecalculateOrder(
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

