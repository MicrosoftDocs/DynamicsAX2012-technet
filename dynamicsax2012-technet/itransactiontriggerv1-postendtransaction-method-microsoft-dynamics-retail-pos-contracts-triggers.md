---
title: ITransactionTriggerV1.PostEndTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PostEndTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITransactionTriggerV1.PostEndTransaction(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.itransactiontriggerv1.postendtransaction(v=AX.60)
ms:contentKeyID: 47128788
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITransactionTriggerV1.PostEndTransaction
dev_langs:
- CSharp
- C++
- VB
---

# PostEndTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Called at the end of a transaction, after the transaction is saved and the receipts are printed.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostEndTransaction ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As ITransactionTriggerV1
Dim posTransaction As IPosTransaction

instance.PostEndTransaction(posTransaction)
```

``` csharp
void PostEndTransaction(
    IPosTransaction posTransaction
)
```

``` c++
void PostEndTransaction(
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

