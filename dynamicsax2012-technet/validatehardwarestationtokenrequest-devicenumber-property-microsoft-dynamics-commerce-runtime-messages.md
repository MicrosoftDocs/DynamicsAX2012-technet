---
title: ValidateHardwareStationTokenRequest.DeviceNumber Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: DeviceNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.ValidateHardwareStationTokenRequest.DeviceNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.validatehardwarestationtokenrequest.devicenumber(v=AX.60)
ms:contentKeyID: 62208424
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.ValidateHardwareStationTokenRequest.DeviceNumber
dev_langs:
- CSharp
- C++
- VB
---

# DeviceNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the device number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeviceNumber As String
    Get
    Set
'Usage
Dim instance As ValidateHardwareStationTokenRequest
Dim value As String

value = instance.DeviceNumber

instance.DeviceNumber = value
```

``` csharp
[DataMemberAttribute]
public string DeviceNumber { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ DeviceNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The device number.  

## See Also

#### Reference

[ValidateHardwareStationTokenRequest Class](validatehardwarestationtokenrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

