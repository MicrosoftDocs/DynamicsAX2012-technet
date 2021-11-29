---
title: ILoyaltyRewardPointLineV1.RewardPointAmountQuantity Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: RewardPointAmountQuantity Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyRewardPointLineV1.RewardPointAmountQuantity
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iloyaltyrewardpointlinev1.rewardpointamountquantity(v=AX.60)
ms:contentKeyID: 62203710
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyRewardPointLineV1.RewardPointAmountQuantity
dev_langs:
- CSharp
- C++
- VB
---

# RewardPointAmountQuantity Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the amount or the quantity of the reward point.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property RewardPointAmountQuantity As Decimal
    Get
    Set
'Usage
Dim instance As ILoyaltyRewardPointLineV1
Dim value As Decimal

value = instance.RewardPointAmountQuantity

instance.RewardPointAmountQuantity = value
```

``` csharp
decimal RewardPointAmountQuantity { get; set; }
```

``` c++
property Decimal RewardPointAmountQuantity {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ILoyaltyRewardPointLineV1 Interface](iloyaltyrewardpointlinev1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

