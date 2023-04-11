---
title: WishListController.PopulateWishListLineDetailsFromSearchResults Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: PopulateWishListLineDetailsFromSearchResults Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.WishListController.PopulateWishListLineDetailsFromSearchResults(Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.WishListLine,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.wishlistcontroller.populatewishlistlinedetailsfromsearchresults(v=AX.60)
ms:contentKeyID: 65317279
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.WishListController.PopulateWishListLineDetailsFromSearchResults
dev_langs:
- CSharp
- C++
- VB
---

# PopulateWishListLineDetailsFromSearchResults Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Sub PopulateWishListLineDetailsFromSearchResults ( _
    wishListLine As WishListLine, _
    searchEngine As ISearchEngine _
)
'Usage
Dim wishListLine As WishListLine
Dim searchEngine As ISearchEngine

Me.PopulateWishListLineDetailsFromSearchResults(wishListLine, _
    searchEngine)
```

``` csharp
protected virtual void PopulateWishListLineDetailsFromSearchResults(
    WishListLine wishListLine,
    ISearchEngine searchEngine
)
```

``` c++
protected:
virtual void PopulateWishListLineDetailsFromSearchResults(
    WishListLine^ wishListLine, 
    ISearchEngine^ searchEngine
)
```

#### Parameters

  - wishListLine  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.WishListLine](wishlistline-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

<!-- end list -->

  - searchEngine  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine](isearchengine-interface-microsoft-dynamics-retail-ecommerce-sdk-core.md)  

## See Also

#### Reference

[WishListController Class](wishlistcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

