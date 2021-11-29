---
title: ICachedProductDataManager.PutProduct Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutProduct Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ICachedProductDataManager.PutProduct(Microsoft.Dynamics.Commerce.Runtime.DataModel.Product,Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.icachedproductdatamanager.putproduct(v=AX.60)
ms:contentKeyID: 65316828
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ICachedProductDataManager.PutProduct
dev_langs:
- CSharp
- C++
- VB
---

# PutProduct Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Sub PutProduct ( _
    product As Product, _
    criteria As ProductSearchCriteria _
)
'Usage
Dim instance As ICachedProductDataManager
Dim product As Product
Dim criteria As ProductSearchCriteria

instance.PutProduct(product, criteria)
```

``` csharp
void PutProduct(
    Product product,
    ProductSearchCriteria criteria
)
```

``` c++
void PutProduct(
    Product^ product, 
    ProductSearchCriteria^ criteria
)
```

#### Parameters

  - product  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Product](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - criteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ICachedProductDataManager Interface](icachedproductdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

