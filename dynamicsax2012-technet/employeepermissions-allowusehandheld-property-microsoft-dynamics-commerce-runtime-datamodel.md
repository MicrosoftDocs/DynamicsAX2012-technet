---
title: EmployeePermissions.AllowUseHandheld Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AllowUseHandheld Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowUseHandheld
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.allowusehandheld(v=AX.60)
ms:contentKeyID: 62210175
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowUseHandheld
dev_langs:
- CSharp
- C++
- VB
---

# AllowUseHandheld Property

Gets or sets a value indicating whether employee can use handheld devices.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<RequiredAttribute> _
<ColumnAttribute("USEHANDHELD")> _
Public Property AllowUseHandheld As Boolean
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Boolean

value = instance.AllowUseHandheld

instance.AllowUseHandheld = value
```

``` csharp
[IgnoreDataMemberAttribute]
[RequiredAttribute]
[ColumnAttribute("USEHANDHELD")]
public bool AllowUseHandheld { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[RequiredAttribute]
[ColumnAttribute(L"USEHANDHELD")]
public:
property bool AllowUseHandheld {
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

