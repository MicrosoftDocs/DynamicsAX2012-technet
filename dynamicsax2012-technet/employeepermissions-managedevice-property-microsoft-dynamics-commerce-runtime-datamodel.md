---
title: EmployeePermissions.ManageDevice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ManageDevice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.ManageDevice
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.managedevice(v=AX.60)
ms:contentKeyID: 62209074
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.ManageDevice
dev_langs:
- CSharp
- C++
- VB
---

# ManageDevice Property

Gets or sets a value indicating whether device management is allowed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<ColumnAttribute("MANAGEDEVICE")> _
<IgnoreDataMemberAttribute> _
Public Property ManageDevice As Boolean
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Boolean

value = instance.ManageDevice

instance.ManageDevice = value
```

``` csharp
[RequiredAttribute]
[ColumnAttribute("MANAGEDEVICE")]
[IgnoreDataMemberAttribute]
public bool ManageDevice { get; set; }
```

``` c++
[RequiredAttribute]
[ColumnAttribute(L"MANAGEDEVICE")]
[IgnoreDataMemberAttribute]
public:
property bool ManageDevice {
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

