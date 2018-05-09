---
title: CatalogsController.Get Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: Get Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CatalogsController.Get
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.catalogscontroller.get(v=AX.60)
ms:contentKeyID: 62202355
ms.date: 04/21/2014
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Get Method

Gets the set of product catalogs.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Overrides Function Get As IQueryable(Of ProductCatalog)
'Usage
Dim instance As CatalogsController
Dim returnValue As IQueryable(Of ProductCatalog)

returnValue = instance.Get()
```

``` csharp
public override IQueryable<ProductCatalog> Get()
```

``` c++
public:
virtual IQueryable<ProductCatalog^>^ Get() override
```

#### Return Value

Type: [System.Linq.IQueryable](https://technet.microsoft.com/en-us/library/bb351562\(v=ax.60\))\<ProductCatalog\>  
The [IQueryable](https://technet.microsoft.com/en-us/library/bb495796\(v=ax.60\)) list.  

## See Also

#### Reference

[CatalogsController Class](catalogscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Get Overload](catalogscontroller-get-method-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

