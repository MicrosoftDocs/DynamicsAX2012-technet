---
title: IBiometricDevice Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IBiometricDevice Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IBiometricDevice
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.ibiometricdevice(v=AX.60)
ms:contentKeyID: 49827303
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IBiometricDevice
dev_langs:
- CSharp
- C++
- VB
---

# IBiometricDevice Interface

Interface for biometric device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("32653B5F-2950-47EA-A5AC-84E6C7DE7039")> _
Public Interface IBiometricDevice _
    Inherits IBiometricDeviceV1, IPeripheral, IPeripheralV1, IPeripheralV2,  _
    IBiometricDeviceV2
'Usage
Dim instance As IBiometricDevice
```

``` csharp
[GuidAttribute("32653B5F-2950-47EA-A5AC-84E6C7DE7039")]
public interface IBiometricDevice : IBiometricDeviceV1, 
    IPeripheral, IPeripheralV1, IPeripheralV2, IBiometricDeviceV2
```

``` c++
[GuidAttribute(L"32653B5F-2950-47EA-A5AC-84E6C7DE7039")]
public interface class IBiometricDevice : IBiometricDeviceV1, 
    IPeripheral, IPeripheralV1, IPeripheralV2, IBiometricDeviceV2
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

