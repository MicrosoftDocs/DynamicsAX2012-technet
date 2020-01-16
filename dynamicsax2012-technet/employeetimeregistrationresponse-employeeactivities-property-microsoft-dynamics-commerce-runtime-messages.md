---
title: EmployeeTimeRegistrationResponse.EmployeeActivities Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: EmployeeActivities Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.EmployeeTimeRegistrationResponse.EmployeeActivities
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.employeetimeregistrationresponse.employeeactivities(v=AX.60)
ms:contentKeyID: 62208712
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.EmployeeTimeRegistrationResponse.EmployeeActivities
dev_langs:
- CSharp
- C++
- VB
---

# EmployeeActivities Property

Gets the employee activity details.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property EmployeeActivities As ReadOnlyCollection(Of EmployeeActivity)
    Get
    Private Set
'Usage
Dim instance As EmployeeTimeRegistrationResponse
Dim value As ReadOnlyCollection(Of EmployeeActivity)

value = instance.EmployeeActivities
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<EmployeeActivity> EmployeeActivities { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<EmployeeActivity^>^ EmployeeActivities {
    ReadOnlyCollection<EmployeeActivity^>^ get ();
    private: void set (ReadOnlyCollection<EmployeeActivity^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[EmployeeActivity](employeeactivity-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[EmployeeTimeRegistrationResponse Class](employeetimeregistrationresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

