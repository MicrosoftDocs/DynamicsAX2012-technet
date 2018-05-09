---
title: EmployeePermissions.AllowTenderDeclaration Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AllowTenderDeclaration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowTenderDeclaration
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.allowtenderdeclaration(v=AX.60)
ms:contentKeyID: 62212515
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowTenderDeclaration
dev_langs:
- CSharp
- C++
- VB
---

# AllowTenderDeclaration Property

Gets or sets a value indicating whether tender declaration is allowed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<RequiredAttribute> _
<ColumnAttribute("ALLOWTENDERDECLARATION")> _
Public Property AllowTenderDeclaration As Boolean
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Boolean

value = instance.AllowTenderDeclaration

instance.AllowTenderDeclaration = value
```

``` csharp
[IgnoreDataMemberAttribute]
[RequiredAttribute]
[ColumnAttribute("ALLOWTENDERDECLARATION")]
public bool AllowTenderDeclaration { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[RequiredAttribute]
[ColumnAttribute(L"ALLOWTENDERDECLARATION")]
public:
property bool AllowTenderDeclaration {
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

