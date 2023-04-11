---
title: WishListController.GetWishList Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetWishList Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.WishListController.GetWishList(System.String,System.String,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.wishlistcontroller.getwishlist(v=AX.60)
ms:contentKeyID: 65315799
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.WishListController.GetWishList
dev_langs:
- CSharp
- C++
- VB
---

# GetWishList Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetWishList ( _
    wishListId As String, _
    customerId As String, _
    searchEngine As ISearchEngine _
) As WishList
'Usage
Dim instance As WishListController
Dim wishListId As String
Dim customerId As String
Dim searchEngine As ISearchEngine
Dim returnValue As WishList

returnValue = instance.GetWishList(wishListId, _
    customerId, searchEngine)
```

``` csharp
public virtual WishList GetWishList(
    string wishListId,
    string customerId,
    ISearchEngine searchEngine
)
```

``` c++
public:
virtual WishList^ GetWishList(
    String^ wishListId, 
    String^ customerId, 
    ISearchEngine^ searchEngine
)
```

#### Parameters

  - wishListId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - searchEngine  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine](isearchengine-interface-microsoft-dynamics-retail-ecommerce-sdk-core.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.WishList](wishlist-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[WishListController Class](wishlistcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

