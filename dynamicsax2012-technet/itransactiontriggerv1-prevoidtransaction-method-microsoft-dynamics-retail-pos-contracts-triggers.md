---
title: ITransactionTriggerV1.PreVoidTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PreVoidTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITransactionTriggerV1.PreVoidTransaction(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.itransactiontriggerv1.prevoidtransaction(v=AX.60)
ms:contentKeyID: 47128386
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITransactionTriggerV1.PreVoidTransaction
dev_langs:
- CSharp
- C++
- VB
---

# PreVoidTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Called before a transaction is voided.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PreVoidTransaction ( _
    preTriggerResult As IPreTriggerResult, _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As ITransactionTriggerV1
Dim preTriggerResult As IPreTriggerResult
Dim posTransaction As IPosTransaction

instance.PreVoidTransaction(preTriggerResult, _
    posTransaction)
```

``` csharp
void PreVoidTransaction(
    IPreTriggerResult preTriggerResult,
    IPosTransaction posTransaction
)
```

``` c++
void PreVoidTransaction(
    IPreTriggerResult^ preTriggerResult, 
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - preTriggerResult  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult](ipretriggerresult-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ITransactionTriggerV1 Interface](itransactiontriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

