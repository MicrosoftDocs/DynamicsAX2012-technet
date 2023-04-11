---
title: OrgUnitsController.GetOrgUnitLocationsByArea Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetOrgUnitLocationsByArea Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.OrgUnitsController.GetOrgUnitLocationsByArea(System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.orgunitscontroller.getorgunitlocationsbyarea(v=AX.60)
ms:contentKeyID: 62203220
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.OrgUnitsController.GetOrgUnitLocationsByArea
dev_langs:
- CSharp
- C++
- VB
---

# GetOrgUnitLocationsByArea Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Finds stores in a defined area.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Function GetOrgUnitLocationsByArea ( _
    parameters As ODataActionParameters _
) As IEnumerable(Of OrgUnitLocation)
'Usage
Dim instance As OrgUnitsController
Dim parameters As ODataActionParameters
Dim returnValue As IEnumerable(Of OrgUnitLocation)

returnValue = instance.GetOrgUnitLocationsByArea(parameters)
```

``` csharp
[HttpPostAttribute]
public IEnumerable<OrgUnitLocation> GetOrgUnitLocationsByArea(
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
public:
IEnumerable<OrgUnitLocation^>^ GetOrgUnitLocationsByArea(
    ODataActionParameters^ parameters
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<OrgUnitLocation\>  
The collection of stores in that area.  

## See Also

#### Reference

[OrgUnitsController Class](orgunitscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

