---
title: LoyaltyRewardPoint.ExpiredPoints Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ExpiredPoints Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyRewardPoint.ExpiredPoints
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.loyaltyrewardpoint.expiredpoints(v=AX.60)
ms:contentKeyID: 62206681
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyRewardPoint.ExpiredPoints
dev_langs:
- CSharp
- C++
- VB
---

# ExpiredPoints Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the expired points.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ExpiredPoints As Decimal
    Get
    Set
'Usage
Dim instance As LoyaltyRewardPoint
Dim value As Decimal

value = instance.ExpiredPoints

instance.ExpiredPoints = value
```

``` csharp
[DataMemberAttribute]
public decimal ExpiredPoints { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal ExpiredPoints {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyRewardPoint Class](loyaltyrewardpoint-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

