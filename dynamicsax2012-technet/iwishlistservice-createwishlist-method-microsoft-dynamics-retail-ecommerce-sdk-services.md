---
title: IWishListService.CreateWishList Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: CreateWishList Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IWishListService.CreateWishList(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.iwishlistservice.createwishlist(v=AX.60)
ms:contentKeyID: 65316880
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IWishListService.CreateWishList
dev_langs:
- CSharp
- C++
- VB
---

# CreateWishList Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function CreateWishList ( _
    wishListName As String _
) As WishListResponse
'Usage
Dim instance As IWishListService
Dim wishListName As String
Dim returnValue As WishListResponse

returnValue = instance.CreateWishList(wishListName)
```

``` csharp
[OperationContractAttribute]
WishListResponse CreateWishList(
    string wishListName
)
```

``` c++
[OperationContractAttribute]
WishListResponse^ CreateWishList(
    String^ wishListName
)
```

#### Parameters

  - wishListName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.WishListResponse](wishlistresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[IWishListService Interface](iwishlistservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

