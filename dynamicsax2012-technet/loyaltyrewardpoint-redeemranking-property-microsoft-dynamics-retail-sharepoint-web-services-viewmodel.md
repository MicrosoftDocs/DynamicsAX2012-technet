---
title: LoyaltyRewardPoint.RedeemRanking Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: RedeemRanking Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyRewardPoint.RedeemRanking
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.loyaltyrewardpoint.redeemranking(v=AX.60)
ms:contentKeyID: 62202844
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyRewardPoint.RedeemRanking
dev_langs:
- CSharp
- C++
- VB
---

# RedeemRanking Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the redeem ranking.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property RedeemRanking As Integer
    Get
    Set
'Usage
Dim instance As LoyaltyRewardPoint
Dim value As Integer

value = instance.RedeemRanking

instance.RedeemRanking = value
```

``` csharp
[IgnoreDataMemberAttribute]
public int RedeemRanking { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property int RedeemRanking {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyRewardPoint Class](loyaltyrewardpoint-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

