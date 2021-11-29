---
title: EmployeePermissions.AllowMultipleShiftLogOn Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AllowMultipleShiftLogOn Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowMultipleShiftLogOn
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.allowmultipleshiftlogon(v=AX.60)
ms:contentKeyID: 62212107
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowMultipleShiftLogOn
dev_langs:
- CSharp
- C++
- VB
---

# AllowMultipleShiftLogOn Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether multiple shift logons are allowed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("ALLOWMULTIPLESHIFTLOGON")> _
<RequiredAttribute> _
Public Property AllowMultipleShiftLogOn As Boolean
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Boolean

value = instance.AllowMultipleShiftLogOn

instance.AllowMultipleShiftLogOn = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("ALLOWMULTIPLESHIFTLOGON")]
[RequiredAttribute]
public bool AllowMultipleShiftLogOn { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"ALLOWMULTIPLESHIFTLOGON")]
[RequiredAttribute]
public:
property bool AllowMultipleShiftLogOn {
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

