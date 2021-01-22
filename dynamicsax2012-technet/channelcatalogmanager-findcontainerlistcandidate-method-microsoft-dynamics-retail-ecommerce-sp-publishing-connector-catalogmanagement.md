---
title: ChannelCatalogManager.FindContainerListCandidate Method  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement)
TOCTitle: FindContainerListCandidate Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ChannelCatalogManager.FindContainerListCandidate(Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductListing,System.Boolean,Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductList)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.catalogmanagement.channelcatalogmanager.findcontainerlistcandidate(v=AX.60)
ms:contentKeyID: 65315724
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ChannelCatalogManager.FindContainerListCandidate
dev_langs:
- CSharp
- C++
- VB
---

# FindContainerListCandidate Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Protected Function FindContainerListCandidate ( _
    listing As ProductListing, _
    useBestFit As Boolean, _
    listHint As ProductList _
) As ProductList
'Usage
Dim listing As ProductListing
Dim useBestFit As Boolean
Dim listHint As ProductList
Dim returnValue As ProductList

returnValue = Me.FindContainerListCandidate(listing, _
    useBestFit, listHint)
```

``` csharp
protected ProductList FindContainerListCandidate(
    ProductListing listing,
    bool useBestFit,
    ProductList listHint
)
```

``` c++
protected:
ProductList^ FindContainerListCandidate(
    ProductListing^ listing, 
    bool useBestFit, 
    ProductList^ listHint
)
```

#### Parameters

  - listing  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductListing](productlisting-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)  

<!-- end list -->

  - useBestFit  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - listHint  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductList](productlist-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductList](productlist-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)  

## See Also

#### Reference

[ChannelCatalogManager Class](channelcatalogmanager-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)

