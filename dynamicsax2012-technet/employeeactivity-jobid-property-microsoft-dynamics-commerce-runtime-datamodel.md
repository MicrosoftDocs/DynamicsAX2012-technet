---
title: EmployeeActivity.JobId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: JobId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivity.JobId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employeeactivity.jobid(v=AX.60)
ms:contentKeyID: 62207299
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivity.JobId
dev_langs:
- CSharp
- C++
- VB
---

# JobId Property

Gets or sets the job identifier for the corresponding activity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("JOBID")> _
<IgnoreDataMemberAttribute> _
Public Property JobId As String
    Get
    Set
'Usage
Dim instance As EmployeeActivity
Dim value As String

value = instance.JobId

instance.JobId = value
```

``` csharp
[ColumnAttribute("JOBID")]
[IgnoreDataMemberAttribute]
public string JobId { get; set; }
```

``` c++
[ColumnAttribute(L"JOBID")]
[IgnoreDataMemberAttribute]
public:
property String^ JobId {
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

