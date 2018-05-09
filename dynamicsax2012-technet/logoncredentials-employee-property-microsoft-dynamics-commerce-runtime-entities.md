---
title: LogonCredentials.Employee Property  (Microsoft.Dynamics.Commerce.Runtime.Entities)
TOCTitle: Employee Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Entities.LogonCredentials.Employee
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.entities.logoncredentials.employee(v=AX.60)
ms:contentKeyID: 65316265
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Entities.LogonCredentials.Employee
dev_langs:
- CSharp
- C++
- VB
---

# Employee Property

Gets or sets the employee information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Entities](microsoft-dynamics-commerce-runtime-entities-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Employee As Employee
    Get
    Set
'Usage
Dim instance As LogonCredentials
Dim value As Employee

value = instance.Employee

instance.Employee = value
```

``` csharp
[DataMemberAttribute]
public Employee Employee { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Employee^ Employee {
    Employee^ get ();
    void set (Employee^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee](employee-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Employee](employee-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[LogonCredentials Class](logoncredentials-class-microsoft-dynamics-commerce-runtime-entities.md)

[Microsoft.Dynamics.Commerce.Runtime.Entities Namespace](microsoft-dynamics-commerce-runtime-entities-namespace.md)

