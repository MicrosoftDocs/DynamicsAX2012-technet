---
title: IItemTriggerV1.PostSale Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PostSale Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IItemTriggerV1.PostSale(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.iitemtriggerv1.postsale(v=AX.60)
ms:contentKeyID: 47128028
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IItemTriggerV1.PostSale
dev_langs:
- CSharp
- C++
- VB
---

# PostSale Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggered after the item is added to the transaction.

Prices and discounts have been calculated, but the event is triggered before processing infocodes or linked items.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostSale ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IItemTriggerV1
Dim posTransaction As IPosTransaction

instance.PostSale(posTransaction)
```

``` csharp
void PostSale(
    IPosTransaction posTransaction
)
```

``` c++
void PostSale(
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IItemTriggerV1 Interface](iitemtriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

