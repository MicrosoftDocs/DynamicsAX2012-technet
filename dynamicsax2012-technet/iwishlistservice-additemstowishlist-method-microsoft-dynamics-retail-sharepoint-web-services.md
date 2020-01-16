---
title: IWishListService.AddItemsToWishList Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: AddItemsToWishList Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.IWishListService.AddItemsToWishList(System.String,System.Collections.Generic.ICollection{Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.Listing})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.iwishlistservice.additemstowishlist(v=AX.60)
ms:contentKeyID: 62206992
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.IWishListService.AddItemsToWishList
dev_langs:
- CSharp
- C++
- VB
---

# AddItemsToWishList Method

Adds items to wish list.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function AddItemsToWishList ( _
    wishListId As String, _
    listings As ICollection(Of Listing) _
) As WishListResponse
'Usage
Dim instance As IWishListService
Dim wishListId As String
Dim listings As ICollection(Of Listing)
Dim returnValue As WishListResponse

returnValue = instance.AddItemsToWishList(wishListId, _
    listings)
```

``` csharp
[OperationContractAttribute]
WishListResponse AddItemsToWishList(
    string wishListId,
    ICollection<Listing> listings
)
```

``` c++
[OperationContractAttribute]
WishListResponse^ AddItemsToWishList(
    String^ wishListId, 
    ICollection<Listing^>^ listings
)
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

## See Also

#### Reference

[IWishListService Interface](iwishlistservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

