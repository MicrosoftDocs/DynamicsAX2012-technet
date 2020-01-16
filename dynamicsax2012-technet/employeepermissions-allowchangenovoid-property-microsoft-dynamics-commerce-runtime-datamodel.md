---
title: EmployeePermissions.AllowChangeNoVoid Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AllowChangeNoVoid Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowChangeNoVoid
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.allowchangenovoid(v=AX.60)
ms:contentKeyID: 62207448
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowChangeNoVoid
dev_langs:
- CSharp
- C++
- VB
---

# AllowChangeNoVoid Property

Gets or sets a value indicating whether AllowChangeNoVoid is allowed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("ALLOWCHANGENOVOID")> _
<RequiredAttribute> _
Public Property AllowChangeNoVoid As Boolean
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Boolean

value = instance.AllowChangeNoVoid

instance.AllowChangeNoVoid = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("ALLOWCHANGENOVOID")]
[RequiredAttribute]
public bool AllowChangeNoVoid { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"ALLOWCHANGENOVOID")]
[RequiredAttribute]
public:
property bool AllowChangeNoVoid {
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

