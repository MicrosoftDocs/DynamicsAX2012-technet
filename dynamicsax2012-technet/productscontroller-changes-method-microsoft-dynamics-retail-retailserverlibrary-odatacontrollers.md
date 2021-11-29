---
title: ProductsController.Changes Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: Changes Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ProductsController.Changes(System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.productscontroller.changes(v=AX.60)
ms:contentKeyID: 62203358
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.ProductsController.Changes
dev_langs:
- CSharp
- C++
- VB
---

# Changes Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Searches and retrieves changed products given the specified query criteria.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := True,  _
    RetailOperationId := RetailOperation.ViewProductDetails)> _
<HttpPostAttribute> _
Public Overridable Function Changes ( _
    parameters As ODataActionParameters _
) As IEnumerable(Of Product)
'Usage
Dim instance As ProductsController
Dim parameters As ODataActionParameters
Dim returnValue As IEnumerable(Of Product)

returnValue = instance.Changes(parameters)
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation.ViewProductDetails)]
[HttpPostAttribute]
public virtual IEnumerable<Product> Changes(
    ODataActionParameters parameters
)
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation::ViewProductDetails)]
[HttpPostAttribute]
public:
virtual IEnumerable<Product^>^ Changes(
    ODataActionParameters^ parameters
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<Product\>  
The set of changed products, as well as the next sync anchor.  

## See Also

#### Reference

[ProductsController Class](productscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

