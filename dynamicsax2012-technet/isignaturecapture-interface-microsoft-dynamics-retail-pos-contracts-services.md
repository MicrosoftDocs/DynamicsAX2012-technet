---
title: ISignatureCapture Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ISignatureCapture Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISignatureCapture
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.isignaturecapture(v=AX.60)
ms:contentKeyID: 49825240
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISignatureCapture
dev_langs:
- CSharp
- C++
- VB
---

# ISignatureCapture Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Interface for signature capture device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("2E5F75B6-DBFB-4437-A797-FF52AA1FE070")> _
Public Interface ISignatureCapture _
    Inherits ISignatureCaptureV1, IPeripheral, IPeripheralV1, IPeripheralV2
'Usage
Dim instance As ISignatureCapture
```

``` csharp
[GuidAttribute("2E5F75B6-DBFB-4437-A797-FF52AA1FE070")]
public interface ISignatureCapture : ISignatureCaptureV1, 
    IPeripheral, IPeripheralV1, IPeripheralV2
```

``` c++
[GuidAttribute(L"2E5F75B6-DBFB-4437-A797-FF52AA1FE070")]
public interface class ISignatureCapture : ISignatureCaptureV1, 
    IPeripheral, IPeripheralV1, IPeripheralV2
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

