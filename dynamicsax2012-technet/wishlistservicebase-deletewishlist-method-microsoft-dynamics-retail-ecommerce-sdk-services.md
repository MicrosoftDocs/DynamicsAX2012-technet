---
title: WishListServiceBase.DeleteWishList Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: DeleteWishList Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.WishListServiceBase.DeleteWishList(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.services.wishlistservicebase.deletewishlist(v=AX.60)
ms:contentKeyID: 65318023
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.WishListServiceBase.DeleteWishList
dev_langs:
- CSharp
- C++
- VB
---

# DeleteWishList Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function DeleteWishList ( _
    wishListId As String _
) As NullResponse
'Usage
Dim instance As WishListServiceBase
Dim wishListId As String
Dim returnValue As NullResponse

returnValue = instance.DeleteWishList(wishListId)
```

``` csharp
public virtual NullResponse DeleteWishList(
    string wishListId
)
```

``` c++
public:
virtual NullResponse^ DeleteWishList(
    String^ wishListId
)
```

#### Parameters

  - wishListId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.NullResponse](nullresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[IWishListService.DeleteWishList(String)](iwishlistservice-deletewishlist-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[WishListServiceBase Class](wishlistservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

