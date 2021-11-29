---
title: IWishListService.UpdateWishListProperties Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: UpdateWishListProperties Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IWishListService.UpdateWishListProperties(System.String,System.String,System.Nullable{System.Boolean})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.iwishlistservice.updatewishlistproperties(v=AX.60)
ms:contentKeyID: 65318336
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IWishListService.UpdateWishListProperties
dev_langs:
- CSharp
- C++
- VB
---

# UpdateWishListProperties Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function UpdateWishListProperties ( _
    wishListId As String, _
    wishListName As String, _
    isFavorite As Nullable(Of Boolean) _
) As WishListResponse
'Usage
Dim instance As IWishListService
Dim wishListId As String
Dim wishListName As String
Dim isFavorite As Nullable(Of Boolean)
Dim returnValue As WishListResponse

returnValue = instance.UpdateWishListProperties(wishListId, _
    wishListName, isFavorite)
```

``` csharp
[OperationContractAttribute]
WishListResponse UpdateWishListProperties(
    string wishListId,
    string wishListName,
    Nullable<bool> isFavorite
)
```

``` c++
[OperationContractAttribute]
WishListResponse^ UpdateWishListProperties(
    String^ wishListId, 
    String^ wishListName, 
    Nullable<bool> isFavorite
)
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

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.WishListResponse](wishlistresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[IWishListService Interface](iwishlistservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

