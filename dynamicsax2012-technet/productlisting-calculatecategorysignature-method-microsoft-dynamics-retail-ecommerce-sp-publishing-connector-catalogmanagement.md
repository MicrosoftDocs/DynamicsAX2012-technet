---
title: ProductListing.CalculateCategorySignature Method  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement)
TOCTitle: CalculateCategorySignature Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductListing.CalculateCategorySignature(System.Collections.Generic.IDictionary{System.Int64,Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductCategory})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.catalogmanagement.productlisting.calculatecategorysignature(v=AX.60)
ms:contentKeyID: 65316423
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductListing.CalculateCategorySignature
dev_langs:
- CSharp
- C++
- VB
---

# CalculateCategorySignature Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Sub CalculateCategorySignature ( _
    categorySpace As IDictionary(Of Long, ProductCategory) _
)
'Usage
Dim instance As ProductListing
Dim categorySpace As IDictionary(Of Long, ProductCategory)

instance.CalculateCategorySignature(categorySpace)
```

``` csharp
public void CalculateCategorySignature(
    IDictionary<long, ProductCategory> categorySpace
)
```

``` c++
public:
void CalculateCategorySignature(
    IDictionary<long long, ProductCategory^>^ categorySpace
)
```

#### Parameters

  - categorySpace  
    Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)), [ProductCategory](productcategory-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)\>  

## See Also

#### Reference

[ProductListing Class](productlisting-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)

