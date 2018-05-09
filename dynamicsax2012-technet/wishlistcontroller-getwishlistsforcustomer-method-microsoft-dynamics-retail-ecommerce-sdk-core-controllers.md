---
title: WishListController.GetWishListsForCustomer Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetWishListsForCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.WishListController.GetWishListsForCustomer(System.String,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.wishlistcontroller.getwishlistsforcustomer(v=AX.60)
ms:contentKeyID: 65318609
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.WishListController.GetWishListsForCustomer
dev_langs:
- CSharp
- C++
- VB
---

# GetWishListsForCustomer Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetWishListsForCustomer ( _
    customerId As String, _
    searchEngine As ISearchEngine _
) As Collection(Of WishList)
'Usage
Dim instance As WishListController
Dim customerId As String
Dim searchEngine As ISearchEngine
Dim returnValue As Collection(Of WishList)

returnValue = instance.GetWishListsForCustomer(customerId, _
    searchEngine)
```

``` csharp
public virtual Collection<WishList> GetWishListsForCustomer(
    string customerId,
    ISearchEngine searchEngine
)
```

``` c++
public:
virtual Collection<WishList^>^ GetWishListsForCustomer(
    String^ customerId, 
    ISearchEngine^ searchEngine
)
```

#### Parameters

  - customerId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - searchEngine  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.ISearchEngine](isearchengine-interface-microsoft-dynamics-retail-ecommerce-sdk-core.md)  

#### Return Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/en-us/library/ms132397\(v=ax.60\))\<[WishList](wishlist-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[WishListController Class](wishlistcontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

