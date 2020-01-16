---
title: LoyaltyCard.RewardPoints Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: RewardPoints Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.LoyaltyCard.RewardPoints
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.loyaltycard.rewardpoints(v=AX.60)
ms:contentKeyID: 65316693
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.LoyaltyCard.RewardPoints
dev_langs:
- CSharp
- C++
- VB
---

# RewardPoints Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RewardPoints As IList(Of LoyaltyRewardPoint)
    Get
    Set
'Usage
Dim instance As LoyaltyCard
Dim value As IList(Of LoyaltyRewardPoint)

value = instance.RewardPoints

instance.RewardPoints = value
```

``` csharp
[DataMemberAttribute]
public IList<LoyaltyRewardPoint> RewardPoints { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<LoyaltyRewardPoint^>^ RewardPoints {
    IList<LoyaltyRewardPoint^>^ get ();
    void set (IList<LoyaltyRewardPoint^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[LoyaltyRewardPoint](loyaltyrewardpoint-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[LoyaltyCard Class](loyaltycard-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

