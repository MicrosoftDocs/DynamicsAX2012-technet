---
title: ITenderRestriction Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ITenderRestriction Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ITenderRestriction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.itenderrestriction(v=AX.60)
ms:contentKeyID: 47344447
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ITenderRestriction
dev_langs:
- CSharp
- C++
- VB
---

# ITenderRestriction Interface


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.ITenderRestriction interface indicates whether any item in the transaction is restricted from being paid for with the currently added payment method.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("07AAA0CF-77FF-4E53-ABA5-EF78F360802D")> _
Public Interface ITenderRestriction _
    Inherits IService, ITenderRestrictionV1
'Usage
Dim instance As ITenderRestriction
```

``` csharp
[GuidAttribute("07AAA0CF-77FF-4E53-ABA5-EF78F360802D")]
public interface ITenderRestriction : IService, 
    ITenderRestrictionV1
```

``` c++
[GuidAttribute(L"07AAA0CF-77FF-4E53-ABA5-EF78F360802D")]
public interface class ITenderRestriction : IService, 
    ITenderRestrictionV1
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

