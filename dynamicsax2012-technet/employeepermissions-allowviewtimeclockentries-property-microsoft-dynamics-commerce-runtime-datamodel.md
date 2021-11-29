---
title: EmployeePermissions.AllowViewTimeClockEntries Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AllowViewTimeClockEntries Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowViewTimeClockEntries
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.allowviewtimeclockentries(v=AX.60)
ms:contentKeyID: 62209796
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowViewTimeClockEntries
dev_langs:
- CSharp
- C++
- VB
---

# AllowViewTimeClockEntries Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether viewing time clock entries is allowed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<RequiredAttribute> _
<ColumnAttribute("VIEWTIMECLOCKENTRIES")> _
Public Property AllowViewTimeClockEntries As Boolean
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Boolean

value = instance.AllowViewTimeClockEntries

instance.AllowViewTimeClockEntries = value
```

``` csharp
[IgnoreDataMemberAttribute]
[RequiredAttribute]
[ColumnAttribute("VIEWTIMECLOCKENTRIES")]
public bool AllowViewTimeClockEntries { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[RequiredAttribute]
[ColumnAttribute(L"VIEWTIMECLOCKENTRIES")]
public:
property bool AllowViewTimeClockEntries {
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

