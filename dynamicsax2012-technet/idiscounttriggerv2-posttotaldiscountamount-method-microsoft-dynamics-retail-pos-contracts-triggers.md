---
title: IDiscountTriggerV2.PostTotalDiscountAmount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PostTotalDiscountAmount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IDiscountTriggerV2.PostTotalDiscountAmount(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.triggers.idiscounttriggerv2.posttotaldiscountamount(v=AX.60)
ms:contentKeyID: 49844914
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IDiscountTriggerV2.PostTotalDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# PostTotalDiscountAmount Method

Triggered after total discount amount.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostTotalDiscountAmount ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IDiscountTriggerV2
Dim posTransaction As IPosTransaction

instance.PostTotalDiscountAmount(posTransaction)
```

``` csharp
void PostTotalDiscountAmount(
    IPosTransaction posTransaction
)
```

``` c++
void PostTotalDiscountAmount(
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IDiscountTriggerV2 Interface](idiscounttriggerv2-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

