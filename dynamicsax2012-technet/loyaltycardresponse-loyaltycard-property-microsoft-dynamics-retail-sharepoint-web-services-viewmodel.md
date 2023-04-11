---
title: LoyaltyCardResponse.LoyaltyCard Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: LoyaltyCard Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardResponse.LoyaltyCard
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.loyaltycardresponse.loyaltycard(v=AX.60)
ms:contentKeyID: 62204887
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardResponse.LoyaltyCard
dev_langs:
- CSharp
- C++
- VB
---

# LoyaltyCard Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the loyalty card for the customer.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LoyaltyCard As LoyaltyCard
    Get
    Set
'Usage
Dim instance As LoyaltyCardResponse
Dim value As LoyaltyCard

value = instance.LoyaltyCard

instance.LoyaltyCard = value
```

``` csharp
[DataMemberAttribute]
public LoyaltyCard LoyaltyCard { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property LoyaltyCard^ LoyaltyCard {
    LoyaltyCard^ get ();
    void set (LoyaltyCard^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCard](loyaltycard-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [LoyaltyCard](loyaltycard-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## See Also

#### Reference

[LoyaltyCardResponse Class](loyaltycardresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

