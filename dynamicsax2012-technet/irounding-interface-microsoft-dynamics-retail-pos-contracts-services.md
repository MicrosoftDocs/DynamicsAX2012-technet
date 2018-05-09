---
title: IRounding Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IRounding Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRounding
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.irounding(v=AX.60)
ms:contentKeyID: 47344441
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRounding
dev_langs:
- CSharp
- C++
- VB
---

# IRounding Interface

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRounding interface contains various utility methods for rounding decimal values for display, printing, and rounding based on currency rules.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("EA4C06AE-0D49-47AA-B0EC-6D8973CF4C30")> _
Public Interface IRounding _
    Inherits IService, IRoundingV1, IRoundingV2, IRoundingV3
'Usage
Dim instance As IRounding
```

``` csharp
[GuidAttribute("EA4C06AE-0D49-47AA-B0EC-6D8973CF4C30")]
public interface IRounding : IService, 
    IRoundingV1, IRoundingV2, IRoundingV3
```

``` c++
[GuidAttribute(L"EA4C06AE-0D49-47AA-B0EC-6D8973CF4C30")]
public interface class IRounding : IService, 
    IRoundingV1, IRoundingV2, IRoundingV3
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

