---
title: OrgUnitsController.Search Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: Search Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.OrgUnitsController.Search(System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.orgunitscontroller.search(v=AX.60)
ms:contentKeyID: 62201872
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.OrgUnitsController.Search
dev_langs:
- CSharp
- C++
- VB
---

# Search Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Searches for organization unit by the given search query.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Function Search ( _
    parameters As ODataActionParameters _
) As IEnumerable(Of OrgUnit)
'Usage
Dim instance As OrgUnitsController
Dim parameters As ODataActionParameters
Dim returnValue As IEnumerable(Of OrgUnit)

returnValue = instance.Search(parameters)
```

``` csharp
[HttpPostAttribute]
public IEnumerable<OrgUnit> Search(
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
public:
IEnumerable<OrgUnit^>^ Search(
    ODataActionParameters^ parameters
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<OrgUnit\>  
The collection of stores.  

## See Also

#### Reference

[OrgUnitsController Class](orgunitscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

