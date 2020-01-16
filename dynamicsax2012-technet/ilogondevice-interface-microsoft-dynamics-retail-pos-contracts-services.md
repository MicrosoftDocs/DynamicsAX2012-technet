---
title: ILogOnDevice Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ILogOnDevice Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILogOnDevice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ilogondevice(v=AX.60)
ms:contentKeyID: 49823116
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILogOnDevice
dev_langs:
- CSharp
- C++
- VB
---

# ILogOnDevice Interface

Interface for log on device adaptor.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("7B8262EC-DFCE-454E-B03D-F45809010891")> _
Public Interface ILogOnDevice _
    Inherits ILogOnDeviceV1, IPeripheral, IPeripheralV1, IPeripheralV2,  _
    ILogOnDeviceV2
'Usage
Dim instance As ILogOnDevice
```

``` csharp
[GuidAttribute("7B8262EC-DFCE-454E-B03D-F45809010891")]
public interface ILogOnDevice : ILogOnDeviceV1, 
    IPeripheral, IPeripheralV1, IPeripheralV2, ILogOnDeviceV2
```

``` c++
[GuidAttribute(L"7B8262EC-DFCE-454E-B03D-F45809010891")]
public interface class ILogOnDevice : ILogOnDeviceV1, 
    IPeripheral, IPeripheralV1, IPeripheralV2, ILogOnDeviceV2
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

