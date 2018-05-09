---
title: WishListService.RemoveItemFromWishList Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: RemoveItemFromWishList Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.WishListService.RemoveItemFromWishList(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.wishlistservice.removeitemfromwishlist(v=AX.60)
ms:contentKeyID: 62207126
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.WishListService.RemoveItemFromWishList
dev_langs:
- CSharp
- C++
- VB
---

# RemoveItemFromWishList Method

Remove item from wish list.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function RemoveItemFromWishList ( _
    wishListId As String, _
    listingId As String _
) As NullResponse
'Usage
Dim instance As WishListService
Dim wishListId As String
Dim listingId As String
Dim returnValue As NullResponse

returnValue = instance.RemoveItemFromWishList(wishListId, _
    listingId)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public NullResponse RemoveItemFromWishList(
    string wishListId,
    string listingId
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual NullResponse^ RemoveItemFromWishList(
    String^ wishListId, 
    String^ listingId
) sealed
```

#### Parameters

  - wishListId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - listingId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.NullResponse](nullresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [NullResponse](nullresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

#### Implements

[IWishListService.RemoveItemFromWishList(String, String)](iwishlistservice-removeitemfromwishlist-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[WishListService Class](wishlistservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

