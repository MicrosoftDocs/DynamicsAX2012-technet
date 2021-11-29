---
title: LoyaltyCardsResponse.LoyaltyCards Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: LoyaltyCards Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardsResponse.LoyaltyCards
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.loyaltycardsresponse.loyaltycards(v=AX.60)
ms:contentKeyID: 62203854
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardsResponse.LoyaltyCards
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyCards Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the collection of loyalty cards.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LoyaltyCards As ReadOnlyCollection(Of LoyaltyCard)
    Get
    Friend Set
'Usage
Dim instance As LoyaltyCardsResponse
Dim value As ReadOnlyCollection(Of LoyaltyCard)

value = instance.LoyaltyCards
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<LoyaltyCard> LoyaltyCards { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<LoyaltyCard^>^ LoyaltyCards {
    ReadOnlyCollection<LoyaltyCard^>^ get ();
    internal: void set (ReadOnlyCollection<LoyaltyCard^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[LoyaltyCard](loyaltycard-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyCardsResponse Class](loyaltycardsresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

