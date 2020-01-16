---
title: ITransactionTriggerV1.BeginTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: BeginTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITransactionTriggerV1.BeginTransaction(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.itransactiontriggerv1.begintransaction(v=AX.60)
ms:contentKeyID: 47129301
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ITransactionTriggerV1.BeginTransaction
dev_langs:
- CSharp
- C++
- VB
---

# BeginTransaction Method

Called at the start of a new transaction, but after loading the transaction with initialization data, such as the store ID, the terminal number, and the date.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub BeginTransaction ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As ITransactionTriggerV1
Dim posTransaction As IPosTransaction

instance.BeginTransaction(posTransaction)
```

``` csharp
void BeginTransaction(
    IPosTransaction posTransaction
)
```

``` c++
void BeginTransaction(
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

