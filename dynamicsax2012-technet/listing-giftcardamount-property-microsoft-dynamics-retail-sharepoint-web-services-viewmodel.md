---
title: Listing.GiftCardAmount Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: GiftCardAmount Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Listing.GiftCardAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.listing.giftcardamount(v=AX.60)
ms:contentKeyID: 62202329
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Listing.GiftCardAmount
dev_langs:
- CSharp
- C++
- VB
---

# GiftCardAmount Property

Gift card value.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property GiftCardAmount As Decimal
    Get
    Set
'Usage
Dim instance As Listing
Dim value As Decimal

value = instance.GiftCardAmount

instance.GiftCardAmount = value
```

``` csharp
[DataMemberAttribute]
public decimal GiftCardAmount { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal GiftCardAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

