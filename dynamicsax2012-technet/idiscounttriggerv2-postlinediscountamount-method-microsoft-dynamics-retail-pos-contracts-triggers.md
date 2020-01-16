---
title: IDiscountTriggerV2.PostLineDiscountAmount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: PostLineDiscountAmount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IDiscountTriggerV2.PostLineDiscountAmount(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.idiscounttriggerv2.postlinediscountamount(v=AX.60)
ms:contentKeyID: 49851770
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IDiscountTriggerV2.PostLineDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# PostLineDiscountAmount Method

Triggered after adding line discount amount.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Triggers](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub PostLineDiscountAmount ( _
    posTransaction As IPosTransaction, _
    lineId As Integer _
)
'Usage
Dim instance As IDiscountTriggerV2
Dim posTransaction As IPosTransaction
Dim lineId As Integer

instance.PostLineDiscountAmount(posTransaction, _
    lineId)
```

``` csharp
void PostLineDiscountAmount(
    IPosTransaction posTransaction,
    int lineId
)
```

``` c++
void PostLineDiscountAmount(
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

