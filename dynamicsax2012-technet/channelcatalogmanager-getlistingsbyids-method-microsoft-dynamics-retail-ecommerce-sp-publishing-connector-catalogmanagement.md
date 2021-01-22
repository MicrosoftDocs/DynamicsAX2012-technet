---
title: ChannelCatalogManager.GetListingsByIds Method  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement)
TOCTitle: GetListingsByIds Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ChannelCatalogManager.GetListingsByIds(System.Int64,System.Collections.Generic.ICollection{Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductListing})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.catalogmanagement.channelcatalogmanager.getlistingsbyids(v=AX.60)
ms:contentKeyID: 65318424
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ChannelCatalogManager.GetListingsByIds
dev_langs:
- CSharp
- C++
- VB
---

# GetListingsByIds Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetListingsByIds ( _
    catalogId As Long, _
    listings As ICollection(Of ProductListing) _
) As ICollection(Of ListingIdentity)
'Usage
Dim catalogId As Long
Dim listings As ICollection(Of ProductListing)
Dim returnValue As ICollection(Of ListingIdentity)

returnValue = ChannelCatalogManager.GetListingsByIds(catalogId, _
    listings)
```

``` csharp
public static ICollection<ListingIdentity> GetListingsByIds(
    long catalogId,
    ICollection<ProductListing> listings
)
```

``` c++
public:
static ICollection<ListingIdentity^>^ GetListingsByIds(
    long long catalogId, 
    ICollection<ProductListing^>^ listings
)
```

#### Parameters

  - catalogId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - listings  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[ProductListing](productlisting-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)\>  

#### Return Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[ListingIdentity](listingidentity-class-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)\>  

## See Also

#### Reference

[ChannelCatalogManager Class](channelcatalogmanager-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)

