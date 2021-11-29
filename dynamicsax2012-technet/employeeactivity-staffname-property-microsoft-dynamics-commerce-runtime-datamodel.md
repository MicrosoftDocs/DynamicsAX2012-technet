---
title: EmployeeActivity.StaffName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StaffName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivity.StaffName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeeactivity.staffname(v=AX.60)
ms:contentKeyID: 62209808
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivity.StaffName
dev_langs:
- CSharp
- C++
- VB
---

# StaffName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the Name of the employee.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("NAME")> _
Public Property StaffName As String
    Get
    Set
'Usage
Dim instance As EmployeeActivity
Dim value As String

value = instance.StaffName

instance.StaffName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("NAME")]
public string StaffName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"NAME")]
public:
property String^ StaffName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[EmployeeActivity Class](employeeactivity-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

