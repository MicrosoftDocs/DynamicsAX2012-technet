---
title: WishListService.UpdateWishListProperties Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: UpdateWishListProperties Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.WishListService.UpdateWishListProperties(System.String,System.String,System.Nullable{System.Boolean})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.wishlistservice.updatewishlistproperties(v=AX.60)
ms:contentKeyID: 62204835
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.WishListService.UpdateWishListProperties
dev_langs:
- CSharp
- C++
- VB
---

# UpdateWishListProperties Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Updates the wish list properties.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<WebInvokeAttribute(ResponseFormat := WebMessageFormat.Json, RequestFormat := WebMessageFormat.Json,  _
    BodyStyle := WebMessageBodyStyle.WrappedRequest)> _
Public Function UpdateWishListProperties ( _
    wishListId As String, _
    wishListName As String, _
    isFavorite As Nullable(Of Boolean) _
) As WishListResponse
'Usage
Dim instance As WishListService
Dim wishListId As String
Dim wishListName As String
Dim isFavorite As Nullable(Of Boolean)
Dim returnValue As WishListResponse

returnValue = instance.UpdateWishListProperties(wishListId, _
    wishListName, isFavorite)
```

``` csharp
[WebInvokeAttribute(ResponseFormat = WebMessageFormat.Json, RequestFormat = WebMessageFormat.Json, 
    BodyStyle = WebMessageBodyStyle.WrappedRequest)]
public WishListResponse UpdateWishListProperties(
    string wishListId,
    string wishListName,
    Nullable<bool> isFavorite
)
```

``` c++
[WebInvokeAttribute(ResponseFormat = WebMessageFormat::Json, RequestFormat = WebMessageFormat::Json, 
    BodyStyle = WebMessageBodyStyle::WrappedRequest)]
public:
virtual WishListResponse^ UpdateWishListProperties(
    String^ wishListId, 
    String^ wishListName, 
    Nullable<bool> isFavorite
) sealed
```

#### Parameters

  - wishListId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - wishListName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - isFavorite  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.WishListResponse](wishlistresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
The service response containing the wish list.  

#### Implements

[IWishListService.UpdateWishListProperties(String, String, Nullable\<Boolean\>)](iwishlistservice-updatewishlistproperties-method-microsoft-dynamics-retail-sharepoint-web-services.md)  

## See Also

#### Reference

[WishListService Class](wishlistservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

