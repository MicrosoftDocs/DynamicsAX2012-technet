---
title: ChannelCatalogManager.CatalogListings Method  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement)
TOCTitle: CatalogListings Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ChannelCatalogManager.CatalogListings(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Channels.Listing},System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.AttributeProductListing}@,System.Collections.Generic.ICollection{Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductListing}@,System.Collections.Generic.ICollection{Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductListing}@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.catalogmanagement.channelcatalogmanager.cataloglistings(v=AX.60)
ms:contentKeyID: 65318407
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ChannelCatalogManager.CatalogListings
dev_langs:
- CSharp
- C++
- VB
---

# CatalogListings Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Function CatalogListings ( _
    inputListings As IEnumerable(Of Listing), _
    <OutAttribute> ByRef attributeSpace As IEnumerable(Of AttributeProductListing), _
    <OutAttribute> ByRef unprocessedListings As ICollection(Of ProductListing), _
    <OutAttribute> ByRef uncategorizedListings As ICollection(Of ProductListing) _
) As ICollection(Of ProductList)
'Usage
Dim instance As ChannelCatalogManager
Dim inputListings As IEnumerable(Of Listing)
Dim attributeSpace As IEnumerable(Of AttributeProductListing)
Dim unprocessedListings As ICollection(Of ProductListing)
Dim uncategorizedListings As ICollection(Of ProductListing)
Dim returnValue As ICollection(Of ProductList)

returnValue = instance.CatalogListings(inputListings, _
    attributeSpace, unprocessedListings, _
    uncategorizedListings)
```

``` csharp
public ICollection<ProductList> CatalogListings(
    IEnumerable<Listing> inputListings,
    out IEnumerable<AttributeProductListing> attributeSpace,
    out ICollection<ProductListing> unprocessedListings,
    out ICollection<ProductListing> uncategorizedListings
)
```

``` c++
public:
ICollection<ProductList^>^ CatalogListings(
    IEnumerable<Listing^>^ inputListings, 
    [OutAttribute] IEnumerable<AttributeProductListing^>^% attributeSpace, 
    [OutAttribute] ICollection<ProductListing^>^% unprocessedListings, 
    [OutAttribute] ICollection<ProductListing^>^% uncategorizedListings
)
```

#### Parameters

  - inputListings  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Listing](listing-class-microsoft-dynamics-retail-channels.md)\>  

<!-- end list -->

  - attributeSpace  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[AttributeProductListing](attributeproductlisting-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)\>  

<!-- end list -->

  - unprocessedListings  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[ProductListing](productlisting-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)\>  

<!-- end list -->

  - uncategorizedListings  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[ProductListing](productlisting-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)\>  

#### Return Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[ProductList](productlist-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)\>  

## See Also

#### Reference

[ChannelCatalogManager Class](channelcatalogmanager-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)

