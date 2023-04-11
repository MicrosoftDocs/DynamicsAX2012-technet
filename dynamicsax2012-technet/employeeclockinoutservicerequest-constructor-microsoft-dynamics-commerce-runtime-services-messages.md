---
title: EmployeeClockInOutServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: EmployeeClockInOutServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.EmployeeClockInOutServiceRequest.#ctor(System.String,System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.employeeclockinoutservicerequest.employeeclockinoutservicerequest(v=AX.60)
ms:contentKeyID: 65321226
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.EmployeeClockInOutServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# EmployeeClockInOutServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    userId As String, _
    terminalId As String, _
    clockIn As Boolean _
)
'Usage
Dim userId As String
Dim terminalId As String
Dim clockIn As Boolean

Dim instance As New EmployeeClockInOutServiceRequest(userId, _
    terminalId, clockIn)
```

``` csharp
public EmployeeClockInOutServiceRequest(
    string userId,
    string terminalId,
    bool clockIn
)
```

``` c++
public:
EmployeeClockInOutServiceRequest(
    String^ userId, 
    String^ terminalId, 
    bool clockIn
)
```

#### Parameters

  - userId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - clockIn  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[EmployeeClockInOutServiceRequest Class](employeeclockinoutservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

