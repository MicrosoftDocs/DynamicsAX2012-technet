---
title: AuthenticateDeviceServiceRequest.DeviceNumber Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: DeviceNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthenticateDeviceServiceRequest.DeviceNumber
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.authenticatedeviceservicerequest.devicenumber(v=AX.60)
ms:contentKeyID: 62213545
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthenticateDeviceServiceRequest.DeviceNumber
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
Dim instance As AuthenticateDeviceServiceRequest
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

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[AuthenticateDeviceServiceRequest Class](authenticatedeviceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

