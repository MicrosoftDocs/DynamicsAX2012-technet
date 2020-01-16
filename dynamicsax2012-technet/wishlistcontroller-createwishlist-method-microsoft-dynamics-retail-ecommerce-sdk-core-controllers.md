---
title: WishListController.CreateWishList Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: CreateWishList Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.WishListController.CreateWishList(Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.WishList,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.wishlistcontroller.createwishlist(v=AX.60)
ms:contentKeyID: 65316331
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.WishListController.CreateWishList
dev_langs:
- CSharp
- C++
- VB
---

# CreateWishList Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function CreateWishList ( _
    wishList As WishList, _
    customerId As String _
) As WishList
'Usage
Dim instance As WishListController
Dim wishList As WishList
Dim customerId As String
Dim returnValue As WishList

returnValue = instance.CreateWishList(wishList, _
    customerId)
```

``` csharp
public virtual WishList CreateWishList(
    WishList wishList,
    string customerId
)
```

``` c++
public:
virtual WishList^ CreateWishList(
    WishList^ wishList, 
    String^ customerId
)
```

#### Parameters

  - wishList  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.WishList](wishlist-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.WishList](wishlist-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[WishListController Class](wishlistcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

