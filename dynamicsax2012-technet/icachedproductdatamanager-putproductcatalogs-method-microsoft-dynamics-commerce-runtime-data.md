---
title: ICachedProductDataManager.PutProductCatalogs Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutProductCatalogs Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedProductDataManager.PutProductCatalogs(Microsoft.Dynamics.Commerce.Runtime.DataModel.CatalogSearchCriteria,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalog})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedproductdatamanager.putproductcatalogs(v=AX.60)
ms:contentKeyID: 65322719
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedProductDataManager.PutProductCatalogs
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
Sub PutProductCatalogs ( _
    queryCriteria As CatalogSearchCriteria, _
    querySettings As QueryResultSettings, _
    result As ReadOnlyCollection(Of ProductCatalog) _
)
'Usage
Dim instance As ICachedProductDataManager
Dim queryCriteria As CatalogSearchCriteria
Dim querySettings As QueryResultSettings
Dim result As ReadOnlyCollection(Of ProductCatalog)

instance.PutProductCatalogs(queryCriteria, _
    querySettings, result)
```

``` csharp
void PutProductCatalogs(
    CatalogSearchCriteria queryCriteria,
    QueryResultSettings querySettings,
    ReadOnlyCollection<ProductCatalog> result
)
```

``` c++
void PutProductCatalogs(
    CatalogSearchCriteria^ queryCriteria, 
    QueryResultSettings^ querySettings, 
    ReadOnlyCollection<ProductCatalog^>^ result
)
```

#### Parameters

  - queryCriteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CatalogSearchCriteria](catalogsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - querySettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductCatalog](productcatalog-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ICachedProductDataManager Interface](icachedproductdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

