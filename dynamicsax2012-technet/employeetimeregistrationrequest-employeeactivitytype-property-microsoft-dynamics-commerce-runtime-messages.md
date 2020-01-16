---
title: EmployeeTimeRegistrationRequest.EmployeeActivityType Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: EmployeeActivityType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.EmployeeTimeRegistrationRequest.EmployeeActivityType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.employeetimeregistrationrequest.employeeactivitytype(v=AX.60)
ms:contentKeyID: 62207886
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.EmployeeTimeRegistrationRequest.EmployeeActivityType
dev_langs:
- CSharp
- C++
- VB
---

# EmployeeActivityType Property

Gets or sets the employee activity type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property EmployeeActivityType As EmployeeActivityType
    Get
    Set
'Usage
Dim instance As EmployeeTimeRegistrationRequest
Dim value As EmployeeActivityType

value = instance.EmployeeActivityType

instance.EmployeeActivityType = value
```

``` csharp
[DataMemberAttribute]
public EmployeeActivityType EmployeeActivityType { get; set; }
```

``` c++
[DataMemberAttribute]
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

[EmployeeTimeRegistrationRequest Class](employeetimeregistrationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

