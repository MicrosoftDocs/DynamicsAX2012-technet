---
title: EmployeePermissions.AllowResetPassword Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AllowResetPassword Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowResetPassword
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.allowresetpassword(v=AX.60)
ms:contentKeyID: 62205699
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowResetPassword
dev_langs:
- CSharp
- C++
- VB
---

# AllowResetPassword Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether reset password is allowed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ALLOWRESETPASSWORD")> _
<IgnoreDataMemberAttribute> _
<RequiredAttribute> _
Public Property AllowResetPassword As Boolean
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Boolean

value = instance.AllowResetPassword

instance.AllowResetPassword = value
```

``` csharp
[ColumnAttribute("ALLOWRESETPASSWORD")]
[IgnoreDataMemberAttribute]
[RequiredAttribute]
public bool AllowResetPassword { get; set; }
```

``` c++
[ColumnAttribute(L"ALLOWRESETPASSWORD")]
[IgnoreDataMemberAttribute]
[RequiredAttribute]
public:
property bool AllowResetPassword {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[EmployeePermissions Class](employeepermissions-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

