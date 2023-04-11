---
title: SecurityManager.ActivateDevice Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: ActivateDevice Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.ActivateDevice(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.securitymanager.activatedevice(v=AX.60)
ms:contentKeyID: 62214681
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.ActivateDevice
dev_langs:
- CSharp
- C++
- VB
---

# ActivateDevice Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Activate the device.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function ActivateDevice ( _
    deviceNumber As String, _
    terminalId As String _
) As DeviceActivationResult
'Usage
Dim instance As SecurityManager
Dim deviceNumber As String
Dim terminalId As String
Dim returnValue As DeviceActivationResult

returnValue = instance.ActivateDevice(deviceNumber, _
    terminalId)
```

``` csharp
public DeviceActivationResult ActivateDevice(
    string deviceNumber,
    string terminalId
)
```

``` c++
public:
DeviceActivationResult^ ActivateDevice(
    String^ deviceNumber, 
    String^ terminalId
)
```

#### Parameters

  - deviceNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceActivationResult](deviceactivationresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Device information.  

## See Also

#### Reference

[SecurityManager Class](securitymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

