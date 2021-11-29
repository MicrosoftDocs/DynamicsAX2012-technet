---
title: IScale Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IScale Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IScale
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iscale(v=AX.60)
ms:contentKeyID: 47344170
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IScale
dev_langs:
- CSharp
- C++
- VB
---

# IScale Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.IScale interface for scale device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("FEAEEAD2-B900-4879-A7EC-D0CC1196917E")> _
Public Interface IScale _
    Inherits IScaleV1, IPeripheral, IPeripheralV1, IPeripheralV2
'Usage
Dim instance As IScale
```

``` csharp
[GuidAttribute("FEAEEAD2-B900-4879-A7EC-D0CC1196917E")]
public interface IScale : IScaleV1, IPeripheral, 
    IPeripheralV1, IPeripheralV2
```

``` c++
[GuidAttribute(L"FEAEEAD2-B900-4879-A7EC-D0CC1196917E")]
public interface class IScale : IScaleV1, 
    IPeripheral, IPeripheralV1, IPeripheralV2
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

