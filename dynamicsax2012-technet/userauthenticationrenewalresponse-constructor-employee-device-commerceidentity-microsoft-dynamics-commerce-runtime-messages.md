---
title: UserAuthenticationRenewalResponse Constructor (Employee, Device, CommerceIdentity) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: UserAuthenticationRenewalResponse Constructor (Employee, Device, CommerceIdentity)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.UserAuthenticationRenewalResponse.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee,Microsoft.Dynamics.Commerce.Runtime.DataModel.Device,Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.userauthenticationrenewalresponse.userauthenticationrenewalresponse(v=AX.60)
ms:contentKeyID: 62212172
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# UserAuthenticationRenewalResponse Constructor (Employee, Device, CommerceIdentity)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [UserAuthenticationRenewalResponse](userauthenticationrenewalresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

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

Dim instance As New UserAuthenticationRenewalResponse(employee, _
    device, identity)
```

``` csharp
public UserAuthenticationRenewalResponse(
    Employee employee,
    Device device,
    CommerceIdentity identity
)
```

``` c++
public:
UserAuthenticationRenewalResponse(
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

[UserAuthenticationRenewalResponse Class](userauthenticationrenewalresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[UserAuthenticationRenewalResponse Overload](userauthenticationrenewalresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

