---
title: LoyaltyRewardPoint.RewardPointCurrency Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: RewardPointCurrency Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyRewardPoint.RewardPointCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.loyaltyrewardpoint.rewardpointcurrency(v=AX.60)
ms:contentKeyID: 62206262
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyRewardPoint.RewardPointCurrency
dev_langs:
- CSharp
- C++
- VB
---

# RewardPointCurrency Property

Gets the currency of the reward point if the reward point is amount type.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RewardPointCurrency As String
    Get
    Set
'Usage
Dim instance As LoyaltyRewardPoint
Dim value As String

value = instance.RewardPointCurrency

instance.RewardPointCurrency = value
```

``` csharp
[DataMemberAttribute]
public string RewardPointCurrency { get; set; }
```

``` c++
[DataMemberAttribute]
public:
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

[LoyaltyRewardPoint Class](loyaltyrewardpoint-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

