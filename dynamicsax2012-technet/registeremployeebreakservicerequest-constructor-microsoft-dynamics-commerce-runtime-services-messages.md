---
title: RegisterEmployeeBreakServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: RegisterEmployeeBreakServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.RegisterEmployeeBreakServiceRequest.#ctor(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.registeremployeebreakservicerequest.registeremployeebreakservicerequest(v=AX.60)
ms:contentKeyID: 65322677
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.RegisterEmployeeBreakServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# RegisterEmployeeBreakServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    userId As String, _
    terminalId As String, _
    jobId As String _
)
'Usage
Dim userId As String
Dim terminalId As String
Dim jobId As String

Dim instance As New RegisterEmployeeBreakServiceRequest(userId, _
    terminalId, jobId)
```

``` csharp
public RegisterEmployeeBreakServiceRequest(
    string userId,
    string terminalId,
    string jobId
)
```

``` c++
public:
RegisterEmployeeBreakServiceRequest(
    String^ userId, 
    String^ terminalId, 
    String^ jobId
)
```

#### Parameters

  - userId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - jobId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[RegisterEmployeeBreakServiceRequest Class](registeremployeebreakservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

