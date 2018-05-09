---
title: EmployeeActivity.StoreNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StoreNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivity.StoreNumber
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.employeeactivity.storenumber(v=AX.60)
ms:contentKeyID: 62213308
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivity.StoreNumber
dev_langs:
- CSharp
- C++
- VB
---

# StoreNumber Property

Gets or sets the store number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STORENUMBER")> _
<DataMemberAttribute> _
Public Property StoreNumber As String
    Get
    Set
'Usage
Dim instance As EmployeeActivity
Dim value As String

value = instance.StoreNumber

instance.StoreNumber = value
```

``` csharp
[ColumnAttribute("STORENUMBER")]
[DataMemberAttribute]
public string StoreNumber { get; set; }
```

``` c++
[ColumnAttribute(L"STORENUMBER")]
[DataMemberAttribute]
public:
property String^ StoreNumber {
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

