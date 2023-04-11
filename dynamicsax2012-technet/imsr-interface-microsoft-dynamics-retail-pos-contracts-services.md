---
title: IMSR Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IMSR Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IMSR
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.imsr(v=AX.60)
ms:contentKeyID: 47343900
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IMSR
dev_langs:
- CSharp
- C++
- VB
---

# IMSR Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.IMSR interface for magnetic stripe reader device.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("1983683C-F2B8-4A6E-BCB8-3521429C63FC")> _
Public Interface IMSR _
    Inherits IMSRV1, IPeripheral, IPeripheralV1, IPeripheralV2
'Usage
Dim instance As IMSR
```

``` csharp
[GuidAttribute("1983683C-F2B8-4A6E-BCB8-3521429C63FC")]
public interface IMSR : IMSRV1, IPeripheral, 
    IPeripheralV1, IPeripheralV2
```

``` c++
[GuidAttribute(L"1983683C-F2B8-4A6E-BCB8-3521429C63FC")]
public interface class IMSR : IMSRV1, 
    IPeripheral, IPeripheralV1, IPeripheralV2
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

