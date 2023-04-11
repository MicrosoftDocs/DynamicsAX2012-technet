---
title: LoyaltyCardTier.ValidToFriendly Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ValidToFriendly Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardTier.ValidToFriendly
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.loyaltycardtier.validtofriendly(v=AX.60)
ms:contentKeyID: 62203594
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardTier.ValidToFriendly
dev_langs:
- CSharp
- C++
- VB
---

# ValidToFriendly Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the start date of the valid period in a numeric string.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ValidToFriendly As String
    Get
    Set
'Usage
Dim instance As LoyaltyCardTier
Dim value As String

value = instance.ValidToFriendly

instance.ValidToFriendly = value
```

``` csharp
[DataMemberAttribute]
public string ValidToFriendly { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ValidToFriendly {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyCardTier Class](loyaltycardtier-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

