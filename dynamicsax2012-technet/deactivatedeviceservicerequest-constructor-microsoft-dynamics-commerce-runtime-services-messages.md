---
title: DeactivateDeviceServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: DeactivateDeviceServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DeactivateDeviceServiceRequest.#ctor(System.String,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.deactivatedeviceservicerequest.deactivatedeviceservicerequest(v=AX.60)
ms:contentKeyID: 65318876
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.DeactivateDeviceServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# DeactivateDeviceServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    deviceNumber As String, _
    terminalId As String, _
    staffId As String, _
    deviceToken As String _
)
'Usage
Dim deviceNumber As String
Dim terminalId As String
Dim staffId As String
Dim deviceToken As String

Dim instance As New DeactivateDeviceServiceRequest(deviceNumber, _
    terminalId, staffId, deviceToken)
```

``` csharp
public DeactivateDeviceServiceRequest(
    string deviceNumber,
    string terminalId,
    string staffId,
    string deviceToken
)
```

``` c++
public:
DeactivateDeviceServiceRequest(
    String^ deviceNumber, 
    String^ terminalId, 
    String^ staffId, 
    String^ deviceToken
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

<!-- end list -->

  - deviceToken  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[DeactivateDeviceServiceRequest Class](deactivatedeviceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

