---
title: WishList.WishListLines Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: WishListLines Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.WishList.WishListLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.wishlist.wishlistlines(v=AX.60)
ms:contentKeyID: 65316357
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.WishList.WishListLines
dev_langs:
- CSharp
- C++
- VB
---

# WishListLines Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property WishListLines As Collection(Of WishListLine)
    Get
    Set
'Usage
Dim instance As WishList
Dim value As Collection(Of WishListLine)

value = instance.WishListLines

instance.WishListLines = value
```

``` csharp
[DataMemberAttribute]
public Collection<WishListLine> WishListLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<WishListLine^>^ WishListLines {
    Collection<WishListLine^>^ get ();
    void set (Collection<WishListLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[WishListLine](wishlistline-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[WishList Class](wishlist-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

