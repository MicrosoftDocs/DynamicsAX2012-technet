---
title: Employee.Permissions Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Permissions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee.Permissions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employee.permissions(v=AX.60)
ms:contentKeyID: 62211005
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee.Permissions
dev_langs:
- CSharp
- C++
- VB
---

# Permissions Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the employee permission settings.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Permissions As EmployeePermissions
    Get
    Set
'Usage
Dim instance As Employee
Dim value As EmployeePermissions

value = instance.Permissions

instance.Permissions = value
```

``` csharp
[DataMemberAttribute]
public EmployeePermissions Permissions { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property EmployeePermissions^ Permissions {
    EmployeePermissions^ get ();
    void set (EmployeePermissions^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions](employeepermissions-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The Permissions for the employee.  

## See Also

#### Reference

[Employee Class](employee-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

