---
title: Listing.ExpandProductsToListings Method  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: ExpandProductsToListings Method
ms:assetid: M:Microsoft.Dynamics.Retail.Channels.Listing.ExpandProductsToListings(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.Product})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.channels.listing.expandproductstolistings(v=AX.60)
ms:contentKeyID: 65317197
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.ExpandProductsToListings
dev_langs:
- CSharp
- C++
- VB
---

# ExpandProductsToListings Method

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Shared Function ExpandProductsToListings ( _
    products As IEnumerable(Of Product) _
) As ReadOnlyCollection(Of Listing)
'Usage
Dim products As IEnumerable(Of Product)
Dim returnValue As ReadOnlyCollection(Of Listing)

returnValue = Listing.ExpandProductsToListings(products)
```

``` csharp
public static ReadOnlyCollection<Listing> ExpandProductsToListings(
    IEnumerable<Product> products
)
```

``` c++
public:
static ReadOnlyCollection<Listing^>^ ExpandProductsToListings(
    IEnumerable<Product^>^ products
)
```

#### Parameters

  - products  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<Product\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Listing](listing-class-microsoft-dynamics-retail-channels.md)\>  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-channels.md)

[Microsoft.Dynamics.Retail.Channels Namespace](microsoft-dynamics-retail-channels-namespace.md)

