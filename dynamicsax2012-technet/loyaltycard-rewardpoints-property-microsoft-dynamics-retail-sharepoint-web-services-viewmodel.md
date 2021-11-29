---
title: LoyaltyCard.RewardPoints Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: RewardPoints Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCard.RewardPoints
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.loyaltycard.rewardpoints(v=AX.60)
ms:contentKeyID: 62206979
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCard.RewardPoints
dev_langs:
- CSharp
- C++
- VB
---

# RewardPoints Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the reward points on the loyalty card.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

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

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[LoyaltyRewardPoint](loyaltyrewardpoint-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyCard Class](loyaltycard-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

