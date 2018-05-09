---
title: ProductL2CacheDataStoreAccessor.PutProductCatalogs Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutProductCatalogs Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor.PutProductCatalogs(Microsoft.Dynamics.Commerce.Runtime.DataModel.CatalogSearchCriteria,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalog})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.productl2cachedatastoreaccessor.putproductcatalogs(v=AX.60)
ms:contentKeyID: 65319683
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor.PutProductCatalogs
dev_langs:
- CSharp
- C++
- VB
---

# PutProductCatalogs Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub PutProductCatalogs ( _
    queryCriteria As CatalogSearchCriteria, _
    querySettings As QueryResultSettings, _
    result As ReadOnlyCollection(Of ProductCatalog) _
)
'Usage
Dim instance As ProductL2CacheDataStoreAccessor
Dim queryCriteria As CatalogSearchCriteria
Dim querySettings As QueryResultSettings
Dim result As ReadOnlyCollection(Of ProductCatalog)

instance.PutProductCatalogs(queryCriteria, _
    querySettings, result)
```

``` csharp
public void PutProductCatalogs(
    CatalogSearchCriteria queryCriteria,
    QueryResultSettings querySettings,
    ReadOnlyCollection<ProductCatalog> result
)
```

``` c++
public:
virtual void PutProductCatalogs(
    CatalogSearchCriteria^ queryCriteria, 
    QueryResultSettings^ querySettings, 
    ReadOnlyCollection<ProductCatalog^>^ result
) sealed
```

#### Parameters

  - queryCriteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CatalogSearchCriteria](catalogsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - querySettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ProductCatalog](productcatalog-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Implements

[ICachedProductDataManager.PutProductCatalogs(CatalogSearchCriteria, QueryResultSettings, ReadOnlyCollection\<ProductCatalog\>)](icachedproductdatamanager-putproductcatalogs-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ProductL2CacheDataStoreAccessor Class](productl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

