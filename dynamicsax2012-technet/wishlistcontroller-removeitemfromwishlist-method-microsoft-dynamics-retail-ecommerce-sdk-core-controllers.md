---
title: WishListController.RemoveItemFromWishList Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: RemoveItemFromWishList Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.WishListController.RemoveItemFromWishList(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.wishlistcontroller.removeitemfromwishlist(v=AX.60)
ms:contentKeyID: 65316611
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.WishListController.RemoveItemFromWishList
dev_langs:
- CSharp
- C++
- VB
---

# RemoveItemFromWishList Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Sub RemoveItemFromWishList ( _
    wishListId As String, _
    customerId As String, _
    listingId As String _
)
'Usage
Dim instance As WishListController
Dim wishListId As String
Dim customerId As String
Dim listingId As String

instance.RemoveItemFromWishList(wishListId, _
    customerId, listingId)
```

``` csharp
public virtual void RemoveItemFromWishList(
    string wishListId,
    string customerId,
    string listingId
)
```

``` c++
public:
virtual void RemoveItemFromWishList(
    String^ wishListId, 
    String^ customerId, 
    String^ listingId
)
```

#### Parameters

  - wishListId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - listingId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[WishListController Class](wishlistcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

