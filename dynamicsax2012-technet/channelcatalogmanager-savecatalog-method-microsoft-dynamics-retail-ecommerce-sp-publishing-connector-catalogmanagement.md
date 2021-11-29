---
title: ChannelCatalogManager.SaveCatalog Method  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement)
TOCTitle: SaveCatalog Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ChannelCatalogManager.SaveCatalog(System.Int64,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.Publisher)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.catalogmanagement.channelcatalogmanager.savecatalog(v=AX.60)
ms:contentKeyID: 65315921
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ChannelCatalogManager.SaveCatalog
dev_langs:
- CSharp
- C++
- VB
---

# SaveCatalog Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Shared Sub SaveCatalog ( _
    catalogId As Long, _
    publisher As Publisher _
)
'Usage
Dim catalogId As Long
Dim publisher As Publisher

ChannelCatalogManager.SaveCatalog(catalogId, publisher)
```

``` csharp
public static void SaveCatalog(
    long catalogId,
    Publisher publisher
)
```

``` c++
public:
static void SaveCatalog(
    long long catalogId, 
    Publisher^ publisher
)
```

#### Parameters

  - catalogId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - publisher  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.Publisher](publisher-class-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)  

## See Also

#### Reference

[ChannelCatalogManager Class](channelcatalogmanager-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)

