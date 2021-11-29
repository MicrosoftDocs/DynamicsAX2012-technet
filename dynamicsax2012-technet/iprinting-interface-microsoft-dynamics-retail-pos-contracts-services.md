---
title: IPrinting Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IPrinting Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrinting
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iprinting(v=AX.60)
ms:contentKeyID: 47344218
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrinting
dev_langs:
- CSharp
- C++
- VB
---

# IPrinting Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPrinting interface for printing services

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("EBA4887B-32D2-452B-9BFF-7BFD98A50F7D")> _
Public Interface IPrinting _
    Inherits IService, IPrintingV1, IPrintingV2, IPrintingV3
'Usage
Dim instance As IPrinting
```

``` csharp
[GuidAttribute("EBA4887B-32D2-452B-9BFF-7BFD98A50F7D")]
public interface IPrinting : IService, 
    IPrintingV1, IPrintingV2, IPrintingV3
```

``` c++
[GuidAttribute(L"EBA4887B-32D2-452B-9BFF-7BFD98A50F7D")]
public interface class IPrinting : IService, 
    IPrintingV1, IPrintingV2, IPrintingV3
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

