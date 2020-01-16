---
title: ValidateHardwareStationTokenServiceRequest.DeviceNumber Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: DeviceNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateHardwareStationTokenServiceRequest.DeviceNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.validatehardwarestationtokenservicerequest.devicenumber(v=AX.60)
ms:contentKeyID: 62209280
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateHardwareStationTokenServiceRequest.DeviceNumber
dev_langs:
- CSharp
- C++
- VB
---

# DeviceNumber Property

Gets the device number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeviceNumber As String
    Get
    Private Set
'Usage
Dim instance As ValidateHardwareStationTokenServiceRequest
Dim value As String

value = instance.DeviceNumber
```

``` csharp
[DataMemberAttribute]
public string DeviceNumber { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ DeviceNumber {
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

