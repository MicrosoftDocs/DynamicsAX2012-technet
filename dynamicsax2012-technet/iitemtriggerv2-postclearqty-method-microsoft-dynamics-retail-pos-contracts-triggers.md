---
title: IItemTriggerV2.PostClearQty Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PostClearQty Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IItemTriggerV2.PostClearQty(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.iitemtriggerv2.postclearqty(v=AX.60)
ms:contentKeyID: 49839142
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IItemTriggerV2.PostClearQty
dev_langs:
- CSharp
- C++
- VB
---

# PostClearQty Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggered after clear the quantity of an item.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostClearQty ( _
    posTransaction As IPosTransaction, _
    saleLineItem As ISaleLineItem _
)
'Usage
Dim instance As IItemTriggerV2
Dim posTransaction As IPosTransaction
Dim saleLineItem As ISaleLineItem

instance.PostClearQty(posTransaction, _
    saleLineItem)
```

``` csharp
void PostClearQty(
    IPosTransaction posTransaction,
    ISaleLineItem saleLineItem
)
```

``` c++
void PostClearQty(
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

[IItemTriggerV2 Interface](iitemtriggerv2-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

