---
title: EmployeePermissions.AllowXReportPrinting Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AllowXReportPrinting Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowXReportPrinting
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.employeepermissions.allowxreportprinting(v=AX.60)
ms:contentKeyID: 62211601
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeePermissions.AllowXReportPrinting
dev_langs:
- CSharp
- C++
- VB
---

# AllowXReportPrinting Property

Gets or sets a value indicating whether X-Report printing is allowed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ALLOWXREPORTPRINTING")> _
<IgnoreDataMemberAttribute> _
<RequiredAttribute> _
Public Property AllowXReportPrinting As Boolean
    Get
    Set
'Usage
Dim instance As EmployeePermissions
Dim value As Boolean

value = instance.AllowXReportPrinting

instance.AllowXReportPrinting = value
```

``` csharp
[ColumnAttribute("ALLOWXREPORTPRINTING")]
[IgnoreDataMemberAttribute]
[RequiredAttribute]
public bool AllowXReportPrinting { get; set; }
```

``` c++
[ColumnAttribute(L"ALLOWXREPORTPRINTING")]
[IgnoreDataMemberAttribute]
[RequiredAttribute]
public:
property bool AllowXReportPrinting {
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

