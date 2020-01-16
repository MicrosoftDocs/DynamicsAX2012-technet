---
title: UserLogOnServiceResponse.Employee Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Employee Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnServiceResponse.Employee
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.userlogonserviceresponse.employee(v=AX.60)
ms:contentKeyID: 62207090
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnServiceResponse.Employee
dev_langs:
- CSharp
- C++
- VB
---

# Employee Property

Gets the employee.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Employee As Employee
    Get
    Private Set
'Usage
Dim instance As UserLogOnServiceResponse
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

[UserLogOnServiceResponse Class](userlogonserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

