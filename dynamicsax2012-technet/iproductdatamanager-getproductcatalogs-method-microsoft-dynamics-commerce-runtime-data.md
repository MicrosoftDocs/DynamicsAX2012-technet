---
title: IProductDataManager.GetProductCatalogs Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetProductCatalogs Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IProductDataManager.GetProductCatalogs(Microsoft.Dynamics.Commerce.Runtime.DataModel.CatalogSearchCriteria,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.iproductdatamanager.getproductcatalogs(v=AX.60)
ms:contentKeyID: 65315620
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IProductDataManager.GetProductCatalogs
dev_langs:
- CSharp
- C++
- VB
---

# GetProductCatalogs Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetProductCatalogs ( _
    queryCriteria As CatalogSearchCriteria, _
    querySettings As QueryResultSettings _
) As ReadOnlyCollection(Of ProductCatalog)
'Usage
Dim instance As IProductDataManager
Dim queryCriteria As CatalogSearchCriteria
Dim querySettings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of ProductCatalog)

returnValue = instance.GetProductCatalogs(queryCriteria, _
    querySettings)
```

``` csharp
ReadOnlyCollection<ProductCatalog> GetProductCatalogs(
    CatalogSearchCriteria queryCriteria,
    QueryResultSettings querySettings
)
```

``` c++
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

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ProductCatalog](productcatalog-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[IProductDataManager Interface](iproductdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

