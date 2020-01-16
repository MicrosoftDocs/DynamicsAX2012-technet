---
title: LoyaltyRewardPoint.ExpirationTimeUnit Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ExpirationTimeUnit Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyRewardPoint.ExpirationTimeUnit
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.loyaltyrewardpoint.expirationtimeunit(v=AX.60)
ms:contentKeyID: 62206827
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyRewardPoint.ExpirationTimeUnit
dev_langs:
- CSharp
- C++
- VB
---

# ExpirationTimeUnit Property

Gets expiration time unit of the reward point.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property ExpirationTimeUnit As DayMonthYear
    Get
    Set
'Usage
Dim instance As LoyaltyRewardPoint
Dim value As DayMonthYear

value = instance.ExpirationTimeUnit

instance.ExpirationTimeUnit = value
```

``` csharp
[IgnoreDataMemberAttribute]
public DayMonthYear ExpirationTimeUnit { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property DayMonthYear ExpirationTimeUnit {
    DayMonthYear get ();
    void set (DayMonthYear value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.DayMonthYear](daymonthyear-enumeration-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [DayMonthYear](daymonthyear-enumeration-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## See Also

#### Reference

[LoyaltyRewardPoint Class](loyaltyrewardpoint-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

