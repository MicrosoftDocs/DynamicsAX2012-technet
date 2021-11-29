---
title: WishListCollectionResponse.WishLists Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: WishLists Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.WishListCollectionResponse.WishLists
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.wishlistcollectionresponse.wishlists(v=AX.60)
ms:contentKeyID: 65316801
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.WishListCollectionResponse.WishLists
dev_langs:
- CSharp
- C++
- VB
---

# WishLists Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property WishLists As Collection(Of WishList)
    Get
    Friend Set
'Usage
Dim instance As WishListCollectionResponse
Dim value As Collection(Of WishList)

value = instance.WishLists
```

``` csharp
[DataMemberAttribute]
public Collection<WishList> WishLists { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<WishList^>^ WishLists {
    Collection<WishList^>^ get ();
    internal: void set (Collection<WishList^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[WishList](wishlist-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[WishListCollectionResponse Class](wishlistcollectionresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

