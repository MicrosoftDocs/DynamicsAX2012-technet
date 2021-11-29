---
title: ChannelCatalogManager.LoadListingMap Method  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement)
TOCTitle: LoadListingMap Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ChannelCatalogManager.LoadListingMap(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Channels.Listing})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.catalogmanagement.channelcatalogmanager.loadlistingmap(v=AX.60)
ms:contentKeyID: 65316593
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ChannelCatalogManager.LoadListingMap
dev_langs:
- CSharp
- C++
- VB
---

# LoadListingMap Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function LoadListingMap ( _
    listings As IEnumerable(Of Listing) _
) As CatalogListingMap
'Usage
Dim listings As IEnumerable(Of Listing)
Dim returnValue As CatalogListingMap

returnValue = ChannelCatalogManager.LoadListingMap(listings)
```

``` csharp
protected static CatalogListingMap LoadListingMap(
    IEnumerable<Listing> listings
)
```

``` c++
protected:
static CatalogListingMap^ LoadListingMap(
    IEnumerable<Listing^>^ listings
)
```

#### Parameters

  - listings  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Listing](listing-class-microsoft-dynamics-retail-channels.md)\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.CatalogListingMap](cataloglistingmap-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)  

## See Also

#### Reference

[ChannelCatalogManager Class](channelcatalogmanager-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)

