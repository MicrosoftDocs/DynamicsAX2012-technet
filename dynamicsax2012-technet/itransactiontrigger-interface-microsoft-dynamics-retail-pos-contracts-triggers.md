---
title: ITransactionTrigger Interface (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: ITransactionTrigger Interface
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITransactionTrigger
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.triggers.itransactiontrigger(v=AX.60)
ms:contentKeyID: 47128070
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITransactionTrigger
dev_langs:
- CSharp
- C++
- VB
---

# ITransactionTrigger Interface

The ITransactionTrigger interface. These interfaces are implemented in the satellite assemblies in the \\Triggers subdirectory of the POS installation.

They can be overridden by third-party developers.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<GuidAttribute("4A5F1BC2-FC0F-49E7-B4A5-41F1BCB3B106")> _
Public Interface ITransactionTrigger _
    Inherits ITrigger, ITransactionTriggerV1, ITransactionTriggerV2
'Usage
Dim instance As ITransactionTrigger
```

``` csharp
[GuidAttribute("4A5F1BC2-FC0F-49E7-B4A5-41F1BCB3B106")]
public interface ITransactionTrigger : ITrigger, 
    ITransactionTriggerV1, ITransactionTriggerV2
```

``` c++
[GuidAttribute(L"4A5F1BC2-FC0F-49E7-B4A5-41F1BCB3B106")]
public interface class ITransactionTrigger : ITrigger, 
    ITransactionTriggerV1, ITransactionTriggerV2
```

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

