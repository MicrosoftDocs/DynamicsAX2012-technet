---
title: EmployeeActivity.EmployeeActivityType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EmployeeActivityType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivity.EmployeeActivityType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeeactivity.employeeactivitytype(v=AX.60)
ms:contentKeyID: 62204729
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivity.EmployeeActivityType
dev_langs:
- CSharp
- C++
- VB
---

# EmployeeActivityType Property

Gets or sets the time clock activity type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("TIMECLOCKTYPE")> _
Public Property EmployeeActivityType As EmployeeActivityType
    Get
    Set
'Usage
Dim instance As EmployeeActivity
Dim value As EmployeeActivityType

value = instance.EmployeeActivityType

instance.EmployeeActivityType = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("TIMECLOCKTYPE")]
public EmployeeActivityType EmployeeActivityType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"TIMECLOCKTYPE")]
public:
property EmployeeActivityType EmployeeActivityType {
    EmployeeActivityType get ();
    void set (EmployeeActivityType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType](employeeactivitytype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [EmployeeActivityType](employeeactivitytype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[EmployeeActivity Class](employeeactivity-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

