---
title: LoyaltyRewardPointLine.RewardPointIsRedeemable Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RewardPointIsRedeemable Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.RewardPointIsRedeemable
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyrewardpointline.rewardpointisredeemable(v=AX.60)
ms:contentKeyID: 62203535
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.RewardPointIsRedeemable
dev_langs:
- CSharp
- C++
- VB
---

# RewardPointIsRedeemable Property

Gets or sets a value indicating whether the reward point is redeemable.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("REWARDPOINTREDEEMABLE")> _
Public Property RewardPointIsRedeemable As Boolean
    Get
    Set
'Usage
Dim instance As LoyaltyRewardPointLine
Dim value As Boolean

value = instance.RewardPointIsRedeemable

instance.RewardPointIsRedeemable = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("REWARDPOINTREDEEMABLE")]
public bool RewardPointIsRedeemable { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"REWARDPOINTREDEEMABLE")]
public:
property bool RewardPointIsRedeemable {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyRewardPointLine Class](loyaltyrewardpointline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

