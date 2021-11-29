---
title: OrgUnitsController.Get Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: Get Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.OrgUnitsController.Get
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.orgunitscontroller.get(v=AX.60)
ms:contentKeyID: 62202211
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Get Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets all organization as [IQueryable](https://technet.microsoft.com/library/bb495796\(v=ax.60\)).

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Overrides Function Get As IQueryable(Of OrgUnit)
'Usage
Dim instance As OrgUnitsController
Dim returnValue As IQueryable(Of OrgUnit)

returnValue = instance.Get()
```

``` csharp
public override IQueryable<OrgUnit> Get()
```

``` c++
public:
virtual IQueryable<OrgUnit^>^ Get() override
```

#### Return Value

Type: [System.Linq.IQueryable](https://technet.microsoft.com/library/bb351562\(v=ax.60\))\<OrgUnit\>  
The [IQueryable](https://technet.microsoft.com/library/bb495796\(v=ax.60\)) of OrgUnit.  

## See Also

#### Reference

[OrgUnitsController Class](orgunitscontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Get Overload](orgunitscontroller-get-method-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

