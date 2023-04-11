---
title: CategoriesController.GetChildren Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetChildren Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CategoriesController.GetChildren(System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.categoriescontroller.getchildren(v=AX.60)
ms:contentKeyID: 62202204
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CategoriesController.GetChildren
dev_langs:
- CSharp
- C++
- VB
---

# GetChildren Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets subcategories by given Channel ID and Category ID.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Overridable Function GetChildren ( _
    parameters As ODataActionParameters _
) As IEnumerable(Of Category)
'Usage
Dim instance As CategoriesController
Dim parameters As ODataActionParameters
Dim returnValue As IEnumerable(Of Category)

returnValue = instance.GetChildren(parameters)
```

``` csharp
[HttpPostAttribute]
public virtual IEnumerable<Category> GetChildren(
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
public:
virtual IEnumerable<Category^>^ GetChildren(
    ODataActionParameters^ parameters
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<Category\>  
The list of subcategories.  

## See Also

#### Reference

[CategoriesController Class](categoriescontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

