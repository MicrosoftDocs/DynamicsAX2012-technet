---
title: Employee.CultureName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CultureName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee.CultureName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.employee.culturename(v=AX.60)
ms:contentKeyID: 62208668
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee.CultureName
dev_langs:
- CSharp
- C++
- VB
---

# CultureName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the culture name of the employee.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CULTURENAME")> _
<DataMemberAttribute> _
Public Property CultureName As String
    Get
    Set
'Usage
Dim instance As Employee
Dim value As String

value = instance.CultureName

instance.CultureName = value
```

``` csharp
[ColumnAttribute("CULTURENAME")]
[DataMemberAttribute]
public string CultureName { get; set; }
```

``` c++
[ColumnAttribute(L"CULTURENAME")]
[DataMemberAttribute]
public:
property String^ CultureName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The culture name of the employee.  

## See Also

#### Reference

[Employee Class](employee-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

