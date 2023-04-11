---
title: SecurityManager.ValidateHardwareStationToken Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: ValidateHardwareStationToken Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.ValidateHardwareStationToken(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.securitymanager.validatehardwarestationtoken(v=AX.60)
ms:contentKeyID: 62210675
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.ValidateHardwareStationToken
dev_langs:
- CSharp
- C++
- VB
---

# ValidateHardwareStationToken Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Validates the hardware station token.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function ValidateHardwareStationToken ( _
    deviceNumber As String, _
    hardwareStationToken As String _
) As ValidateHardwareStationTokenResult
'Usage
Dim instance As SecurityManager
Dim deviceNumber As String
Dim hardwareStationToken As String
Dim returnValue As ValidateHardwareStationTokenResult

returnValue = instance.ValidateHardwareStationToken(deviceNumber, _
    hardwareStationToken)
```

``` csharp
public ValidateHardwareStationTokenResult ValidateHardwareStationToken(
    string deviceNumber,
    string hardwareStationToken
)
```

``` c++
public:
ValidateHardwareStationTokenResult^ ValidateHardwareStationToken(
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

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidateHardwareStationTokenResult](validatehardwarestationtokenresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[SecurityManager Class](securitymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

