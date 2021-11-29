---
title: LoyaltyCard.LoyaltyGroups Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: LoyaltyGroups Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCard.LoyaltyGroups
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.loyaltycard.loyaltygroups(v=AX.60)
ms:contentKeyID: 62203856
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCard.LoyaltyGroups
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyGroups Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the loyalty groups that the loyalty card belongs to.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LoyaltyGroups As IList(Of LoyaltyGroup)
    Get
    Set
'Usage
Dim instance As LoyaltyCard
Dim value As IList(Of LoyaltyGroup)

value = instance.LoyaltyGroups

instance.LoyaltyGroups = value
```

``` csharp
[DataMemberAttribute]
public IList<LoyaltyGroup> LoyaltyGroups { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<LoyaltyGroup^>^ LoyaltyGroups {
    IList<LoyaltyGroup^>^ get ();
    void set (IList<LoyaltyGroup^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[LoyaltyGroup](loyaltygroup-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyCard Class](loyaltycard-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

