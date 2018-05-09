---
title: WishListController.PopulateWishListDetailsFromProducts Method (WishList, IEnumerable(Product), ISearchEngine) (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: PopulateWishListDetailsFromProducts Method (WishList, IEnumerable(Product), ISearchEngine)
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.WishListController.PopulateWishListDetailsFromProducts(Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.WishList,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.Product},Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.wishlistcontroller.populatewishlistdetailsfromproducts(v=AX.60)
ms:contentKeyID: 65316831
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PopulateWishListDetailsFromProducts Method (WishList, IEnumerable(Product), ISearchEngine)

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Sub PopulateWishListDetailsFromProducts ( _
    wishList As WishList, _
    products As IEnumerable(Of Product), _
    searchEngine As ISearchEngine _
)
'Usage
Dim wishList As WishList
Dim products As IEnumerable(Of Product)
Dim searchEngine As ISearchEngine

Me.PopulateWishListDetailsFromProducts(wishList, _
    products, searchEngine)
```

``` csharp
protected virtual void PopulateWishListDetailsFromProducts(
    WishList wishList,
    IEnumerable<Product> products,
    ISearchEngine searchEngine
)
```

``` c++
protected:
virtual void PopulateWishListDetailsFromProducts(
    WishList^ wishList, 
    IEnumerable<Product^>^ products, 
    ISearchEngine^ searchEngine
)
```

#### Parameters

  - wishList  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.WishList](wishlist-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

<!-- end list -->

  - products  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<Product\>  

<!-- end list -->

  - searchEngine  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine](isearchengine-interface-microsoft-dynamics-retail-ecommerce-sdk-core.md)  

## See Also

#### Reference

[WishListController Class](wishlistcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[PopulateWishListDetailsFromProducts Overload](wishlistcontroller-populatewishlistdetailsfromproducts-method-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

