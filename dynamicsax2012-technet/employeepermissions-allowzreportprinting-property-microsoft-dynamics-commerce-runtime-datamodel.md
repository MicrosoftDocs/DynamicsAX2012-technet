---
title: EmployeePermissions.AllowZReportPrinting Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AllowZReportPrinting Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowZReportPrinting
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.allowzreportprinting(v=AX.60)
ms:contentKeyID: 62212618
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowZReportPrinting
dev_langs:
- CSharp
- C++
- VB
---

# AllowZReportPrinting Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether Z-Report printing is allowed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("ALLOWZREPORTPRINTING")> _
<RequiredAttribute> _
Public Property AllowZReportPrinting As Boolean
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Boolean

value = instance.AllowZReportPrinting

instance.AllowZReportPrinting = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("ALLOWZREPORTPRINTING")]
[RequiredAttribute]
public bool AllowZReportPrinting { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"ALLOWZREPORTPRINTING")]
[RequiredAttribute]
public:
property bool AllowZReportPrinting {
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

