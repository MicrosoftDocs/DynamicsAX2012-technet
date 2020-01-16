---
title: WishListResponse.WishList Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: WishList Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.WishListResponse.WishList
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.wishlistresponse.wishlist(v=AX.60)
ms:contentKeyID: 62203299
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.WishListResponse.WishList
dev_langs:
- CSharp
- C++
- VB
---

# WishList Property

Gets or sets the wish list.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property WishList As WishList
    Get
    Set
'Usage
Dim instance As WishListResponse
Dim value As WishList

value = instance.WishList

instance.WishList = value
```

``` csharp
[DataMemberAttribute]
public WishList WishList { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property WishList^ WishList {
    WishList^ get ();
    void set (WishList^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.WishList](wishlist-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [WishList](wishlist-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## See Also

#### Reference

[WishListResponse Class](wishlistresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

