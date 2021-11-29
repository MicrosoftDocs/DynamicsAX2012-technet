---
title: IBiometricDeviceV1.StatusUpdate Event (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: StatusUpdate Event
ms:assetid: E:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IBiometricDeviceV1.StatusUpdate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ibiometricdevicev1.statusupdate(v=AX.60)
ms:contentKeyID: 49833413
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IBiometricDeviceV1.StatusUpdate
dev_langs:
- CSharp
- C++
- VB
---

# StatusUpdate Event


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Biometric device update event.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Event StatusUpdate As BiometricDeviceStatusEventHandler
'Usage
Dim instance As IBiometricDeviceV1
Dim handler As BiometricDeviceStatusEventHandler

AddHandler instance.StatusUpdate, handler
```

``` csharp
event BiometricDeviceStatusEventHandler StatusUpdate
```

``` c++
 event BiometricDeviceStatusEventHandler^ StatusUpdate {
    void add (BiometricDeviceStatusEventHandler^ value);
    void remove (BiometricDeviceStatusEventHandler^ value);
}
```

## See Also

#### Reference

[IBiometricDeviceV1 Interface](ibiometricdevicev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

