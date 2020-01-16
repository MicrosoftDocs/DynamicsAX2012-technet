---
title: GiftCardResponse.GiftCardInformation Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: GiftCardInformation Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.GiftCardResponse.GiftCardInformation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.giftcardresponse.giftcardinformation(v=AX.60)
ms:contentKeyID: 62202027
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.GiftCardResponse.GiftCardInformation
dev_langs:
- CSharp
- C++
- VB
---

# GiftCardInformation Property

Gets or sets the customer.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property GiftCardInformation As GiftCardInformation
    Get
    Set
'Usage
Dim instance As GiftCardResponse
Dim value As GiftCardInformation

value = instance.GiftCardInformation

instance.GiftCardInformation = value
```

``` csharp
[DataMemberAttribute]
public GiftCardInformation GiftCardInformation { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property GiftCardInformation^ GiftCardInformation {
    GiftCardInformation^ get ();
    void set (GiftCardInformation^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.GiftCardInformation](giftcardinformation-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [GiftCardInformation](giftcardinformation-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## See Also

#### Reference

[GiftCardResponse Class](giftcardresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

