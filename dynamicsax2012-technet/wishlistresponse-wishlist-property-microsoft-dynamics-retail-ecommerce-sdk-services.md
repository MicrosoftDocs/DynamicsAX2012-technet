---
title: WishListResponse.WishList Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: WishList Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.WishListResponse.WishList
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.wishlistresponse.wishlist(v=AX.60)
ms:contentKeyID: 65318767
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.WishListResponse.WishList
dev_langs:
- CSharp
- C++
- VB
---

# WishList Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property WishList As WishList
    Get
    Set
'Usage
Dim instance As WishListResponse
Dim value As WishList

value = instance.WishList

instance.WishList = value
```

``` csharp
[DataMemberAttribute]
public WishList WishList { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property WishList^ WishList {
    WishList^ get ();
    void set (WishList^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.WishList](wishlist-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)  

## See Also

#### Reference

[WishListResponse Class](wishlistresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

