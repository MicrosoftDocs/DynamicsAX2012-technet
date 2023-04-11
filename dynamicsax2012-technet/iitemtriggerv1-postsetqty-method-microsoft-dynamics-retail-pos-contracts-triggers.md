---
title: IItemTriggerV1.PostSetQty Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PostSetQty Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IItemTriggerV1.PostSetQty(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.iitemtriggerv1.postsetqty(v=AX.60)
ms:contentKeyID: 47128077
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IItemTriggerV1.PostSetQty
dev_langs:
- CSharp
- C++
- VB
---

# PostSetQty Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggered after the quantity of an item is set.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostSetQty ( _
    posTransaction As IPosTransaction, _
    saleLineItem As ISaleLineItem _
)
'Usage
Dim instance As IItemTriggerV1
Dim posTransaction As IPosTransaction
Dim saleLineItem As ISaleLineItem

instance.PostSetQty(posTransaction, saleLineItem)
```

``` csharp
void PostSetQty(
    IPosTransaction posTransaction,
    ISaleLineItem saleLineItem
)
```

``` c++
void PostSetQty(
    IPosTransaction^ posTransaction, 
    ISaleLineItem^ saleLineItem
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - saleLineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem](isalelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IItemTriggerV1 Interface](iitemtriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

