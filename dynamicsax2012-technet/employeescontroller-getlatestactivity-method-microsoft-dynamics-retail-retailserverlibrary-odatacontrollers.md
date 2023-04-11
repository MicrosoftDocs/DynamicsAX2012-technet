---
title: EmployeesController.GetLatestActivity Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: GetLatestActivity Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.EmployeesController.GetLatestActivity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.employeescontroller.getlatestactivity(v=AX.60)
ms:contentKeyID: 62202521
author: tonyafehr
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.EmployeesController.GetLatestActivity
dev_langs:
- CSharp
- C++
- VB
---

# GetLatestActivity Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the latest employee activity.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<HttpPostAttribute> _
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := True,  _
    RetailOperationId := RetailOperation.TimeRegistration)> _
Public Overridable Function GetLatestActivity As EmployeeActivity
'Usage
Dim instance As EmployeesController
Dim returnValue As EmployeeActivity

returnValue = instance.GetLatestActivity()
```

``` csharp
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation.TimeRegistration)]
public virtual EmployeeActivity GetLatestActivity()
```

``` c++
[HttpPostAttribute]
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = true, 
    RetailOperationId = RetailOperation::TimeRegistration)]
public:
virtual EmployeeActivity^ GetLatestActivity()
```

#### Return Value

Type: EmployeeActivity  
The EmployeeActivity.  

## See Also

#### Reference

[EmployeesController Class](employeescontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

