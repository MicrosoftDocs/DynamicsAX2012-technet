---
title: EmployeeDataManager.GetEmployeePermissions Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetEmployeePermissions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.EmployeeDataManager.GetEmployeePermissions(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.employeedatamanager.getemployeepermissions(v=AX.60)
ms:contentKeyID: 62204212
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.EmployeeDataManager.GetEmployeePermissions
dev_langs:
- CSharp
- C++
- VB
---

# GetEmployeePermissions Method

Gets the employee permission group for the staff identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetEmployeePermissions ( _
    staffId As String, _
    columnSet As ColumnSet _
) As EmployeePermissions
'Usage
Dim instance As EmployeeDataManager
Dim staffId As String
Dim columnSet As ColumnSet
Dim returnValue As EmployeePermissions

returnValue = instance.GetEmployeePermissions(staffId, _
    columnSet)
```

``` csharp
public EmployeePermissions GetEmployeePermissions(
    string staffId,
    ColumnSet columnSet
)
```

``` c++
public:
EmployeePermissions^ GetEmployeePermissions(
    String^ staffId, 
    ColumnSet^ columnSet
)
```

#### Parameters

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions](employeepermissions-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The employee permissions.  

## See Also

#### Reference

[EmployeeDataManager Class](employeedatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

