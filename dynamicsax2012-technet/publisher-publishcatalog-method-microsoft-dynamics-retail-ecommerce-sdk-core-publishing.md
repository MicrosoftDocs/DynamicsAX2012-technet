---
title: Publisher.PublishCatalog Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing)
TOCTitle: PublishCatalog Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.Publisher.PublishCatalog(Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.ICatalogPublisher)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.publishing.publisher.publishcatalog(v=AX.60)
ms:contentKeyID: 65316134
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.Publisher.PublishCatalog
dev_langs:
- CSharp
- C++
- VB
---

# PublishCatalog Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Function PublishCatalog ( _
    catalogPublisher As ICatalogPublisher _
) As Boolean
'Usage
Dim instance As Publisher
Dim catalogPublisher As ICatalogPublisher
Dim returnValue As Boolean

returnValue = instance.PublishCatalog(catalogPublisher)
```

``` csharp
public bool PublishCatalog(
    ICatalogPublisher catalogPublisher
)
```

``` c++
public:
bool PublishCatalog(
    ICatalogPublisher^ catalogPublisher
)
```

#### Parameters

  - catalogPublisher  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.ICatalogPublisher](icatalogpublisher-interface-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[Publisher Class](publisher-class-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)

