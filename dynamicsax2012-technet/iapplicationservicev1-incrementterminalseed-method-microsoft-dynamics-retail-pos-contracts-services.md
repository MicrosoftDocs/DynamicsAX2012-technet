---
title: IApplicationServiceV1.IncrementTerminalSeed Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IncrementTerminalSeed Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IApplicationServiceV1.IncrementTerminalSeed(Microsoft.Dynamics.Retail.Pos.Contracts.Services.NumberSequenceSeedType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iapplicationservicev1.incrementterminalseed(v=AX.60)
ms:contentKeyID: 47344203
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IApplicationServiceV1.IncrementTerminalSeed
dev_langs:
- CSharp
- C++
- VB
---

# IncrementTerminalSeed Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Increments the terminal seed value for the type given.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub IncrementTerminalSeed ( _
    type As NumberSequenceSeedType _
)
'Usage
Dim instance As IApplicationServiceV1
Dim type As NumberSequenceSeedType

instance.IncrementTerminalSeed(type)
```

``` csharp
void IncrementTerminalSeed(
    NumberSequenceSeedType type
)
```

``` c++
void IncrementTerminalSeed(
    NumberSequenceSeedType type
)
```

#### Parameters

  - type  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.NumberSequenceSeedType](numbersequenceseedtype-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  

## See Also

#### Reference

[IApplicationServiceV1 Interface](iapplicationservicev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

