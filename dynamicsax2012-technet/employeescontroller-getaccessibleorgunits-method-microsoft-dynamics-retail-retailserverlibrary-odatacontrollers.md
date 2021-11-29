---
title: EmployeesController.GetAccessibleOrgUnits Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetAccessibleOrgUnits Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.EmployeesController.GetAccessibleOrgUnits
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.employeescontroller.getaccessibleorgunits(v=AX.60)
ms:contentKeyID: 62201788
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.EmployeesController.GetAccessibleOrgUnits
dev_langs:
- CSharp
- C++
- VB
---

# GetAccessibleOrgUnits Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the employee registered organization units from address book.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
Public Function GetAccessibleOrgUnits As IEnumerable(Of OrgUnit)
'Usage
Dim instance As EmployeesController
Dim returnValue As IEnumerable(Of OrgUnit)

returnValue = instance.GetAccessibleOrgUnits()
```

``` csharp
[HttpPostAttribute]
public IEnumerable<OrgUnit> GetAccessibleOrgUnits()
```

``` c++
[HttpPostAttribute]
public:
IEnumerable<OrgUnit^>^ GetAccessibleOrgUnits()
```

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<OrgUnit\>  
The collection of organization units.  

## See Also

#### Reference

[EmployeesController Class](employeescontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

