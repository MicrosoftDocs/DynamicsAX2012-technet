---
title: Listing.RelatedProducts Property  (Microsoft.Dynamics.Retail.Channels)
TOCTitle: RelatedProducts Property
ms:assetid: P:Microsoft.Dynamics.Retail.Channels.Listing.RelatedProducts
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.channels.listing.relatedproducts(v=AX.60)
ms:contentKeyID: 65316324
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Channels.Listing.RelatedProducts
dev_langs:
- CSharp
- C++
- VB
---

# RelatedProducts Property

**Namespace:**  [Microsoft.Dynamics.Retail.Channels](microsoft-dynamics-retail-channels-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RelatedProducts As ICollection(Of RelatedProduct)
    Get
    Friend Set
'Usage
Dim instance As Listing
Dim value As ICollection(Of RelatedProduct)

value = instance.RelatedProducts
```

``` csharp
[DataMemberAttribute]
public ICollection<RelatedProduct> RelatedProducts { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<RelatedProduct^>^ RelatedProducts {
    ICollection<RelatedProduct^>^ get ();
    internal: void set (ICollection<RelatedProduct^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<RelatedProduct\>  

## See Also

#### Reference

[Listing Class](listing-class-microsoft-dynamics-retail-channels.md)

[Microsoft.Dynamics.Retail.Channels Namespace](microsoft-dynamics-retail-channels-namespace.md)

