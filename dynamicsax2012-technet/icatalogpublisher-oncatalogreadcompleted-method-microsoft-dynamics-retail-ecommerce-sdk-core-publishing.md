---
title: ICatalogPublisher.OnCatalogReadCompleted Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing)
TOCTitle: OnCatalogReadCompleted Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.ICatalogPublisher.OnCatalogReadCompleted(System.Int64,Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.Publisher)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.publishing.icatalogpublisher.oncatalogreadcompleted(v=AX.60)
ms:contentKeyID: 65318523
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.ICatalogPublisher.OnCatalogReadCompleted
dev_langs:
- CSharp
- C++
- VB
---

# OnCatalogReadCompleted Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Sub OnCatalogReadCompleted ( _
    catalogId As Long, _
    publisher As Publisher _
)
'Usage
Dim instance As ICatalogPublisher
Dim catalogId As Long
Dim publisher As Publisher

instance.OnCatalogReadCompleted(catalogId, _
    publisher)
```

``` csharp
void OnCatalogReadCompleted(
    long catalogId,
    Publisher publisher
)
```

``` c++
void OnCatalogReadCompleted(
    long long catalogId, 
    Publisher^ publisher
)
```

#### Parameters

  - catalogId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - publisher  
    Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.Publisher](publisher-class-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)  

## See Also

#### Reference

[ICatalogPublisher Interface](icatalogpublisher-interface-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)

