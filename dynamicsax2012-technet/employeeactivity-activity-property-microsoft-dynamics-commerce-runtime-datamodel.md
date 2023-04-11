---
title: EmployeeActivity.Activity Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Activity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivity.Activity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeeactivity.activity(v=AX.60)
ms:contentKeyID: 62215201
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivity.Activity
dev_langs:
- CSharp
- C++
- VB
---

# Activity Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the activity of the employee.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("REGTYPE")> _
Public Property Activity As String
    Get
    Set
'Usage
Dim instance As EmployeeActivity
Dim value As String

value = instance.Activity

instance.Activity = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("REGTYPE")]
public string Activity { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"REGTYPE")]
public:
property String^ Activity {
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

