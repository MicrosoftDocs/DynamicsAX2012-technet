---
title: OrgUnitsController.GetAvailableInventory Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetAvailableInventory Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.OrgUnitsController.GetAvailableInventory(System.Web.Http.OData.ODataActionParameters)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.orgunitscontroller.getavailableinventory(v=AX.60)
ms:contentKeyID: 62203065
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.OrgUnitsController.GetAvailableInventory
dev_langs:
- CSharp
- C++
- VB
---

# GetAvailableInventory Method

Get available inventory across all stores for an item identifier or barcode.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Overridable Function GetAvailableInventory ( _
    parameters As ODataActionParameters _
) As IEnumerable(Of OrgUnitAvailability)
'Usage
Dim instance As OrgUnitsController
Dim parameters As ODataActionParameters
Dim returnValue As IEnumerable(Of OrgUnitAvailability)

returnValue = instance.GetAvailableInventory(parameters)
```

``` csharp
[HttpPostAttribute]
public virtual IEnumerable<OrgUnitAvailability> GetAvailableInventory(
    ODataActionParameters parameters
)
```

``` c++
[HttpPostAttribute]
public:
virtual IEnumerable<OrgUnitAvailability^>^ GetAvailableInventory(
    ODataActionParameters^ parameters
)
```

#### Parameters

  - parameters  
    Type: ODataActionParameters  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<OrgUnitAvailability\>  
The collection of store availabilities.  

## See Also

#### Reference

[OrgUnitsController Class](orgunitscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

