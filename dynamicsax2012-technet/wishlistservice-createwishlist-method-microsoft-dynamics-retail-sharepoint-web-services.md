---
title: WishListService.CreateWishList Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: CreateWishList Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.WishListService.CreateWishList(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.wishlistservice.createwishlist(v=AX.60)
ms:contentKeyID: 62206506
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.WishListService.CreateWishList
dev_langs:
- CSharp
- C++
- VB
---

# CreateWishList Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates the wish list.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function CreateWishList ( _
    wishListName As String _
) As WishListResponse
'Usage
Dim instance As WishListService
Dim wishListName As String
Dim returnValue As WishListResponse

returnValue = instance.CreateWishList(wishListName)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public WishListResponse CreateWishList(
    string wishListName
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual WishListResponse^ CreateWishList(
    String^ wishListName
) sealed
```

#### Parameters

  - wishListName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.WishListResponse](wishlistresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
The service response containing the wish list.  

#### Implements

[IWishListService.CreateWishList(String)](iwishlistservice-createwishlist-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[WishListService Class](wishlistservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

