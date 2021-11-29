---
title: WishListService.AddItemsToWishList Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: AddItemsToWishList Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.WishListService.AddItemsToWishList(System.String,System.Collections.Generic.ICollection{Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Listing})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.wishlistservice.additemstowishlist(v=AX.60)
ms:contentKeyID: 62205688
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.WishListService.AddItemsToWishList
dev_langs:
- CSharp
- C++
- VB
---

# AddItemsToWishList Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Adds items to wish list.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function AddItemsToWishList ( _
    wishListId As String, _
    listings As ICollection(Of Listing) _
) As WishListResponse
'Usage
Dim instance As WishListService
Dim wishListId As String
Dim listings As ICollection(Of Listing)
Dim returnValue As WishListResponse

returnValue = instance.AddItemsToWishList(wishListId, _
    listings)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public WishListResponse AddItemsToWishList(
    string wishListId,
    ICollection<Listing> listings
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual WishListResponse^ AddItemsToWishList(
    String^ wishListId, 
    ICollection<Listing^>^ listings
) sealed
```

#### Parameters

  - wishListId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - listings  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[Listing](listing-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.WishListResponse](wishlistresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
The service response containing the wish list.  

#### Implements

[IWishListService.AddItemsToWishList(String, ICollection\<Listing\>)](iwishlistservice-additemstowishlist-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[WishListService Class](wishlistservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

