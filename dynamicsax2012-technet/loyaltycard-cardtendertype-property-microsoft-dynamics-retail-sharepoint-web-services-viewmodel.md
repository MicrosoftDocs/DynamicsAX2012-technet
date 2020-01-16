---
title: LoyaltyCard.CardTenderType Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: CardTenderType Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCard.CardTenderType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.loyaltycard.cardtendertype(v=AX.60)
ms:contentKeyID: 62204893
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCard.CardTenderType
dev_langs:
- CSharp
- C++
- VB
---

# CardTenderType Property

Gets or sets the card tender type.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CardTenderType As LoyaltyCardTenderType
    Get
    Set
'Usage
Dim instance As LoyaltyCard
Dim value As LoyaltyCardTenderType

value = instance.CardTenderType

instance.CardTenderType = value
```

``` csharp
[DataMemberAttribute]
public LoyaltyCardTenderType CardTenderType { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property LoyaltyCardTenderType CardTenderType {
    LoyaltyCardTenderType get ();
    void set (LoyaltyCardTenderType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardTenderType](loyaltycardtendertype-enumeration-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [LoyaltyCardTenderType](loyaltycardtendertype-enumeration-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## See Also

#### Reference

[LoyaltyCard Class](loyaltycard-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

