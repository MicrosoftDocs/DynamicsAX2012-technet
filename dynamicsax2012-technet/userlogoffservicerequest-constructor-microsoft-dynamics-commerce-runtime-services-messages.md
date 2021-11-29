---
title: UserLogOffServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: UserLogOffServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOffServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.Device,System.String,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnConfiguration)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.userlogoffservicerequest.userlogoffservicerequest(v=AX.60)
ms:contentKeyID: 65319885
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOffServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# UserLogOffServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    device As Device, _
    staffId As String, _
    authenticationProvider As String, _
    logOnConfiguration As LogOnConfiguration _
)
'Usage
Dim device As Device
Dim staffId As String
Dim authenticationProvider As String
Dim logOnConfiguration As LogOnConfiguration

Dim instance As New UserLogOffServiceRequest(device, _
    staffId, authenticationProvider, _
    logOnConfiguration)
```

``` csharp
public UserLogOffServiceRequest(
    Device device,
    string staffId,
    string authenticationProvider,
    LogOnConfiguration logOnConfiguration
)
```

``` c++
public:
UserLogOffServiceRequest(
    Device^ device, 
    String^ staffId, 
    String^ authenticationProvider, 
    LogOnConfiguration logOnConfiguration
)
```

#### Parameters

  - device  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Device](device-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - authenticationProvider  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - logOnConfiguration  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnConfiguration](logonconfiguration-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[UserLogOffServiceRequest Class](userlogoffservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

