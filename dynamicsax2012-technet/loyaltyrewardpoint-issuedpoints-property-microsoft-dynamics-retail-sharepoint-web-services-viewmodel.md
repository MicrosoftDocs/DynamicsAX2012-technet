---
title: LoyaltyRewardPoint.IssuedPoints Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: IssuedPoints Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyRewardPoint.IssuedPoints
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.loyaltyrewardpoint.issuedpoints(v=AX.60)
ms:contentKeyID: 62202014
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyRewardPoint.IssuedPoints
dev_langs:
- CSharp
- C++
- VB
---

# IssuedPoints Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the issued points.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IssuedPoints As Decimal
    Get
    Set
'Usage
Dim instance As LoyaltyRewardPoint
Dim value As Decimal

value = instance.IssuedPoints

instance.IssuedPoints = value
```

``` csharp
[DataMemberAttribute]
public decimal IssuedPoints { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal IssuedPoints {
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

