---
title: LoyaltyRewardPointLine.RewardPointRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RewardPointRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.RewardPointRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyrewardpointline.rewardpointrecordid(v=AX.60)
ms:contentKeyID: 62209297
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPointLine.RewardPointRecordId
dev_langs:
- CSharp
- C++
- VB
---

# RewardPointRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the record identifier of the loyalty reward point.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("REWARDPOINT")> _
Public Property RewardPointRecordId As Long
    Get
    Set
'Usage
Dim instance As LoyaltyRewardPointLine
Dim value As Long

value = instance.RewardPointRecordId

instance.RewardPointRecordId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("REWARDPOINT")]
public long RewardPointRecordId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"REWARDPOINT")]
public:
property long long RewardPointRecordId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyRewardPointLine Class](loyaltyrewardpointline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

