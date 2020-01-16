---
title: IDiscountTriggerV2.PostTotalDiscountPercent Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PostTotalDiscountPercent Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IDiscountTriggerV2.PostTotalDiscountPercent(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.idiscounttriggerv2.posttotaldiscountpercent(v=AX.60)
ms:contentKeyID: 49839950
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IDiscountTriggerV2.PostTotalDiscountPercent
dev_langs:
- CSharp
- C++
- VB
---

# PostTotalDiscountPercent Method

Triggered after total discount percent.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostTotalDiscountPercent ( _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IDiscountTriggerV2
Dim posTransaction As IPosTransaction

instance.PostTotalDiscountPercent(posTransaction)
```

``` csharp
void PostTotalDiscountPercent(
    IPosTransaction posTransaction
)
```

``` c++
void PostTotalDiscountPercent(
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

