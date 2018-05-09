---
title: EmployeePermissions.AllowManageSharedShift Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AllowManageSharedShift Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowManageSharedShift
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.allowmanagesharedshift(v=AX.60)
ms:contentKeyID: 65321155
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowManageSharedShift
dev_langs:
- CSharp
- C++
- VB
---

# AllowManageSharedShift Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ALLOWMANAGESHAREDSHIFT")> _
<DataMemberAttribute> _
Public Property AllowManageSharedShift As Boolean
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Boolean

value = instance.AllowManageSharedShift

instance.AllowManageSharedShift = value
```

``` csharp
[ColumnAttribute("ALLOWMANAGESHAREDSHIFT")]
[DataMemberAttribute]
public bool AllowManageSharedShift { get; set; }
```

``` c++
[ColumnAttribute(L"ALLOWMANAGESHAREDSHIFT")]
[DataMemberAttribute]
public:
property bool AllowManageSharedShift {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[EmployeePermissions Class](employeepermissions-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

