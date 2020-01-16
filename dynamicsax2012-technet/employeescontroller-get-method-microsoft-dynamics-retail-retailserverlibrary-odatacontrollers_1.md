---
title: EmployeesController.Get Method  (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers)
TOCTitle: Get Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers.EmployeesController.Get
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.odatacontrollers.employeescontroller.get(v=AX.60)
ms:contentKeyID: 62202205
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Get Method

Gets Employees as IQueryable.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<CommerceAuthorizationAttribute(AllowedRetailRoles := , CheckRetailOperation := False)> _
Public Overrides Function Get As IQueryable(Of Employee)
'Usage
Dim instance As EmployeesController
Dim returnValue As IQueryable(Of Employee)

returnValue = instance.Get()
```

``` csharp
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public override IQueryable<Employee> Get()
```

``` c++
[CommerceAuthorizationAttribute(AllowedRetailRoles = , CheckRetailOperation = false)]
public:
virtual IQueryable<Employee^>^ Get() override
```

#### Return Value

Type: [System.Linq.IQueryable](https://technet.microsoft.com/library/bb351562\(v=ax.60\))\<Employee\>  
The [IQueryable](https://technet.microsoft.com/library/bb495796\(v=ax.60\)) of Employee.  

## See Also

#### Reference

[EmployeesController Class](employeescontroller-class-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Get Overload](employeescontroller-get-method-microsoft-dynamics-retail-retailserverlibrary-odatacontrollers.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataControllers Namespace](microsoft-dynamics-retail-retailserverlibrary-odatacontrollers-namespace.md)

