---
title: IBiometricDeviceV1.DataReceived Event (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: DataReceived Event
ms:assetid: E:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IBiometricDeviceV1.DataReceived
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ibiometricdevicev1.datareceived(v=AX.60)
ms:contentKeyID: 49837487
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IBiometricDeviceV1.DataReceived
dev_langs:
- CSharp
- C++
- VB
---

# DataReceived Event

Biometric device message event.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Event DataReceived As BiometricDeviceDataEventHandler
'Usage
Dim instance As IBiometricDeviceV1
Dim handler As BiometricDeviceDataEventHandler

AddHandler instance.DataReceived, handler
```

``` csharp
event BiometricDeviceDataEventHandler DataReceived
```

``` c++
 event BiometricDeviceDataEventHandler^ DataReceived {
    void add (BiometricDeviceDataEventHandler^ value);
    void remove (BiometricDeviceDataEventHandler^ value);
}
```

## See Also

#### Reference

[IBiometricDeviceV1 Interface](ibiometricdevicev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

