---
title: ProductDatabaseAccessor.VerifyProductsExistence Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: VerifyProductsExistence Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductDatabaseAccessor.VerifyProductsExistence(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductExistenceCriteria)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.productdatabaseaccessor.verifyproductsexistence(v=AX.60)
ms:contentKeyID: 62213028
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductDatabaseAccessor.VerifyProductsExistence
dev_langs:
- CSharp
- C++
- VB
---

# VerifyProductsExistence Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Verifies existance of products by given composite IDs.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function VerifyProductsExistence ( _
    criteria As ProductExistenceCriteria _
) As ReadOnlyCollection(Of ProductExistenceId)
'Usage
Dim instance As ProductDatabaseAccessor
Dim criteria As ProductExistenceCriteria
Dim returnValue As ReadOnlyCollection(Of ProductExistenceId)

returnValue = instance.VerifyProductsExistence(criteria)
```

``` csharp
public ReadOnlyCollection<ProductExistenceId> VerifyProductsExistence(
    ProductExistenceCriteria criteria
)
```

``` c++
public:
ReadOnlyCollection<ProductExistenceId^>^ VerifyProductsExistence(
    ProductExistenceCriteria^ criteria
)
```

#### Parameters

  - criteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductExistenceCriteria](productexistencecriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductExistenceId](productexistenceid-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Collection of verified IDs.  

## See Also

#### Reference

[ProductDatabaseAccessor Class](productdatabaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

