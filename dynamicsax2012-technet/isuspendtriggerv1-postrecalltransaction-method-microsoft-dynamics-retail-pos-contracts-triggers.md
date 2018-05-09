---
title: ISuspendTriggerV1.PostRecallTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PostRecallTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ISuspendTriggerV1.PostRecallTransaction(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.triggers.isuspendtriggerv1.postrecalltransaction(v=AX.60)
ms:contentKeyID: 47128118
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.ISuspendTriggerV1.PostRecallTransaction
dev_langs:
- CSharp
- C++
- VB
---

# PostRecallTransaction Method

Called after a transaction is recalled.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostRecallTransaction ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As ISuspendTriggerV1
Dim posTransaction As IPosTransaction

instance.PostRecallTransaction(posTransaction)
```

``` csharp
void PostRecallTransaction(
    IPosTransaction posTransaction
)
```

``` c++
void PostRecallTransaction(
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ISuspendTriggerV1 Interface](isuspendtriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

