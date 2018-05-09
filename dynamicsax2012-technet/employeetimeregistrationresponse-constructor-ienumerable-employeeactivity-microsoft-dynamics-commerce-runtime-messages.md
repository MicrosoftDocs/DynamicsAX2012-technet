---
title: EmployeeTimeRegistrationResponse Constructor (IEnumerable(EmployeeActivity)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: EmployeeTimeRegistrationResponse Constructor (IEnumerable(EmployeeActivity))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.EmployeeTimeRegistrationResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivity})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.employeetimeregistrationresponse.employeetimeregistrationresponse(v=AX.60)
ms:contentKeyID: 62214182
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# EmployeeTimeRegistrationResponse Constructor (IEnumerable(EmployeeActivity))

Initializes a new instance of the [EmployeeTimeRegistrationResponse](employeetimeregistrationresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    employeeActivities As IEnumerable(Of EmployeeActivity) _
)
'Usage
Dim employeeActivities As IEnumerable(Of EmployeeActivity)

Dim instance As New EmployeeTimeRegistrationResponse(employeeActivities)
```

``` csharp
public EmployeeTimeRegistrationResponse(
    IEnumerable<EmployeeActivity> employeeActivities
)
```

``` c++
public:
EmployeeTimeRegistrationResponse(
    IEnumerable<EmployeeActivity^>^ employeeActivities
)
```

#### Parameters

  - employeeActivities  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[EmployeeActivity](employeeactivity-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[EmployeeTimeRegistrationResponse Class](employeetimeregistrationresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[EmployeeTimeRegistrationResponse Overload](employeetimeregistrationresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

