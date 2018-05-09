---
title: CategoriesController.GetCategories Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetCategories Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CategoriesController.GetCategories(System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.categoriescontroller.getcategories(v=AX.60)
ms:contentKeyID: 62202183
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CategoriesController.GetCategories
dev_langs:
- CSharp
- C++
- VB
---

# GetCategories Method

Gets categories by OData query.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Overridable Function GetCategories ( _
    parameters As ODataActionParameters _
) As IEnumerable(Of Category)
'Usage
Dim instance As CategoriesController
Dim parameters As ODataActionParameters
Dim returnValue As IEnumerable(Of Category)

returnValue = instance.GetCategories(parameters)
```

``` csharp
[HttpPostAttribute]
public virtual IEnumerable<Category> GetCategories(
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
public:
virtual IEnumerable<Category^>^ GetCategories(
    ODataActionParameters^ parameters
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<Category\>  
The list of categories.  

## See Also

#### Reference

[CategoriesController Class](categoriescontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

