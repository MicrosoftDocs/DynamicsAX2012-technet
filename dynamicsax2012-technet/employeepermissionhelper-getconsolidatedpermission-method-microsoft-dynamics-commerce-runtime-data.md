---
title: EmployeePermissionHelper.GetConsolidatedPermission Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetConsolidatedPermission Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.EmployeePermissionHelper.GetConsolidatedPermission(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions},Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.employeepermissionhelper.getconsolidatedpermission(v=AX.60)
ms:contentKeyID: 65317483
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.EmployeePermissionHelper.GetConsolidatedPermission
dev_langs:
- CSharp
- C++
- VB
---

# GetConsolidatedPermission Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Helper method to get consolidated permission.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetConsolidatedPermission ( _
    employeePermissionsCollection As IEnumerable(Of EmployeePermissions), _
    overriddenPermission As EmployeePermissions _
) As EmployeePermissions
'Usage
Dim employeePermissionsCollection As IEnumerable(Of EmployeePermissions)
Dim overriddenPermission As EmployeePermissions
Dim returnValue As EmployeePermissions

returnValue = EmployeePermissionHelper.GetConsolidatedPermission(employeePermissionsCollection, _
    overriddenPermission)
```

``` csharp
public static EmployeePermissions GetConsolidatedPermission(
    IEnumerable<EmployeePermissions> employeePermissionsCollection,
    EmployeePermissions overriddenPermission
)
```

``` c++
public:
static EmployeePermissions^ GetConsolidatedPermission(
    IEnumerable<EmployeePermissions^>^ employeePermissionsCollection, 
    EmployeePermissions^ overriddenPermission
)
```

#### Parameters

  - employeePermissionsCollection  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[EmployeePermissions](employeepermissions-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - overriddenPermission  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions](employeepermissions-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions](employeepermissions-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The employee permissions.  

## See Also

#### Reference

[EmployeePermissionHelper Class](employeepermissionhelper-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

