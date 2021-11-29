---
title: IMSRV1 Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IMSRV1 Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IMSRV1
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.imsrv1(v=AX.60)
ms:contentKeyID: 47344385
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IMSRV1
dev_langs:
- CSharp
- C++
- VB
---

# IMSRV1 Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.IMSRV1 interface is the version 1.0 interface for magnetic stripe reader device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("4741DC54-A265-49E8-A54A-AAC697B2A600")> _
Public Interface IMSRV1 _
    Inherits IPeripheral, IPeripheralV1, IPeripheralV2
'Usage
Dim instance As IMSRV1
```

``` csharp
[GuidAttribute("4741DC54-A265-49E8-A54A-AAC697B2A600")]
public interface IMSRV1 : IPeripheral, IPeripheralV1, 
    IPeripheralV2
```

``` c++
[GuidAttribute(L"4741DC54-A265-49E8-A54A-AAC697B2A600")]
public interface class IMSRV1 : IPeripheral, 
    IPeripheralV1, IPeripheralV2
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

