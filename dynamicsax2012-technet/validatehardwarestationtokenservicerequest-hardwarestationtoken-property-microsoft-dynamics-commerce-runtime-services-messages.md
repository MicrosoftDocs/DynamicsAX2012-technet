---
title: ValidateHardwareStationTokenServiceRequest.HardwareStationToken Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: HardwareStationToken Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateHardwareStationTokenServiceRequest.HardwareStationToken
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.validatehardwarestationtokenservicerequest.hardwarestationtoken(v=AX.60)
ms:contentKeyID: 62204560
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateHardwareStationTokenServiceRequest.HardwareStationToken
dev_langs:
- CSharp
- C++
- VB
---

# HardwareStationToken Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the hardware station token.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property HardwareStationToken As String
    Get
    Private Set
'Usage
Dim instance As ValidateHardwareStationTokenServiceRequest
Dim value As String

value = instance.HardwareStationToken
```

``` csharp
[DataMemberAttribute]
public string HardwareStationToken { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ HardwareStationToken {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ValidateHardwareStationTokenServiceRequest Class](validatehardwarestationtokenservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

