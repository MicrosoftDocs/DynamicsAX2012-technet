---
title: EmployeePermissions.AllowFloatingTenderDeclaration Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AllowFloatingTenderDeclaration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowFloatingTenderDeclaration
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.allowfloatingtenderdeclaration(v=AX.60)
ms:contentKeyID: 62210189
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowFloatingTenderDeclaration
dev_langs:
- CSharp
- C++
- VB
---

# AllowFloatingTenderDeclaration Property

Gets or sets a value indicating whether floating tender declaration is allowed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ALLOWFLOATINGTENDERDECLARATION")> _
<IgnoreDataMemberAttribute> _
<RequiredAttribute> _
Public Property AllowFloatingTenderDeclaration As Boolean
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Boolean

value = instance.AllowFloatingTenderDeclaration

instance.AllowFloatingTenderDeclaration = value
```

``` csharp
[ColumnAttribute("ALLOWFLOATINGTENDERDECLARATION")]
[IgnoreDataMemberAttribute]
[RequiredAttribute]
public bool AllowFloatingTenderDeclaration { get; set; }
```

``` c++
[ColumnAttribute(L"ALLOWFLOATINGTENDERDECLARATION")]
[IgnoreDataMemberAttribute]
[RequiredAttribute]
public:
property bool AllowFloatingTenderDeclaration {
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

