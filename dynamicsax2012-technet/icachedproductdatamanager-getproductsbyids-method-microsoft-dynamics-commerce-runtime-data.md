---
title: ICachedProductDataManager.GetProductsByIds Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetProductsByIds Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedProductDataManager.GetProductsByIds(System.Collections.Generic.IList{System.Int64},Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria,System.Collections.Generic.List{System.Int64}@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedproductdatamanager.getproductsbyids(v=AX.60)
ms:contentKeyID: 65319348
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedProductDataManager.GetProductsByIds
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
Function GetProductsByIds ( _
    productIds As IList(Of Long), _
    criteria As ProductSearchCriteria, _
    <OutAttribute> ByRef missed As List(Of Long) _
) As ProductSearchResult
'Usage
Dim instance As ICachedProductDataManager
Dim productIds As IList(Of Long)
Dim criteria As ProductSearchCriteria
Dim missed As List(Of Long)
Dim returnValue As ProductSearchResult

returnValue = instance.GetProductsByIds(productIds, _
    criteria, missed)
```

``` csharp
ProductSearchResult GetProductsByIds(
    IList<long> productIds,
    ProductSearchCriteria criteria,
    out List<long> missed
)
```

``` c++
ProductSearchResult^ GetProductsByIds(
    IList<long long>^ productIds, 
    ProductSearchCriteria^ criteria, 
    [OutAttribute] List<long long>^% missed
)
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

## See Also

#### Reference

[ICachedProductDataManager Interface](icachedproductdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

