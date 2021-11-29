---
title: IItemTriggerV1.PreSale Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PreSale Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IItemTriggerV1.PreSale(Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.iitemtriggerv1.presale(v=AX.60)
ms:contentKeyID: 47129159
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IItemTriggerV1.PreSale
dev_langs:
- CSharp
- C++
- VB
---

# PreSale Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggered before the item is added to the transaction.

Note: Data in saleLineItem, such as price and tax, is not yet set when this method is invoked.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PreSale ( _
    preTriggerResult As IPreTriggerResult, _
    saleLineItem As ISaleLineItem, _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IItemTriggerV1
Dim preTriggerResult As IPreTriggerResult
Dim saleLineItem As ISaleLineItem
Dim posTransaction As IPosTransaction

instance.PreSale(preTriggerResult, saleLineItem, _
    posTransaction)
```

``` csharp
void PreSale(
    IPreTriggerResult preTriggerResult,
    ISaleLineItem saleLineItem,
    IPosTransaction posTransaction
)
```

``` c++
void PreSale(
    IPreTriggerResult^ preTriggerResult, 
    ISaleLineItem^ saleLineItem, 
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - preTriggerResult  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IPreTriggerResult](ipretriggerresult-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)  

<!-- end list -->

  - saleLineItem  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem](isalelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IItemTriggerV1 Interface](iitemtriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

