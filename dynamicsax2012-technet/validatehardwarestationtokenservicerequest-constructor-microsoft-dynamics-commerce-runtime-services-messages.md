---
title: ValidateHardwareStationTokenServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ValidateHardwareStationTokenServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateHardwareStationTokenServiceRequest.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.validatehardwarestationtokenservicerequest.validatehardwarestationtokenservicerequest(v=AX.60)
ms:contentKeyID: 65320972
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateHardwareStationTokenServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ValidateHardwareStationTokenServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    deviceNumber As String, _
    hardwareStationToken As String _
)
'Usage
Dim deviceNumber As String
Dim hardwareStationToken As String

Dim instance As New ValidateHardwareStationTokenServiceRequest(deviceNumber, _
    hardwareStationToken)
```

``` csharp
public ValidateHardwareStationTokenServiceRequest(
    string deviceNumber,
    string hardwareStationToken
)
```

``` c++
public:
ValidateHardwareStationTokenServiceRequest(
    String^ deviceNumber, 
    String^ hardwareStationToken
)
```

#### Parameters

  - deviceNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - hardwareStationToken  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ValidateHardwareStationTokenServiceRequest Class](validatehardwarestationtokenservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

