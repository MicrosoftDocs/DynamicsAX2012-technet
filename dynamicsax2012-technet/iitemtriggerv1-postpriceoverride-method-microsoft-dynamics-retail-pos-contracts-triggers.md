---
title: IItemTriggerV1.PostPriceOverride Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PostPriceOverride Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IItemTriggerV1.PostPriceOverride(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.triggers.iitemtriggerv1.postpriceoverride(v=AX.60)
ms:contentKeyID: 47129009
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IItemTriggerV1.PostPriceOverride
dev_langs:
- CSharp
- C++
- VB
---

# PostPriceOverride Method

Triggered after the price of an item is overridden.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostPriceOverride ( _
    posTransaction As IPosTransaction, _
    saleLineItem As ISaleLineItem _
)
'Usage
Dim instance As IItemTriggerV1
Dim posTransaction As IPosTransaction
Dim saleLineItem As ISaleLineItem

instance.PostPriceOverride(posTransaction, _
    saleLineItem)
```

``` csharp
void PostPriceOverride(
    IPosTransaction posTransaction,
    ISaleLineItem saleLineItem
)
```

``` c++
void PostPriceOverride(
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

