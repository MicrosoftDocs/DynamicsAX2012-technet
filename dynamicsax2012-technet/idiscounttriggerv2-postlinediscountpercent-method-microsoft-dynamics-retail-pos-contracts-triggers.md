---
title: IDiscountTriggerV2.PostLineDiscountPercent Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PostLineDiscountPercent Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IDiscountTriggerV2.PostLineDiscountPercent(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.idiscounttriggerv2.postlinediscountpercent(v=AX.60)
ms:contentKeyID: 49829713
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IDiscountTriggerV2.PostLineDiscountPercent
dev_langs:
- CSharp
- C++
- VB
---

# PostLineDiscountPercent Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Triggered after adding line discount percentange.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostLineDiscountPercent ( _
    posTransaction As IPosTransaction, _
    lineId As Integer _
)
'Usage
Dim instance As IDiscountTriggerV2
Dim posTransaction As IPosTransaction
Dim lineId As Integer

instance.PostLineDiscountPercent(posTransaction, _
    lineId)
```

``` csharp
void PostLineDiscountPercent(
    IPosTransaction posTransaction,
    int lineId
)
```

``` c++
void PostLineDiscountPercent(
    IPosTransaction^ posTransaction, 
    int lineId
)
```

#### Parameters

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - lineId  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[IDiscountTriggerV2 Interface](idiscounttriggerv2-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

