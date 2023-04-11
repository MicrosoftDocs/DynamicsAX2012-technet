---
title: Listing.ProductsRelatedToThis Property  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: ProductsRelatedToThis Property
ms:assetid: P:Microsoft.Dynamics.Retail.Channels.Listing.ProductsRelatedToThis
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.channels.listing.productsrelatedtothis(v=AX.60)
ms:contentKeyID: 65317531
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.ProductsRelatedToThis
dev_langs:
- CSharp
- C++
- VB
---

# ProductsRelatedToThis Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ProductsRelatedToThis As ICollection(Of RelatedProduct)
    Get
    Friend Set
'Usage
Dim instance As Listing
Dim value As ICollection(Of RelatedProduct)

value = instance.ProductsRelatedToThis
```

``` csharp
[DataMemberAttribute]
public ICollection<RelatedProduct> ProductsRelatedToThis { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<RelatedProduct^>^ ProductsRelatedToThis {
    ICollection<RelatedProduct^>^ get ();
    internal: void set (ICollection<RelatedProduct^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<RelatedProduct\>  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-channels.md)

[Microsoft.Dynamics.Retail.Channels Namespace](microsoft-dynamics-retail-channels-namespace.md)

