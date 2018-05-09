---
title: EmployeePermissions.HasManagerPrivileges Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: HasManagerPrivileges Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.HasManagerPrivileges
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.hasmanagerprivileges(v=AX.60)
ms:contentKeyID: 62211877
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.HasManagerPrivileges
dev_langs:
- CSharp
- C++
- VB
---

# HasManagerPrivileges Property

Gets or sets a value indicating whether this employee has manager privileges.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<IgnoreDataMemberAttribute> _
<ColumnAttribute("MANAGERPRIVILEGES")> _
Public Property HasManagerPrivileges As Boolean
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Boolean

value = instance.HasManagerPrivileges

instance.HasManagerPrivileges = value
```

``` csharp
[RequiredAttribute]
[IgnoreDataMemberAttribute]
[ColumnAttribute("MANAGERPRIVILEGES")]
public bool HasManagerPrivileges { get; set; }
```

``` c++
[RequiredAttribute]
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"MANAGERPRIVILEGES")]
public:
property bool HasManagerPrivileges {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[EmployeePermissions Class](employeepermissions-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

