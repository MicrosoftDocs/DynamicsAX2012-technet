---
title: WishListServiceBase.RemoveItemFromWishList Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: RemoveItemFromWishList Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.WishListServiceBase.RemoveItemFromWishList(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.services.wishlistservicebase.removeitemfromwishlist(v=AX.60)
ms:contentKeyID: 65315867
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.WishListServiceBase.RemoveItemFromWishList
dev_langs:
- CSharp
- C++
- VB
---

# RemoveItemFromWishList Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function RemoveItemFromWishList ( _
    wishListId As String, _
    listingId As String _
) As NullResponse
'Usage
Dim instance As WishListServiceBase
Dim wishListId As String
Dim listingId As String
Dim returnValue As NullResponse

returnValue = instance.RemoveItemFromWishList(wishListId, _
    listingId)
```

``` csharp
public virtual NullResponse RemoveItemFromWishList(
    string wishListId,
    string listingId
)
```

``` c++
public:
virtual NullResponse^ RemoveItemFromWishList(
    String^ wishListId, 
    String^ listingId
)
```

#### Parameters

  - wishListId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - listingId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.NullResponse](nullresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[IWishListService.RemoveItemFromWishList(String, String)](iwishlistservice-removeitemfromwishlist-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[WishListServiceBase Class](wishlistservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

