---
title: LoyaltyTier.TierLevel Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: TierLevel Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyTier.TierLevel
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.loyaltytier.tierlevel(v=AX.60)
ms:contentKeyID: 62205811
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyTier.TierLevel
dev_langs:
- CSharp
- C++
- VB
---

# TierLevel Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the tier level. Bigger number means higher level.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TierLevel As Decimal
    Get
    Set
'Usage
Dim instance As LoyaltyTier
Dim value As Decimal

value = instance.TierLevel

instance.TierLevel = value
```

``` csharp
[DataMemberAttribute]
public decimal TierLevel { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal TierLevel {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyTier Class](loyaltytier-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

