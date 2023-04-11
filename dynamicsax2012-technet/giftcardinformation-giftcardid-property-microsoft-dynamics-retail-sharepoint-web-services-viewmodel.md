---
title: GiftCardInformation.GiftCardId Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: GiftCardId Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.GiftCardInformation.GiftCardId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.giftcardinformation.giftcardid(v=AX.60)
ms:contentKeyID: 62204900
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.GiftCardInformation.GiftCardId
dev_langs:
- CSharp
- C++
- VB
---

# GiftCardId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the gift card ID.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property GiftCardId As String
    Get
    Set
'Usage
Dim instance As GiftCardInformation
Dim value As String

value = instance.GiftCardId

instance.GiftCardId = value
```

``` csharp
[DataMemberAttribute]
public string GiftCardId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ GiftCardId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GiftCardInformation Class](giftcardinformation-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

