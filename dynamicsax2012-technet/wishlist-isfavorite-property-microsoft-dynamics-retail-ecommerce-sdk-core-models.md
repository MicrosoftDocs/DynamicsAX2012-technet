---
title: WishList.IsFavorite Property  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models)
TOCTitle: IsFavorite Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.WishList.IsFavorite
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.models.wishlist.isfavorite(v=AX.60)
ms:contentKeyID: 65316298
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models.WishList.IsFavorite
dev_langs:
- CSharp
- C++
- VB
---

# IsFavorite Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsFavorite As Nullable(Of Boolean)
    Get
    Set
'Usage
Dim instance As WishList
Dim value As Nullable(Of Boolean)

value = instance.IsFavorite

instance.IsFavorite = value
```

``` csharp
[DataMemberAttribute]
public Nullable<bool> IsFavorite { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<bool> IsFavorite {
    Nullable<bool> get ();
    void set (Nullable<bool> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))\>  

## See Also

#### Reference

[WishList Class](wishlist-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Models Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-models-namespace.md)

