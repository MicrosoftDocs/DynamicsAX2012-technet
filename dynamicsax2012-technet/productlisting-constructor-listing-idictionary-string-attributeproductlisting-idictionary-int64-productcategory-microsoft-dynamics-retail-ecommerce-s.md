---
title: ProductListing Constructor (Listing, IDictionary(String, AttributeProductListing), IDictionary(Int64, ProductCategory)) (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement)
TOCTitle: ProductListing Constructor (Listing, IDictionary(String, AttributeProductListing), IDictionary(Int64, ProductCategory))
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductListing.#ctor(Microsoft.Dynamics.Retail.Channels.Listing,System.Collections.Generic.IDictionary{System.String,Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.AttributeProductListing},System.Collections.Generic.IDictionary{System.Int64,Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductCategory})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.catalogmanagement.productlisting.productlisting(v=AX.60)
ms:contentKeyID: 65318534
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ProductListing Constructor (Listing, IDictionary(String, AttributeProductListing), IDictionary(Int64, ProductCategory))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    listing As Listing, _
    attributeSpace As IDictionary(Of String, AttributeProductListing), _
    categorySpace As IDictionary(Of Long, ProductCategory) _
)
'Usage
Dim listing As Listing
Dim attributeSpace As IDictionary(Of String, AttributeProductListing)
Dim categorySpace As IDictionary(Of Long, ProductCategory)

Dim instance As New ProductListing(listing, _
    attributeSpace, categorySpace)
```

``` csharp
public ProductListing(
    Listing listing,
    IDictionary<string, AttributeProductListing> attributeSpace,
    IDictionary<long, ProductCategory> categorySpace
)
```

``` c++
public:
ProductListing(
    Listing^ listing, 
    IDictionary<String^, AttributeProductListing^>^ attributeSpace, 
    IDictionary<long long, ProductCategory^>^ categorySpace
)
```

#### Parameters

  - listing  
    Type: [Microsoft.Dynamics.Retail.Channels.Listing](listing-class-microsoft-dynamics-retail-channels.md)  

<!-- end list -->

  - attributeSpace  
    Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [AttributeProductListing](attributeproductlisting-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)\>  

<!-- end list -->

  - categorySpace  
    Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)), [ProductCategory](productcategory-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)\>  

## See Also

#### Reference

[ProductListing Class](productlisting-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)

[ProductListing Overload](productlisting-constructor-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)

