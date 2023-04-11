---
title: EmployeePermissions.AllowBlindClose Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AllowBlindClose Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowBlindClose
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.allowblindclose(v=AX.60)
ms:contentKeyID: 62213992
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowBlindClose
dev_langs:
- CSharp
- C++
- VB
---

# AllowBlindClose Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether employee is allowed to blind close.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<ColumnAttribute("ALLOWBLINDCLOSE")> _
<IgnoreDataMemberAttribute> _
Public Property AllowBlindClose As Boolean
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Boolean

value = instance.AllowBlindClose

instance.AllowBlindClose = value
```

``` csharp
[RequiredAttribute]
[ColumnAttribute("ALLOWBLINDCLOSE")]
[IgnoreDataMemberAttribute]
public bool AllowBlindClose { get; set; }
```

``` c++
[RequiredAttribute]
[ColumnAttribute(L"ALLOWBLINDCLOSE")]
[IgnoreDataMemberAttribute]
public:
property bool AllowBlindClose {
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

