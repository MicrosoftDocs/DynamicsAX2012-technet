---
title: UserLogOnServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: UserLogOnServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnServiceResponse.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee,Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnConfiguration)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.userlogonserviceresponse.userlogonserviceresponse(v=AX.60)
ms:contentKeyID: 62206080
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# UserLogOnServiceResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [UserLogOnServiceResponse](userlogonserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    employee As Employee, _
    logOnConfiguration As LogOnConfiguration _
)
'Usage
Dim employee As Employee
Dim logOnConfiguration As LogOnConfiguration

Dim instance As New UserLogOnServiceResponse(employee, _
    logOnConfiguration)
```

``` csharp
public UserLogOnServiceResponse(
    Employee employee,
    LogOnConfiguration logOnConfiguration
)
```

``` c++
public:
UserLogOnServiceResponse(
    Employee^ employee, 
    LogOnConfiguration logOnConfiguration
)
```

#### Parameters

  - employee  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee](employee-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - logOnConfiguration  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnConfiguration](logonconfiguration-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[UserLogOnServiceResponse Class](userlogonserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

