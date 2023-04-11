---
title: ProductL2CacheDataStoreAccessor.GetProductsByIds Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetProductsByIds Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor.GetProductsByIds(System.Collections.Generic.IList{System.Int64},Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria,System.Collections.Generic.List{System.Int64}@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.productl2cachedatastoreaccessor.getproductsbyids(v=AX.60)
ms:contentKeyID: 65315675
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor.GetProductsByIds
dev_langs:
- CSharp
- C++
- VB
---

# GetProductsByIds Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetProductsByIds ( _
    productIds As IList(Of Long), _
    criteria As ProductSearchCriteria, _
    <OutAttribute> ByRef missed As List(Of Long) _
) As ProductSearchResult
'Usage
Dim instance As ProductL2CacheDataStoreAccessor
Dim productIds As IList(Of Long)
Dim criteria As ProductSearchCriteria
Dim missed As List(Of Long)
Dim returnValue As ProductSearchResult

returnValue = instance.GetProductsByIds(productIds, _
    criteria, missed)
```

``` csharp
public ProductSearchResult GetProductsByIds(
    IList<long> productIds,
    ProductSearchCriteria criteria,
    out List<long> missed
)
```

``` c++
public:
virtual ProductSearchResult^ GetProductsByIds(
    IList<long long>^ productIds, 
    ProductSearchCriteria^ criteria, 
    [OutAttribute] List<long long>^% missed
) sealed
```

#### Parameters

  - productIds  
    Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - criteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - missed  
    Type: [System.Collections.Generic.List](https://technet.microsoft.com/library/6sh2ey19\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchResult](productsearchresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Implements

[ICachedProductDataManager.GetProductsByIds(IList\<Int64\>, ProductSearchCriteria, List\<Int64\>)](icachedproductdatamanager-getproductsbyids-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ProductL2CacheDataStoreAccessor Class](productl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

