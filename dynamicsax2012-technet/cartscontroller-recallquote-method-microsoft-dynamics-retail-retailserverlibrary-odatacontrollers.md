---
title: CartsController.RecallQuote Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: RecallQuote Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CartsController.RecallQuote(System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.cartscontroller.recallquote(v=AX.60)
ms:contentKeyID: 62203776
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CartsController.RecallQuote
dev_langs:
- CSharp
- C++
- VB
---

# RecallQuote Method

Recalls a quote.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Overridable Function RecallQuote ( _
    parameters As ODataActionParameters _
) As Cart
'Usage
Dim instance As CartsController
Dim parameters As ODataActionParameters
Dim returnValue As Cart

returnValue = instance.RecallQuote(parameters)
```

``` csharp
[HttpPostAttribute]
public virtual Cart RecallQuote(
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
public:
virtual Cart^ RecallQuote(
    ODataActionParameters^ parameters
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

#### Return Value

Type: Cart  
The cart object.  

## See Also

#### Reference

[CartsController Class](cartscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

