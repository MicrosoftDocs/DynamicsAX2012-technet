---
title: WishList.WishListLines Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: WishListLines Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.WishList.WishListLines
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.wishlist.wishlistlines(v=AX.60)
ms:contentKeyID: 62207379
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.WishList.WishListLines
dev_langs:
- CSharp
- C++
- VB
---

# WishListLines Property

Gets or sets the wish list lines.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property WishListLines As Collection(Of WishListLine)
    Get
    Set
'Usage
Dim instance As WishList
Dim value As Collection(Of WishListLine)

value = instance.WishListLines

instance.WishListLines = value
```

``` csharp
[DataMemberAttribute]
public Collection<WishListLine> WishListLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<WishListLine^>^ WishListLines {
    Collection<WishListLine^>^ get ();
    void set (Collection<WishListLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[WishListLine](wishlistline-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[WishList Class](wishlist-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

