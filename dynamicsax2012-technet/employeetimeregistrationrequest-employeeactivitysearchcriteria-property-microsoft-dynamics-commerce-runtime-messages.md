---
title: EmployeeTimeRegistrationRequest.EmployeeActivitySearchCriteria Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: EmployeeActivitySearchCriteria Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.EmployeeTimeRegistrationRequest.EmployeeActivitySearchCriteria
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.employeetimeregistrationrequest.employeeactivitysearchcriteria(v=AX.60)
ms:contentKeyID: 62213896
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.EmployeeTimeRegistrationRequest.EmployeeActivitySearchCriteria
dev_langs:
- CSharp
- C++
- VB
---

# EmployeeActivitySearchCriteria Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the employee search criteria.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property EmployeeActivitySearchCriteria As EmployeeActivitySearchCriteria
    Get
    Set
'Usage
Dim instance As EmployeeTimeRegistrationRequest
Dim value As EmployeeActivitySearchCriteria

value = instance.EmployeeActivitySearchCriteria

instance.EmployeeActivitySearchCriteria = value
```

``` csharp
[DataMemberAttribute]
public EmployeeActivitySearchCriteria EmployeeActivitySearchCriteria { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property EmployeeActivitySearchCriteria^ EmployeeActivitySearchCriteria {
    EmployeeActivitySearchCriteria^ get ();
    void set (EmployeeActivitySearchCriteria^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivitySearchCriteria](employeeactivitysearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [EmployeeActivitySearchCriteria](employeeactivitysearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[EmployeeTimeRegistrationRequest Class](employeetimeregistrationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

