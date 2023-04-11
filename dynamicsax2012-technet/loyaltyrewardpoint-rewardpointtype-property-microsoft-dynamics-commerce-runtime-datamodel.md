---
title: LoyaltyRewardPoint.RewardPointType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RewardPointType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPoint.RewardPointType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyrewardpoint.rewardpointtype(v=AX.60)
ms:contentKeyID: 62214828
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPoint.RewardPointType
dev_langs:
- CSharp
- C++
- VB
---

# RewardPointType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the reward point unit type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("REWARDPOINTTYPE")> _
<IgnoreDataMemberAttribute> _
Public Property RewardPointType As LoyaltyRewardPointType
    Get
    Friend Set
'Usage
Dim instance As LoyaltyRewardPoint
Dim value As LoyaltyRewardPointType

value = instance.RewardPointType
```

``` csharp
[ColumnAttribute("REWARDPOINTTYPE")]
[IgnoreDataMemberAttribute]
public LoyaltyRewardPointType RewardPointType { get; internal set; }
```

``` c++
[ColumnAttribute(L"REWARDPOINTTYPE")]
[IgnoreDataMemberAttribute]
public:
property LoyaltyRewardPointType RewardPointType {
    LoyaltyRewardPointType get ();
    internal: void set (LoyaltyRewardPointType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointType](loyaltyrewardpointtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [LoyaltyRewardPointType](loyaltyrewardpointtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[LoyaltyRewardPoint Class](loyaltyrewardpoint-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

