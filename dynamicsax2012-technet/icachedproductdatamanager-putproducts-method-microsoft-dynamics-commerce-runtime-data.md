---
title: ICachedProductDataManager.PutProducts Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutProducts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedProductDataManager.PutProducts(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchResult,Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedproductdatamanager.putproducts(v=AX.60)
ms:contentKeyID: 65319607
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedProductDataManager.PutProducts
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
Sub PutProducts ( _
    searchResult As ProductSearchResult, _
    criteria As ProductSearchCriteria _
)
'Usage
Dim instance As ICachedProductDataManager
Dim searchResult As ProductSearchResult
Dim criteria As ProductSearchCriteria

instance.PutProducts(searchResult, criteria)
```

``` csharp
void PutProducts(
    ProductSearchResult searchResult,
    ProductSearchCriteria criteria
)
```

``` c++
void PutProducts(
    ProductSearchResult^ searchResult, 
    ProductSearchCriteria^ criteria
)
```

#### Parameters

  - searchResult  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchResult](productsearchresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - criteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ICachedProductDataManager Interface](icachedproductdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

