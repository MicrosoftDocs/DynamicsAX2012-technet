---
title: AuthenticateDevicePartialServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: AuthenticateDevicePartialServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthenticateDevicePartialServiceRequest.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.authenticatedevicepartialservicerequest.authenticatedevicepartialservicerequest(v=AX.60)
ms:contentKeyID: 65318618
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthenticateDevicePartialServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# AuthenticateDevicePartialServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    deviceNumber As String, _
    token As String _
)
'Usage
Dim deviceNumber As String
Dim token As String

Dim instance As New AuthenticateDevicePartialServiceRequest(deviceNumber, _
    token)
```

``` csharp
public AuthenticateDevicePartialServiceRequest(
    string deviceNumber,
    string token
)
```

``` c++
public:
AuthenticateDevicePartialServiceRequest(
    String^ deviceNumber, 
    String^ token
)
```

#### Parameters

  - deviceNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - token  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[AuthenticateDevicePartialServiceRequest Class](authenticatedevicepartialservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

