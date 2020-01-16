---
title: Listing.GetListings Method  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: GetListings Method
ms:assetid: M:Microsoft.Dynamics.Retail.Channels.Listing.GetListings(Microsoft.Dynamics.Commerce.Runtime.DataModel.Product)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.channels.listing.getlistings(v=AX.60)
ms:contentKeyID: 65318780
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.GetListings
dev_langs:
- CSharp
- C++
- VB
---

# GetListings Method

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetListings ( _
    product As Product _
) As ReadOnlyCollection(Of Listing)
'Usage
Dim product As Product
Dim returnValue As ReadOnlyCollection(Of Listing)

returnValue = Listing.GetListings(product)
```

``` csharp
public static ReadOnlyCollection<Listing> GetListings(
    Product product
)
```

``` c++
public:
static ReadOnlyCollection<Listing^>^ GetListings(
    Product^ product
)
```

#### Parameters

  - product  
    Type: Product  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Listing](listing-class-microsoft-dynamics-retail-channels.md)\>  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-channels.md)

[Microsoft.Dynamics.Retail.Channels Namespace](microsoft-dynamics-retail-channels-namespace.md)

