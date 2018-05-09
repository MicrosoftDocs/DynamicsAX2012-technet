---
title: EmployeePermissions.AllowOpenDrawer Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AllowOpenDrawer Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowOpenDrawer
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.allowopendrawer(v=AX.60)
ms:contentKeyID: 62209581
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowOpenDrawer
dev_langs:
- CSharp
- C++
- VB
---

# AllowOpenDrawer Property

Gets or sets a value indicating whether opening the drawer is allowed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("ALLOWOPENDRAWERONLY")> _
<RequiredAttribute> _
Public Property AllowOpenDrawer As Boolean
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Boolean

value = instance.AllowOpenDrawer

instance.AllowOpenDrawer = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("ALLOWOPENDRAWERONLY")]
[RequiredAttribute]
public bool AllowOpenDrawer { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"ALLOWOPENDRAWERONLY")]
[RequiredAttribute]
public:
property bool AllowOpenDrawer {
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

