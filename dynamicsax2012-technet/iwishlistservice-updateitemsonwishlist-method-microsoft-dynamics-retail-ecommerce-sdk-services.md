---
title: IWishListService.UpdateItemsOnWishList Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: UpdateItemsOnWishList Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IWishListService.UpdateItemsOnWishList(System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Listing})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.iwishlistservice.updateitemsonwishlist(v=AX.60)
ms:contentKeyID: 65318362
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IWishListService.UpdateItemsOnWishList
dev_langs:
- CSharp
- C++
- VB
---

# UpdateItemsOnWishList Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function UpdateItemsOnWishList ( _
    wishListId As String, _
    listings As IEnumerable(Of Listing) _
) As WishListResponse
'Usage
Dim instance As IWishListService
Dim wishListId As String
Dim listings As IEnumerable(Of Listing)
Dim returnValue As WishListResponse

returnValue = instance.UpdateItemsOnWishList(wishListId, _
    listings)
```

``` csharp
[OperationContractAttribute]
WishListResponse UpdateItemsOnWishList(
    string wishListId,
    IEnumerable<Listing> listings
)
```

``` c++
[OperationContractAttribute]
WishListResponse^ UpdateItemsOnWishList(
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

## See Also

#### Reference

[IWishListService Interface](iwishlistservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

