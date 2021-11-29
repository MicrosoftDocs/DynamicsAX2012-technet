---
title: ProductL2CacheDataStoreAccessor.GetProductCatalogs Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetProductCatalogs Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor.GetProductCatalogs(Microsoft.Dynamics.Commerce.Runtime.DataModel.CatalogSearchCriteria,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.productl2cachedatastoreaccessor.getproductcatalogs(v=AX.60)
ms:contentKeyID: 65319309
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor.GetProductCatalogs
dev_langs:
- CSharp
- C++
- VB
---

# GetProductCatalogs Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetProductCatalogs ( _
    queryCriteria As CatalogSearchCriteria, _
    querySettings As QueryResultSettings _
) As ReadOnlyCollection(Of ProductCatalog)
'Usage
Dim instance As ProductL2CacheDataStoreAccessor
Dim queryCriteria As CatalogSearchCriteria
Dim querySettings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of ProductCatalog)

returnValue = instance.GetProductCatalogs(queryCriteria, _
    querySettings)
```

``` csharp
public ReadOnlyCollection<ProductCatalog> GetProductCatalogs(
    CatalogSearchCriteria queryCriteria,
    QueryResultSettings querySettings
)
```

``` c++
public:
ReadOnlyCollection<ProductCatalog^>^ GetProductCatalogs(
    CatalogSearchCriteria^ queryCriteria, 
    QueryResultSettings^ querySettings
)
```

#### Parameters

  - queryCriteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CatalogSearchCriteria](catalogsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - querySettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductCatalog](productcatalog-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ProductL2CacheDataStoreAccessor Class](productl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

