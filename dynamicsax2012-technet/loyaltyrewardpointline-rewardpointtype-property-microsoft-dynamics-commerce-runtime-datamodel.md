---
title: LoyaltyRewardPointLine.RewardPointType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RewardPointType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.RewardPointType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyrewardpointline.rewardpointtype(v=AX.60)
ms:contentKeyID: 62209114
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.RewardPointType
dev_langs:
- CSharp
- C++
- VB
---

# RewardPointType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the reward point unit type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("REWARDPOINTTYPE")> _
<DataMemberAttribute> _
Public Property RewardPointType As LoyaltyRewardPointType
    Get
    Set
'Usage
Dim instance As LoyaltyRewardPointLine
Dim value As LoyaltyRewardPointType

value = instance.RewardPointType

instance.RewardPointType = value
```

``` csharp
[ColumnAttribute("REWARDPOINTTYPE")]
[DataMemberAttribute]
public LoyaltyRewardPointType RewardPointType { get; set; }
```

``` c++
[ColumnAttribute(L"REWARDPOINTTYPE")]
[DataMemberAttribute]
public:
property LoyaltyRewardPointType RewardPointType {
    LoyaltyRewardPointType get ();
    void set (LoyaltyRewardPointType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointType](loyaltyrewardpointtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [LoyaltyRewardPointType](loyaltyrewardpointtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[LoyaltyRewardPointLine Class](loyaltyrewardpointline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

