---
title: EmployeeActivity.BreakCategory Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BreakCategory Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivity.BreakCategory
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.employeeactivity.breakcategory(v=AX.60)
ms:contentKeyID: 62208412
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivity.BreakCategory
dev_langs:
- CSharp
- C++
- VB
---

# BreakCategory Property

Gets or sets the break category.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("BREAKCATEGORY")> _
Public Property BreakCategory As String
    Get
    Set
'Usage
Dim instance As EmployeeActivity
Dim value As String

value = instance.BreakCategory

instance.BreakCategory = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("BREAKCATEGORY")]
public string BreakCategory { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"BREAKCATEGORY")]
public:
property String^ BreakCategory {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[EmployeeActivity Class](employeeactivity-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

