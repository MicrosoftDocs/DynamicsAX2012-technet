---
title: ITransactionTriggerV1.PostReturnTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PostReturnTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITransactionTriggerV1.PostReturnTransaction(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.itransactiontriggerv1.postreturntransaction(v=AX.60)
ms:contentKeyID: 47128586
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITransactionTriggerV1.PostReturnTransaction
dev_langs:
- CSharp
- C++
- VB
---

# PostReturnTransaction Method

Called after a return transaction is completed.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostReturnTransaction ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As ITransactionTriggerV1
Dim posTransaction As IPosTransaction

instance.PostReturnTransaction(posTransaction)
```

``` csharp
void PostReturnTransaction(
    IPosTransaction posTransaction
)
```

``` c++
void PostReturnTransaction(
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ITransactionTriggerV1 Interface](itransactiontriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

