---
title: ChannelCatalogManager.ProcessListings Method  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement)
TOCTitle: ProcessListings Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ChannelCatalogManager.ProcessListings(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Channels.Listing},Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.CatalogListingMap,System.Collections.Generic.ICollection{Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductListing},System.Collections.Generic.ICollection{Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductListing})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.catalogmanagement.channelcatalogmanager.processlistings(v=AX.60)
ms:contentKeyID: 65315709
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ChannelCatalogManager.ProcessListings
dev_langs:
- CSharp
- C++
- VB
---

# ProcessListings Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Protected Function ProcessListings ( _
    inputListings As IEnumerable(Of Listing), _
    listingMap As CatalogListingMap, _
    unprocessedListings As ICollection(Of ProductListing), _
    uncategorizedListings As ICollection(Of ProductListing) _
) As Integer
'Usage
Dim inputListings As IEnumerable(Of Listing)
Dim listingMap As CatalogListingMap
Dim unprocessedListings As ICollection(Of ProductListing)
Dim uncategorizedListings As ICollection(Of ProductListing)
Dim returnValue As Integer

returnValue = Me.ProcessListings(inputListings, _
    listingMap, unprocessedListings, _
    uncategorizedListings)
```

``` csharp
protected int ProcessListings(
    IEnumerable<Listing> inputListings,
    CatalogListingMap listingMap,
    ICollection<ProductListing> unprocessedListings,
    ICollection<ProductListing> uncategorizedListings
)
```

``` c++
protected:
int ProcessListings(
    IEnumerable<Listing^>^ inputListings, 
    CatalogListingMap^ listingMap, 
    ICollection<ProductListing^>^ unprocessedListings, 
    ICollection<ProductListing^>^ uncategorizedListings
)
```

#### Parameters

  - inputListings  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Listing](listing-class-microsoft-dynamics-retail-channels.md)\>  

<!-- end list -->

  - listingMap  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.CatalogListingMap](cataloglistingmap-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)  

<!-- end list -->

  - unprocessedListings  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[ProductListing](productlisting-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)\>  

<!-- end list -->

  - uncategorizedListings  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[ProductListing](productlisting-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)\>  

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[ChannelCatalogManager Class](channelcatalogmanager-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)

