---
title: ITransactionTriggerV2.PreConfirmReturnTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PreConfirmReturnTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITransactionTriggerV2.PreConfirmReturnTransaction(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.itransactiontriggerv2.preconfirmreturntransaction(v=AX.60)
ms:contentKeyID: 62203322
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITransactionTriggerV2.PreConfirmReturnTransaction
dev_langs:
- CSharp
- C++
- VB
---

# PreConfirmReturnTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggered before confirmation of return transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PreConfirmReturnTransaction ( _
    preTriggerResult As IPreTriggerResult, _
    originalTransaction As IRetailTransaction _
)
'Usage
Dim instance As ITransactionTriggerV2
Dim preTriggerResult As IPreTriggerResult
Dim originalTransaction As IRetailTransaction

instance.PreConfirmReturnTransaction(preTriggerResult, _
    originalTransaction)
```

``` csharp
void PreConfirmReturnTransaction(
    IPreTriggerResult preTriggerResult,
    IRetailTransaction originalTransaction
)
```

``` c++
void PreConfirmReturnTransaction(
    IPreTriggerResult^ preTriggerResult, 
    IRetailTransaction^ originalTransaction
)
```

#### Parameters

  - preTriggerResult  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult](ipretriggerresult-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)  

<!-- end list -->

  - originalTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ITransactionTriggerV2 Interface](itransactiontriggerv2-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

