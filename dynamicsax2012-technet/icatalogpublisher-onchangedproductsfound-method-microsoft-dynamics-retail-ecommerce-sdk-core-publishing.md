---
title: ICatalogPublisher.OnChangedProductsFound Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing)
TOCTitle: OnChangedProductsFound Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.ICatalogPublisher.OnChangedProductsFound(Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangedProductsSearchResult,System.Int32,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.publishing.icatalogpublisher.onchangedproductsfound(v=AX.60)
ms:contentKeyID: 65317411
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.ICatalogPublisher.OnChangedProductsFound
dev_langs:
- CSharp
- C++
- VB
---

# OnChangedProductsFound Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Sub OnChangedProductsFound ( _
    changedProducts As ChangedProductsSearchResult, _
    pageNumberInCatalog As Integer, _
    catalogId As Long _
)
'Usage
Dim instance As ICatalogPublisher
Dim changedProducts As ChangedProductsSearchResult
Dim pageNumberInCatalog As Integer
Dim catalogId As Long

instance.OnChangedProductsFound(changedProducts, _
    pageNumberInCatalog, catalogId)
```

``` csharp
void OnChangedProductsFound(
    ChangedProductsSearchResult changedProducts,
    int pageNumberInCatalog,
    long catalogId
)
```

``` c++
void OnChangedProductsFound(
    ChangedProductsSearchResult^ changedProducts, 
    int pageNumberInCatalog, 
    long long catalogId
)
```

#### Parameters

  - changedProducts  
    Type: ChangedProductsSearchResult  

<!-- end list -->

  - pageNumberInCatalog  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - catalogId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[ICatalogPublisher Interface](icatalogpublisher-interface-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)

