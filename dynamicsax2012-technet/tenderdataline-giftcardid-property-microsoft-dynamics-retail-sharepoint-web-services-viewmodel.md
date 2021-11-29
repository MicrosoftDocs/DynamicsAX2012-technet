---
title: TenderDataLine.GiftCardId Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: GiftCardId Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.TenderDataLine.GiftCardId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.tenderdataline.giftcardid(v=AX.60)
ms:contentKeyID: 62206563
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.TenderDataLine.GiftCardId
dev_langs:
- CSharp
- C++
- VB
---

# GiftCardId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the gift card identifier.

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
Dim instance As TenderDataLine
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

[TenderDataLine Class](tenderdataline-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

