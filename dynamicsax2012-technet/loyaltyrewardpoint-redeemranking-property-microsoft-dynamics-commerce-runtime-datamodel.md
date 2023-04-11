---
title: LoyaltyRewardPoint.RedeemRanking Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RedeemRanking Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPoint.RedeemRanking
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltyrewardpoint.redeemranking(v=AX.60)
ms:contentKeyID: 62215174
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyRewardPoint.RedeemRanking
dev_langs:
- CSharp
- C++
- VB
---

# RedeemRanking Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the redeem ranking.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("REDEEMRANKING")> _
<IgnoreDataMemberAttribute> _
Public Property RedeemRanking As Integer
    Get
    Friend Set
'Usage
Dim instance As LoyaltyRewardPoint
Dim value As Integer

value = instance.RedeemRanking
```

``` csharp
[ColumnAttribute("REDEEMRANKING")]
[IgnoreDataMemberAttribute]
public int RedeemRanking { get; internal set; }
```

``` c++
[ColumnAttribute(L"REDEEMRANKING")]
[IgnoreDataMemberAttribute]
public:
property int RedeemRanking {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyRewardPoint Class](loyaltyrewardpoint-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

