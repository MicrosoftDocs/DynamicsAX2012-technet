---
title: ILoyaltyRewardPointLineV1.RewardPointType Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: RewardPointType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyRewardPointLineV1.RewardPointType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iloyaltyrewardpointlinev1.rewardpointtype(v=AX.60)
ms:contentKeyID: 62203920
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyRewardPointLineV1.RewardPointType
dev_langs:
- CSharp
- C++
- VB
---

# RewardPointType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the reward point type.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property RewardPointType As LoyaltyRewardPointType
    Get
    Set
'Usage
Dim instance As ILoyaltyRewardPointLineV1
Dim value As LoyaltyRewardPointType

value = instance.RewardPointType

instance.RewardPointType = value
```

``` csharp
LoyaltyRewardPointType RewardPointType { get; set; }
```

``` c++
property LoyaltyRewardPointType RewardPointType {
    LoyaltyRewardPointType get ();
    void set (LoyaltyRewardPointType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.LoyaltyRewardPointType](loyaltyrewardpointtype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
Returns [LoyaltyRewardPointType](loyaltyrewardpointtype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md).  

## See Also

#### Reference

[ILoyaltyRewardPointLineV1 Interface](iloyaltyrewardpointlinev1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

