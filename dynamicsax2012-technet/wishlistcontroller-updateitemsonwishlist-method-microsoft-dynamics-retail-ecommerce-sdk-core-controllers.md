---
title: WishListController.UpdateItemsOnWishList Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: UpdateItemsOnWishList Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.WishListController.UpdateItemsOnWishList(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.Listing})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.wishlistcontroller.updateitemsonwishlist(v=AX.60)
ms:contentKeyID: 65316684
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.WishListController.UpdateItemsOnWishList
dev_langs:
- CSharp
- C++
- VB
---

# UpdateItemsOnWishList Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function UpdateItemsOnWishList ( _
    wishListId As String, _
    customerId As String, _
    listings As IEnumerable(Of Listing) _
) As WishList
'Usage
Dim instance As WishListController
Dim wishListId As String
Dim customerId As String
Dim listings As IEnumerable(Of Listing)
Dim returnValue As WishList

returnValue = instance.UpdateItemsOnWishList(wishListId, _
    customerId, listings)
```

``` csharp
public virtual WishList UpdateItemsOnWishList(
    string wishListId,
    string customerId,
    IEnumerable<Listing> listings
)
```

``` c++
public:
virtual WishList^ UpdateItemsOnWishList(
    String^ wishListId, 
    String^ customerId, 
    IEnumerable<Listing^>^ listings
)
```

#### Parameters

  - wishListId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - listings  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Listing](listing-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.WishList](wishlist-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[WishListController Class](wishlistcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

