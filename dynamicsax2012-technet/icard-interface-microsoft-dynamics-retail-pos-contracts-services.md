---
title: ICard Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ICard Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICard
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icard(v=AX.60)
ms:contentKeyID: 47344329
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICard
dev_langs:
- CSharp
- C++
- VB
---

# ICard Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICard interface is implemented by the card.cs class.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("AB2E8391-6B98-409B-A0B1-414CA00E789A")> _
Public Interface ICard _
    Inherits IService, ICardV1, ICardV2, ICardV3
'Usage
Dim instance As ICard
```

``` csharp
[GuidAttribute("AB2E8391-6B98-409B-A0B1-414CA00E789A")]
public interface ICard : IService, ICardV1, 
    ICardV2, ICardV3
```

``` c++
[GuidAttribute(L"AB2E8391-6B98-409B-A0B1-414CA00E789A")]
public interface class ICard : IService, 
    ICardV1, ICardV2, ICardV3
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

