---
title: GetEmployeePermissionsResponse.Employee Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Employee Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetEmployeePermissionsResponse.Employee
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getemployeepermissionsresponse.employee(v=AX.60)
ms:contentKeyID: 62209933
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetEmployeePermissionsResponse.Employee
dev_langs:
- CSharp
- C++
- VB
---

# Employee Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the employee object.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Employee As Employee
    Get
    Private Set
'Usage
Dim instance As GetEmployeePermissionsResponse
Dim value As Employee

value = instance.Employee
```

``` csharp
[DataMemberAttribute]
public Employee Employee { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Employee^ Employee {
    Employee^ get ();
    private: void set (Employee^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee](employee-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Employee](employee-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetEmployeePermissionsResponse Class](getemployeepermissionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

