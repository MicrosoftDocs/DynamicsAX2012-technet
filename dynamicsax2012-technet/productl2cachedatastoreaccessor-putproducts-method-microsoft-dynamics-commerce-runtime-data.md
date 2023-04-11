---
title: ProductL2CacheDataStoreAccessor.PutProducts Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutProducts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor.PutProducts(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchResult,Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.productl2cachedatastoreaccessor.putproducts(v=AX.60)
ms:contentKeyID: 65322788
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor.PutProducts
dev_langs:
- CSharp
- C++
- VB
---

# PutProducts Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub PutProducts ( _
    searchResult As ProductSearchResult, _
    criteria As ProductSearchCriteria _
)
'Usage
Dim instance As ProductL2CacheDataStoreAccessor
Dim searchResult As ProductSearchResult
Dim criteria As ProductSearchCriteria

instance.PutProducts(searchResult, criteria)
```

``` csharp
public void PutProducts(
    ProductSearchResult searchResult,
    ProductSearchCriteria criteria
)
```

``` c++
public:
virtual void PutProducts(
    ProductSearchResult^ searchResult, 
    ProductSearchCriteria^ criteria
) sealed
```

#### Parameters

  - searchResult  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchResult](productsearchresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - criteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Implements

[ICachedProductDataManager.PutProducts(ProductSearchResult, ProductSearchCriteria)](icachedproductdatamanager-putproducts-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ProductL2CacheDataStoreAccessor Class](productl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

