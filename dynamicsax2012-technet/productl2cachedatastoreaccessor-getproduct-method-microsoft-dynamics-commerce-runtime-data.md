---
title: ProductL2CacheDataStoreAccessor.GetProduct Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetProduct Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor.GetProduct(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.productl2cachedatastoreaccessor.getproduct(v=AX.60)
ms:contentKeyID: 65322741
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor.GetProduct
dev_langs:
- CSharp
- C++
- VB
---

# GetProduct Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetProduct ( _
    productId As Long, _
    criteria As ProductSearchCriteria _
) As Product
'Usage
Dim instance As ProductL2CacheDataStoreAccessor
Dim productId As Long
Dim criteria As ProductSearchCriteria
Dim returnValue As Product

returnValue = instance.GetProduct(productId, _
    criteria)
```

``` csharp
public Product GetProduct(
    long productId,
    ProductSearchCriteria criteria
)
```

``` c++
public:
Product^ GetProduct(
    long long productId, 
    ProductSearchCriteria^ criteria
)
```

#### Parameters

  - productId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - criteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Product](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ProductL2CacheDataStoreAccessor Class](productl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

