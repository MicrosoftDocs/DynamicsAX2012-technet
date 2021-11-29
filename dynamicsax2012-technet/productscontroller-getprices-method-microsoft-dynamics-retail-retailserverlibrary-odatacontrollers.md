---
title: ProductsController.GetPrices Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetPrices Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ProductsController.GetPrices(System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.productscontroller.getprices(v=AX.60)
ms:contentKeyID: 62202366
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ProductsController.GetPrices
dev_langs:
- CSharp
- C++
- VB
---

# GetPrices Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the price of an item in context of the current customer.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := True,  _
    RetailOperationId := RetailOperation.PriceCheck)> _
<HttpPostAttribute> _
Public Overridable Function GetPrices ( _
    parameters As ODataActionParameters _
) As IEnumerable(Of ProductPrice)
'Usage
Dim instance As ProductsController
Dim parameters As ODataActionParameters
Dim returnValue As IEnumerable(Of ProductPrice)

returnValue = instance.GetPrices(parameters)
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation.PriceCheck)]
[HttpPostAttribute]
public virtual IEnumerable<ProductPrice> GetPrices(
    ODataActionParameters parameters
)
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation::PriceCheck)]
[HttpPostAttribute]
public:
virtual IEnumerable<ProductPrice^>^ GetPrices(
    ODataActionParameters^ parameters
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<ProductPrice\>  
The collection of product prices.  

## See Also

#### Reference

[ProductsController Class](productscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

