---
title: ActivateDeviceServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ActivateDeviceServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ActivateDeviceServiceRequest.#ctor(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.activatedeviceservicerequest.activatedeviceservicerequest(v=AX.60)
ms:contentKeyID: 65315608
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ActivateDeviceServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ActivateDeviceServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    deviceNumber As String, _
    terminalId As String, _
    staffId As String _
)
'Usage
Dim deviceNumber As String
Dim terminalId As String
Dim staffId As String

Dim instance As New ActivateDeviceServiceRequest(deviceNumber, _
    terminalId, staffId)
```

``` csharp
public ActivateDeviceServiceRequest(
    string deviceNumber,
    string terminalId,
    string staffId
)
```

``` c++
public:
ActivateDeviceServiceRequest(
    String^ deviceNumber, 
    String^ terminalId, 
    String^ staffId
)
```

#### Parameters

  - deviceNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ActivateDeviceServiceRequest Class](activatedeviceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

