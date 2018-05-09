---
title: CategoriesController.Get Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: Get Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CategoriesController.Get
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.categoriescontroller.get(v=AX.60)
ms:contentKeyID: 62202776
ms.date: 04/21/2014
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Get Method

Gets full list of categories as [IQueryable](https://technet.microsoft.com/en-us/library/bb495796\(v=ax.60\)).

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Overrides Function Get As IQueryable(Of Category)
'Usage
Dim instance As CategoriesController
Dim returnValue As IQueryable(Of Category)

returnValue = instance.Get()
```

``` csharp
public override IQueryable<Category> Get()
```

``` c++
public:
virtual IQueryable<Category^>^ Get() override
```

#### Return Value

Type: [System.Linq.IQueryable](https://technet.microsoft.com/en-us/library/bb351562\(v=ax.60\))\<Category\>  
The [IQueryable](https://technet.microsoft.com/en-us/library/bb495796\(v=ax.60\)) set of categories.  

## See Also

#### Reference

[CategoriesController Class](categoriescontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Get Overload](categoriescontroller-get-method-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

