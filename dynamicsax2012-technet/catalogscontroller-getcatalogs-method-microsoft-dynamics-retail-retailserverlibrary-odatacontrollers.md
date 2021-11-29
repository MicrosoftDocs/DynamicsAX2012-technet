---
title: CatalogsController.GetCatalogs Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetCatalogs Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CatalogsController.GetCatalogs(System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.catalogscontroller.getcatalogs(v=AX.60)
ms:contentKeyID: 62203089
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.CatalogsController.GetCatalogs
dev_langs:
- CSharp
- C++
- VB
---

# GetCatalogs Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets catalogs by OData query.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Overridable Function GetCatalogs ( _
    parameters As ODataActionParameters _
) As IEnumerable(Of ProductCatalog)
'Usage
Dim instance As CatalogsController
Dim parameters As ODataActionParameters
Dim returnValue As IEnumerable(Of ProductCatalog)

returnValue = instance.GetCatalogs(parameters)
```

``` csharp
[HttpPostAttribute]
public virtual IEnumerable<ProductCatalog> GetCatalogs(
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
public:
virtual IEnumerable<ProductCatalog^>^ GetCatalogs(
    ODataActionParameters^ parameters
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<ProductCatalog\>  
The collection of product catalogs.  

## See Also

#### Reference

[CatalogsController Class](catalogscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

