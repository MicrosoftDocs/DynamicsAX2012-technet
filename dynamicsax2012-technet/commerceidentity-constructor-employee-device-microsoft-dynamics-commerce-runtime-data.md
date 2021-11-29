---
title: CommerceIdentity Constructor (Employee, Device) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: CommerceIdentity Constructor (Employee, Device)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee,Microsoft.Dynamics.Commerce.Runtime.DataModel.Device)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.commerceidentity.commerceidentity(v=AX.60)
ms:contentKeyID: 62209793
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CommerceIdentity Constructor (Employee, Device)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [CommerceIdentity](commerceidentity-class-microsoft-dynamics-commerce-runtime-data.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    employee As Employee, _
    device As Device _
)
'Usage
Dim employee As Employee
Dim device As Device

Dim instance As New CommerceIdentity(employee, _
    device)
```

``` csharp
public CommerceIdentity(
    Employee employee,
    Device device
)
```

``` c++
public:
CommerceIdentity(
    Employee^ employee, 
    Device^ device
)
```

#### Parameters

  - employee  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee](employee-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - device  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Device](device-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CommerceIdentity Class](commerceidentity-class-microsoft-dynamics-commerce-runtime-data.md)

[CommerceIdentity Overload](commerceidentity-constructor-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

