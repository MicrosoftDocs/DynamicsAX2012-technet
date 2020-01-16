---
title: ILoyaltyRewardPointLineV1.RewardPointCurrency Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: RewardPointCurrency Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyRewardPointLineV1.RewardPointCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iloyaltyrewardpointlinev1.rewardpointcurrency(v=AX.60)
ms:contentKeyID: 62202749
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyRewardPointLineV1.RewardPointCurrency
dev_langs:
- CSharp
- C++
- VB
---

# RewardPointCurrency Property

Gets or sets the currency of the reward point if the reward point is amount type.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property RewardPointCurrency As String
    Get
    Set
'Usage
Dim instance As ILoyaltyRewardPointLineV1
Dim value As String

value = instance.RewardPointCurrency

instance.RewardPointCurrency = value
```

``` csharp
string RewardPointCurrency { get; set; }
```

``` c++
property String^ RewardPointCurrency {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ILoyaltyRewardPointLineV1 Interface](iloyaltyrewardpointlinev1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

