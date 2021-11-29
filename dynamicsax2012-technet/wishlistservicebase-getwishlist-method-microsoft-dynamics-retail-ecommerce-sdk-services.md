---
title: WishListServiceBase.GetWishList Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: GetWishList Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.WishListServiceBase.GetWishList(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.wishlistservicebase.getwishlist(v=AX.60)
ms:contentKeyID: 65315958
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.WishListServiceBase.GetWishList
dev_langs:
- CSharp
- C++
- VB
---

# GetWishList Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetWishList ( _
    wishListId As String _
) As WishListResponse
'Usage
Dim instance As WishListServiceBase
Dim wishListId As String
Dim returnValue As WishListResponse

returnValue = instance.GetWishList(wishListId)
```

``` csharp
public virtual WishListResponse GetWishList(
    string wishListId
)
```

``` c++
public:
virtual WishListResponse^ GetWishList(
    String^ wishListId
)
```

#### Parameters

  - wishListId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.WishListResponse](wishlistresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

#### Implements

[IWishListService.GetWishList(String)](iwishlistservice-getwishlist-method-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[WishListServiceBase Class](wishlistservicebase-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

