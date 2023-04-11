---
title: EmployeeManager.RegisterActivity Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: RegisterActivity Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.EmployeeManager.RegisterActivity(Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.employeemanager.registeractivity(v=AX.60)
ms:contentKeyID: 62208057
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.EmployeeManager.RegisterActivity
dev_langs:
- CSharp
- C++
- VB
---

# RegisterActivity Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Registers the activity of the employee and returns the date time.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function RegisterActivity ( _
    activityType As EmployeeActivityType _
) As DateTimeOffset
'Usage
Dim instance As EmployeeManager
Dim activityType As EmployeeActivityType
Dim returnValue As DateTimeOffset

returnValue = instance.RegisterActivity(activityType)
```

``` csharp
public DateTimeOffset RegisterActivity(
    EmployeeActivityType activityType
)
```

``` c++
public:
DateTimeOffset RegisterActivity(
    EmployeeActivityType activityType
)
```

#### Parameters

  - activityType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivityType](employeeactivitytype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns the activity date and time offset currently performed.  

## See Also

#### Reference

[EmployeeManager Class](employeemanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

