---
title: WishListServiceBase.AddItemsToWishList Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: AddItemsToWishList Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.WishListServiceBase.AddItemsToWishList(System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Listing})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.wishlistservicebase.additemstowishlist(v=AX.60)
ms:contentKeyID: 65315874
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.WishListServiceBase.AddItemsToWishList
dev_langs:
- CSharp
- C++
- VB
---

# AddItemsToWishList Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function AddItemsToWishList ( _
    wishListId As String, _
    listings As IEnumerable(Of Listing) _
) As WishListResponse
'Usage
Dim instance As WishListServiceBase
Dim wishListId As String
Dim listings As IEnumerable(Of Listing)
Dim returnValue As WishListResponse

returnValue = instance.AddItemsToWishList(wishListId, _
    listings)
```

``` csharp
public virtual WishListResponse AddItemsToWishList(
    string wishListId,
    IEnumerable<Listing> listings
)
```

``` c++
public:
virtual WishListResponse^ AddItemsToWishList(
    String^ wishListId, 
    IEnumerable<Listing^>^ listings
)
```

#### Parameters

  - wishListId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - listings  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Listing](listing-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.WishListResponse](wishlistresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[IWishListService.AddItemsToWishList(String, IEnumerable\<Listing\>)](iwishlistservice-additemstowishlist-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[WishListServiceBase Class](wishlistservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

