---
title: ProductL2CacheDataStoreAccessor.PutProduct Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutProduct Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor.PutProduct(Microsoft.Dynamics.Commerce.Runtime.DataModel.Product,Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.productl2cachedatastoreaccessor.putproduct(v=AX.60)
ms:contentKeyID: 65320677
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductL2CacheDataStoreAccessor.PutProduct
dev_langs:
- CSharp
- C++
- VB
---

# PutProduct Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub PutProduct ( _
    product As Product, _
    criteria As ProductSearchCriteria _
)
'Usage
Dim instance As ProductL2CacheDataStoreAccessor
Dim product As Product
Dim criteria As ProductSearchCriteria

instance.PutProduct(product, criteria)
```

``` csharp
public void PutProduct(
    Product product,
    ProductSearchCriteria criteria
)
```

``` c++
public:
virtual void PutProduct(
    Product^ product, 
    ProductSearchCriteria^ criteria
) sealed
```

#### Parameters

  - product  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Product](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - criteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Implements

[ICachedProductDataManager.PutProduct(Product, ProductSearchCriteria)](icachedproductdatamanager-putproduct-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ProductL2CacheDataStoreAccessor Class](productl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

