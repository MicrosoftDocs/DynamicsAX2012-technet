---
title: LoyaltyGroup.LoyaltyTiers Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: LoyaltyTiers Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyGroup.LoyaltyTiers
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.loyaltygroup.loyaltytiers(v=AX.60)
ms:contentKeyID: 62206437
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyGroup.LoyaltyTiers
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyTiers Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the loyalty tiers.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LoyaltyTiers As IList(Of LoyaltyTier)
    Get
    Set
'Usage
Dim instance As LoyaltyGroup
Dim value As IList(Of LoyaltyTier)

value = instance.LoyaltyTiers

instance.LoyaltyTiers = value
```

``` csharp
[DataMemberAttribute]
public IList<LoyaltyTier> LoyaltyTiers { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<LoyaltyTier^>^ LoyaltyTiers {
    IList<LoyaltyTier^>^ get ();
    void set (IList<LoyaltyTier^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[LoyaltyTier](loyaltytier-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyGroup Class](loyaltygroup-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

