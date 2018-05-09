---
title: AuthenticateDeviceServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: AuthenticateDeviceServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthenticateDeviceServiceRequest.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.authenticatedeviceservicerequest.authenticatedeviceservicerequest(v=AX.60)
ms:contentKeyID: 65319310
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthenticateDeviceServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# AuthenticateDeviceServiceRequest Constructor

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

Dim instance As New AuthenticateDeviceServiceRequest(deviceNumber, _
    token)
```

``` csharp
public AuthenticateDeviceServiceRequest(
    string deviceNumber,
    string token
)
```

``` c++
public:
AuthenticateDeviceServiceRequest(
    String^ deviceNumber, 
    String^ token
)
```

#### Parameters

  - deviceNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - token  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[AuthenticateDeviceServiceRequest Class](authenticatedeviceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

