---
title: OrgUnitsController.GetOrgUnitLocations Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetOrgUnitLocations Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.OrgUnitsController.GetOrgUnitLocations
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.orgunitscontroller.getorgunitlocations(v=AX.60)
ms:contentKeyID: 62203615
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.OrgUnitsController.GetOrgUnitLocations
dev_langs:
- CSharp
- C++
- VB
---

# GetOrgUnitLocations Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Finds all stores locations.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Function GetOrgUnitLocations As IEnumerable(Of OrgUnitLocation)
'Usage
Dim instance As OrgUnitsController
Dim returnValue As IEnumerable(Of OrgUnitLocation)

returnValue = instance.GetOrgUnitLocations()
```

``` csharp
[HttpPostAttribute]
public IEnumerable<OrgUnitLocation> GetOrgUnitLocations()
```

``` c++
[HttpPostAttribute]
public:
IEnumerable<OrgUnitLocation^>^ GetOrgUnitLocations()
```

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<OrgUnitLocation\>  
The collection of all stores locations.  

## See Also

#### Reference

[OrgUnitsController Class](orgunitscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

