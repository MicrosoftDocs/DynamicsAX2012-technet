---
title: LogonCredentials Constructor (Employee, Device, CommerceIdentity) (Microsoft.Dynamics.Commerce.Runtime.Entities)
TOCTitle: LogonCredentials Constructor (Employee, Device, CommerceIdentity)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Entities.LogonCredentials.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee,Microsoft.Dynamics.Commerce.Runtime.DataModel.Device,Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.entities.logoncredentials.logoncredentials(v=AX.60)
ms:contentKeyID: 65322015
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# LogonCredentials Constructor (Employee, Device, CommerceIdentity)

Initializes a new instance of the [LogonCredentials](logoncredentials-class-microsoft-dynamics-commerce-runtime-entities.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Entities](microsoft-dynamics-commerce-runtime-entities-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    employee As Employee, _
    device As Device, _
    identity As CommerceIdentity _
)
'Usage
Dim employee As Employee
Dim device As Device
Dim identity As CommerceIdentity

Dim instance As New LogonCredentials(employee, _
    device, identity)
```

``` csharp
public LogonCredentials(
    Employee employee,
    Device device,
    CommerceIdentity identity
)
```

``` c++
public:
LogonCredentials(
    Employee^ employee, 
    Device^ device, 
    CommerceIdentity^ identity
)
```

#### Parameters

  - employee  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee](employee-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - device  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Device](device-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - identity  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity](commerceidentity-class-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[LogonCredentials Class](logoncredentials-class-microsoft-dynamics-commerce-runtime-entities.md)

[LogonCredentials Overload](logoncredentials-constructor-microsoft-dynamics-commerce-runtime-entities.md)

[Microsoft.Dynamics.Commerce.Runtime.Entities Namespace](microsoft-dynamics-commerce-runtime-entities-namespace.md)

