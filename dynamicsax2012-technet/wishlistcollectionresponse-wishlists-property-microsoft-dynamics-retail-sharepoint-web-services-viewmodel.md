---
title: WishListCollectionResponse.WishLists Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: WishLists Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.WishListCollectionResponse.WishLists
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.wishlistcollectionresponse.wishlists(v=AX.60)
ms:contentKeyID: 62206498
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.WishListCollectionResponse.WishLists
dev_langs:
- CSharp
- C++
- VB
---

# WishLists Property

Gets the wish lists.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property WishLists As Collection(Of WishList)
    Get
    Friend Set
'Usage
Dim instance As WishListCollectionResponse
Dim value As Collection(Of WishList)

value = instance.WishLists
```

``` csharp
[DataMemberAttribute]
public Collection<WishList> WishLists { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<WishList^>^ WishLists {
    Collection<WishList^>^ get ();
    internal: void set (Collection<WishList^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[WishList](wishlist-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
The wish lists.  

## See Also

#### Reference

[WishListCollectionResponse Class](wishlistcollectionresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

