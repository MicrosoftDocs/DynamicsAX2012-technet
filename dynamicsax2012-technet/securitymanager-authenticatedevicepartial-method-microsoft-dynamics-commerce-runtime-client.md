---
title: SecurityManager.AuthenticateDevicePartial Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: AuthenticateDevicePartial Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.AuthenticateDevicePartial(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.securitymanager.authenticatedevicepartial(v=AX.60)
ms:contentKeyID: 62210045
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.AuthenticateDevicePartial
dev_langs:
- CSharp
- C++
- VB
---

# AuthenticateDevicePartial Method

Authenticates the device.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function AuthenticateDevicePartial ( _
    deviceId As String, _
    deviceToken As String _
) As Device
'Usage
Dim instance As SecurityManager
Dim deviceId As String
Dim deviceToken As String
Dim returnValue As Device

returnValue = instance.AuthenticateDevicePartial(deviceId, _
    deviceToken)
```

``` csharp
public Device AuthenticateDevicePartial(
    string deviceId,
    string deviceToken
)
```

``` c++
public:
Device^ AuthenticateDevicePartial(
    String^ deviceId, 
    String^ deviceToken
)
```

#### Parameters

  - deviceId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - deviceToken  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Device](device-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The device.  

## See Also

#### Reference

[SecurityManager Class](securitymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

